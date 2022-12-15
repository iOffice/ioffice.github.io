# Group Centers
Centers-related resources of *iOffice API*

## Centers [/centers{?module}]
Collection of all Centers

### Retrieve All Centers [GET /centers{?module}]
This API returns list of all centers in particular module

The following attributes are required to get list of centers: `module`.

+ Parameters
  + module (string, `reservation`) ... Module name

+ Response 200

      [
         {
            "name": "Reservation Center",
            "id": 82
         },
         {
            "name": "London Reservation Center",
            "id": 95
         },
         {
            "name": "Maine Reservation Center",
            "id": 106
         }
         ...
      ]

### Center Details With All Building And Rules [GET /centers/{centerId}{?selector}]

This API returns the details of a particular center with list of all buildings

+ Parameters
  + centerId (number, `145`) ... Reservations Center ID
  + selector (string, `buildings(centers(module))%2Crules`) ... Selector ID (returns exact response with 'buildings(centers(module))%2Crules')

+ Response 200

        {
           "buildings": [
              {
                 "code": "",
                 "centers": [
                    {
                       "module": "reservation",
                       "name": "Houston Reservation Center - 24 hour",
                       "id": 145
                    }
                 ],
                 "name": "ATest1951",
                 "id": 1332
              },
              {
                 "code": "",
                 "centers": [
                    {
                       "module": "reservation",
                       "name": "Houston Reservation Center - 24 hour",
                       "id": 145
                    }
                 ],
                 "name": "ATest1853",
                 "id": 1223
              },
              ...
           ],
           "name": "Houston Reservation Center - 24 hour",
           "rules": "{\"centerId\":145,\"ruleList\":[{\"roomTypeId\":2,\"$type$\":\"OnlyDuringWorkHours\"}]}",
           "id": 145
        }

## Center Promo Content [/center///{?module,selector}]
Promo Content Collection          

### Retrieve Center Promo Content [GET /center///{?module,selector}]
The following attributes are required to get Promo Content details: `module`, `selector`.

+ Parameters
  + module (string, `reservation`) ... Module name
  + selector (string, `id%2Cname%2CpromoContent`) ... Selector ID

+ Response 200

          [
              {
                  "promoContent": [],
                  "name": "Test",
                  "id": 177
              },
              {
                  "promoContent": [],
                  "name": "SiteAdmin4388",
                  "id": 178
              },
              {
                  "promoContent": [],
                  "name": "SiteAdmin4388",
                  "id": 179
              }
              ...
          ]

### Retrieve Center Name With Promo Content [PUT /centers/promo]

+ Request (application/json)

        {
           "centerId":82,
           "promoContent": 
           [
              "<p><a href=\"https://www.iofficecorp.com/\" rel=\"noopener noreferrer\" target=\"_blank\"><img src=\"https://www.iofficecorp.com/hubfs/2017/Marketplace/ioffice-wheel-2.png?t=1519997685552\"></a></p>",
              "<p><a href=\"https://www.yahoo.com\" rel=\"noopener noreferrer\" target=\"_blank\"><img src=\"https://i.ibb.co/94HpJFj/Screenshot-1.jpg\"></a></p>",
              "<p><img src=\"https://i.ibb.co/7ktkjr6/Screen-Shot-2021-04-21-at-10-57-10-AM.png\"></p>",
              "<p><a href=\"https://hq.iofficeconnect.com/home.i#/admin/users\" rel=\"noopener noreferrer\" target=\"_blank\">HQ SIte</a></p>",
              "<p><img src=\"https://s3.eu-central-1.amazonaws.com/rainforest-random-images/004.jpeg\"></p>"
          ]
        }

+ Response 200

      {
          "name": "Reservation Center",
          "id": 82
      }
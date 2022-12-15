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
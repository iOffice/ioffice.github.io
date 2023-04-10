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

## Holidays [/centers/holidays]

### Retrieve Collection of Holidays [GET]

+ Response 200
		[
		  {
			"holidayItems": [
			  {
				"date": "2019-09-25",
				"id": 255
			  },
			  {
				"date": "2019-09-27",
				"id": 256
			  },
			  {
				"date": "2019-10-02",
				"id": 257
			  },
			  {
				"date": "2019-10-10",
				"id": 258
			  },
			  {
				"date": "2019-10-17",
				"id": 259
			  },
			  {
				"date": "2019-10-24",
				"id": 260
			  },
			  {
				"date": "2019-10-31",
				"id": 261
			  },
			  {
				"date": "2019-11-07",
				"id": 262
			  },
			  {
				"date": "2019-11-14",
				"id": 263
			  },
			  {
				"date": "2019-11-21",
				"id": 264
			  },
			  {
				"date": "2019-11-22",
				"id": 265
			  },
			  {
				"date": "2019-11-23",
				"id": 266
			  },
			  {
				"date": "2019-11-24",
				"id": 267
			  },
			  {
				"date": "2019-11-25",
				"id": 268
			  },
			  {
				"date": "2019-11-26",
				"id": 269
			  },
			  {
				"date": "2019-11-27",
				"id": 270
			  },
			  {
				"date": "2019-11-28",
				"id": 271
			  },
			  {
				"date": "2019-11-29",
				"id": 272
			  },
			  {
				"date": "2019-11-30",
				"id": 273
			  },
			  {
				"date": "2019-12-01",
				"id": 274
			  },
			  {
				"date": "2019-12-02",
				"id": 275
			  },
			  {
				"date": "2019-12-03",
				"id": 276
			  },
			  {
				"date": "2019-12-04",
				"id": 277
			  },
			  {
				"date": "2019-12-05",
				"id": 278
			  },
			  {
				"date": "2019-12-06",
				"id": 279
			  },
			  {
				"date": "2019-12-07",
				"id": 280
			  },
			  {
				"date": "2019-12-12",
				"id": 281
			  },
			  {
				"date": "2019-12-19",
				"id": 282
			  },
			  {
				"date": "2019-12-26",
				"id": 283
			  }
			],
			"dateCreated": 1569959521867,
			"name": "Jason's Holidaze",
			"id": 3,
			"dateUpdated": 1570120771210
		  },
		  {
			"holidayItems": [],
			"dateCreated": 1569959531367,
			"name": "blank",
			"id": 4
		  },
		  {
			"holidayItems": [
			  {
				"date": "2020-04-02",
				"id": 288
			  }
			],
			"dateCreated": 1585777491843,
			"name": "april 2",
			"id": 6
		  },
		  {
			"holidayItems": [
			  {
				"date": "2021-07-02",
				"id": 297
			  },
			  {
				"date": "2021-07-03",
				"id": 298
			  },
			  {
				"date": "2021-07-04",
				"id": 299
			  },
			  {
				"date": "2021-07-05",
				"id": 300
			  }
			],
			"dateCreated": 1623857288427,
			"name": "Tara's Test",
			"id": 7,
			"dateUpdated": 1623858023163
		  }
		]

### Add Holiday Schedule [POST]

+ Request (application/json)

	{
	  "name": "Good Friday",
	  "holidayItems": [
		{
		  "date": "2023-04-07"
		}
	  ]
	}
	
+ Response 201
	
	{
	  "holidayItems": [
		{
		  "date": "2023-04-07",
		  "id": 301
		}
	  ],
	  "dateCreated": 1680621740357,
	  "name": "Good Friday",
	  "id": 8
	}

### Update Holiday Schedule [PUT]

+ Request (application/json)

	{
	  "name": "April Holidays",
	  "id": 8,
	  "holidayItems": [
		{
		  "date": "2023-04-07"
		},
		{
		  "date": "2023-04-11"
		},
		{
		  "date": "2023-04-12"
		}
	  ]
	}
	
+ Response 200
	
	{
	  "holidayItems": [
		{
		  "date": "2023-04-07",
		  "id": 302
		},
		{
		  "date": "2023-04-11",
		  "id": 303
		},
		{
		  "date": "2023-04-12",
		  "id": 304
		}
	  ],
	  "dateCreated": 1680621740373,
	  "name": "Good Friday",
	  "id": 8,
	  "dateUpdated": 1680622535176
	}
	
### Retrieve Single Holiday Schedule [GET /centers/holidays/{id}]

+ Parameters
    + id (string) ... ID of the Holiday Schedule

+ Response 200
	{
	  "holidayItems": [
		{
		  "date": "2023-04-07",
		  "id": 301
		}
	  ],
	  "dateCreated": 1680621740373,
	  "name": "Good Friday",
	  "id": 8
	}
	
### Remove Holiday Schedule [DELETE /centers/holidays/{id}]

+ Parameters
    + id (string) ... ID of the Holiday Schedule

+ Response 200
	{"response":"Successfully removed"}

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

### Add/Update Promo Content for a Center [PUT /centers/promo]

This API Add/Updates the Promo Content details for a Reservation Center

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
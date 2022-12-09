# Group Reservation
Reservation-related resources of *iOffice API*

## Reservation [/reservations///{id}]
A single reservation object.


+ Parameters
    + id (string) ... ID of the Reservation

+ Model (application/json)
    JSON representation of the Reservation Resource

    + Body

            {
                "id": ID,
                "center": {...},
                "numberOfPeople": INT,
                "allDay": "BOOLEAN",
                "checkedIn": "BOOLEAN",
                "checkedOut": "BOOLEAN",
                "notes": "STRING"
                "madeInIoffice": "BOOLEAN",
                "name": "STRING",
                "user": {...},
                "dateUpdated": EPOCH_TIME,
                "room": {...}
            }

### Retrieve a Single Reservation [GET]
+ Response 200

    [Reservation][]

### Edit a Reservation [PUT]
To update a Reservation send JSON with the Reservation's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Reservation
    
+ Request (application/json)

        {
        	"id": 23,
            "user": {
                "id": 56
            }
        }

+ Response 200
    
    [Reservation][]

### Remove a Reservation [DELETE]
+ Parameters
    + id (string) ... ID of the Reservation
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

## Reservation Collection [/reservations///{?includeCancelled,includePastReservations,includeNonCancelled,showOnlyMyReservations,startDate,endDate,buildingId,roomId,modifiedOrCreatedAfter}]
Collection of all Reservations.

+ Model (application/json)
    JSON representation of the Reservation Collection resource.

    + Body

            [
                {
                    "id":21
                    ...
                },
                {
                    "id":22
                    ...
                },
                {
                    "id":23
                    ...
                }
            ]

### List of all Reservations [GET]

+ Parameters
    + includeCancelled = `false` (optional, boolean, , `true`) ... If true, query will include cancelled reservations
    + includeNonCancelled = `true` (optional, boolean, , `false`) ... If true, query will include non-cancelled reservations
    + includePastReservations = `false` (optional, boolean, `true`) ... If true, query will include past reservations
    + showOnlyMyReservations = `true` (optional, boolean, `false`) ... If true, query will only include logged in user's reservations
    + startDate (optional, number, `1404410211910`) ... Epoch time (milliseconds) of reservation start date
    + endDate (optional, number, `1404421051661`) ... Epoch time (milliseconds) of reservation end date
    + buildingId (optional, number, `44`) ... Id of the building to query from
    + limit (optional, number, `500`) ... Reservations List limit to query from
    + roomId (optional, number, `16`) ... Id of the room to query from
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Reservation Collection][]


### Create a Reservation [POST]
The following attributes are required to create a Reservation: `startDate`, `endDate`, `user`, `room`, `center`, and `allDay`.

+ Request (application/json)

            {
                "startDate": EPOCH_TIME,
                "endDate": EPOCH_TIME
                "numberOfPeople": INT,
                "allDay": "BOOLEAN",
                "name": "STRING",
                "center": {...},
                "user": {...},
                "guests": [..],
                "room": {...},
                "notes": "STRING"
            }

+ Response 201

    [Reservation][]

## Cancel [/reservations///{id}/cancel]
Cancel Reservation

+ Parameters

    + id (string) ... ID of the Reservation

### Cancel Reservation [PUT]
+ Response 200

          {
              "id": ID,
              "cancellationReason": "STRING"
              "cancelled": "BOOLEAN"
              "startDate": EPOCH_TIME,
              "endDate": EPOCH_TIME
              "numberOfPeople": INT,
              "checkedIn": "BOOLEAN",
              "checkedOut": "BOOLEAN",
              "name": "STRING",
              "dateCreated": EPOCH_TIME,
              "dateUpdated": EPOCH_TIME,
              "user": {...},
              "center": {...},
              "room": {...},
              "notes": "STRING"
          }


## Check In [/reservations///{id}/checkIn]
Reservation Check In

+ Parameters

    + id (string) ... ID of the Reservation

### Reservation Check In [PUT]
+ Response 200
    [Reservation][]


## Check Out [/reservations///{id}/checkOut]
Reservation Check Out

*Not available through the desktop app*

+ Parameters

    + id (string) ... ID of the Reservation

### Reservation Check Out [PUT]
+ Response 200
    [Reservation][]

## Reservation Rules [/rooms/types/count]
Reservation Rules related resources of *iOffice API*

### Room Types Count [GET /rooms/types/count]
This API returns count of room types

+ Response 200

      {
          "count": 206
      }

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

### All Room Details [GET /rooms/types{?includes,limit,orderBy}]

This API returns list of all rooms and their specific details

+ Parameters
  + includes (optional, string, `reservable`) ... Type of rooms
  + limit (optional, number, `206`) ... Reservations List limit to query from
  + orderBy (optional, string, `sortOrder`) ... Sort order for records

+ Response 200

          [
              {
                 "hexColor": "ffffff",
                 "contentFlag": 1,
                 "dateCreated": 1612384416513,
                 "cost": 0.0,
                 "color": {},
                 "name": "5SW3.04",
                 "occupiable": false,
                 "id": 195,
                 "parkingSpace": false,
                 "dateUpdated": 1667608296090,
                 "typeCode": "ff"
              },
              {
                 "hexColor": "ffffff",
                 "contentFlag": 3,
                 "dateCreated": 1643385124050,
                 "cost": 0.0,
                 "color": {},
                 "name": "Acc. WC",
                 "occupiable": true,
                 "id": 216,
                 "parkingSpace": false,
                 "dateUpdated": 1667608296600,
                 "typeCode": ""
              },
              ...
          ]

### All Rooms Type and Rules [GET /rooms/types{?limit,selector}]

This API returns list of all rooms and their rules

+ Parameters
  + limit (optional, number, `206`) ... Reservations List limit to query from
  + selector (string, `rules`) ... Selector ID

+ Response 200

          [
              {
                 "name": "WKST",
                 "rules": "{\"roomTypeId\":1,\"ruleList\":[]}",
                 "id": 1
              },
              {
                 "name": "OFFICE",
                 "rules": "{\"roomTypeId\":2,\"ruleList\":[]}",
                 "id": 2
              },
              {
                 "name": "Acc. WC",
                 "rules": "{\"roomTypeId\":216,\"ruleList\":[{\"$type$\":\"OnlyDuringWorkHours\"}]}",
                 "id": 216
              }
              ...
         ]

### Particular Center Rules With All Building [GET /centers/{centerId}{?selector}]

This API returns rules of a particular center and list of all buildings it has

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

### Category Details While Adding Rule [GET /categories/type/1{?limit,selector}]

This API returns category details while adding new rule (after clicking on 'Add Rule' button)

+ Parameters
  + limit (optional, number, `79`) ... Reservations List limit to query from
  + selector (string, `itemCount%2Cdepths`) ... Selector ID (returns exact response with 'itemCount%2Cdepths')

+ Response 200

      [
          {
              "depths": [
                  {
                      "name": "Region",
                      "id": 44
                  },
                  {
                      "name": "Division",
                      "id": 90
                  },
                  {
                      "name": "Country",
                      "id": 46
                  },
                  {
                      "name": "Sub-Region",
                      "id": 45
                  }
              ],
              "name": "_",
              "id": 17,
              "itemCount": 15
          },
          {
              "depths": [
                  {
                      "name": "Day",
                      "id": 646
                  },
                  {
                      "name": "Month",
                      "id": 644
                  },
                  {
                      "name": "Week",
                      "id": 645
                  }
              ],
              "name": "April_20",
              "id": 445,
              "itemCount": 2
          },        
          ...
      ]

### Create Rule (Center - Only During Working Hours) [PUT /centers/reservations/rules{?selector}]

This API creates new rule for Center - Only During Working Hours

*If particular rule is already present, the API still passes*

+ Parameters
  + selector (string, `rules`) ... Selector ID (returns exact response with 'rules')

+ Request (application/json)

        {
           "centerId":82,
           "ruleList":[
              {
                 "$type$":"OnlyDuringWorkHours"
              },
              {
                 "$type$":"OnlyDuringWorkHours",
                 "value":"true",
                 "roomTypeId":179
              }
           ]
        }

+ Response 200

      {
         "name": "Reservation Center",
         "rules": "{\"centerId\":82,\"ruleList\":[{\"$type$\":\"OnlyDuringWorkHours\"},{\"roomTypeId\":179,\"$type$\":\"OnlyDuringWorkHours\"}]}",
         "id": 82
      }

### Delete Rule (Center - Only During Working Hours/Max Duration/Min Duration/Max Lead Time) [PUT /centers/reservations/rules{?selector}]

This API deletes rule for Center - Only During Working Hours, Max Duration, Min Duration and Max Lead Time. 

*These all APIs are treated as 'Only During Working Hours', so these all rules get deleted using single API with same payload*

*If particular rule is already deleted, the API still passes*

+ Parameters
  + selector (string, `rules`) ... Selector ID (returns exact response with 'rules')

+ Request (application/json)

        {
           "centerId":82,
           "ruleList":[
              {
                 "roomTypeId":179,
                 "$type$":"OnlyDuringWorkHours"
              }
          ]
        }

+ Response 200

      {
         "name": "Reservation Center",
         "rules": "{\"centerId\":82,\"ruleList\":[{\"roomTypeId\":179,\"$type$\":\"OnlyDuringWorkHours\"}]}",
         "id": 82
      }

### Create Rule (Center - Max Duration) [PUT /centers/reservations/rules{?selector}]

This API creates rule for Center - Max Duration

*If particular rule is already present, the API still passes*

+ Parameters
  + selector (string, `rules`) ... Selector ID (returns exact response with 'rules')

+ Request (application/json)

        {
           "centerId":82,
           "ruleList":[
              {
                 "roomTypeId":179,
                 "$type$":"OnlyDuringWorkHours"
              },
              {
                 "$type$":"MaxDuration",
                 "value":"1530m"
              }
          ]
        }

+ Response 200

      {
         "name": "Reservation Center",
         "rules": "{\"centerId\":82,\"ruleList\":[{\"roomTypeId\":179,\"$type$\":\"OnlyDuringWorkHours\"},{\"value\":\"1530m\",\"$type$\":\"MaxDuration\"}]}",
         "id": 82
      }

### Create Rule (Center - Min Duration) [PUT /centers/reservations/rules{?selector}]

This API creates rule for Center - Min Duration

*If particular rule is already present, the API still passes*

+ Parameters
  + selector (string, `rules`) ... Selector ID (returns exact response with 'rules')

+ Request (application/json)

        {
           "centerId":82,
           "ruleList":[
              {
                 "roomTypeId":179,
                 "$type$":"OnlyDuringWorkHours"
              },
              {
                 "$type$":"MinimumDuration",
                 "value":"1450m"
              }
           ]
        }

+ Response 200

      {
         "name": "Reservation Center",
         "rules": "{\"centerId\":82,\"ruleList\":[{\"roomTypeId\":179,\"$type$\":\"OnlyDuringWorkHours\"},{\"value\":\"1450m\",\"$type$\":\"MinimumDuration\"}]}",
         "id": 82
      }

### Create Rule (Center - Max Lead Time) [PUT /centers/reservations/rules{?selector}]

This API creates rule for Center - Max Lead Time

*If particular rule is already present, the API still passes*

+ Parameters
  + selector (string, `rules`) ... Selector ID (returns exact response with 'rules')

+ Request (application/json)

        {
           "centerId":82,
           "ruleList":[
              {
                 "roomTypeId":179,
                 "$type$":"OnlyDuringWorkHours"
              },
              {
                 "$type$":"MaxLeadTime",
                 "value":"1505m"
              }
           ]
        }

+ Response 200

      {
         "name": "Reservation Center",
         "rules": "{\"centerId\":82,\"ruleList\":[{\"roomTypeId\":179,\"$type$\":\"OnlyDuringWorkHours\"},{\"value\":\"1505m\",\"$type$\":\"MaxLeadTime\"}]}",
         "id": 82
      }
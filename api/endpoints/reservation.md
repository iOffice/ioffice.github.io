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

### Create/Update/Delete Rule [PUT /centers/reservations/rules{?selector}]

This API creates/updates/deletes particular rule for Space Type, Center, Space and Neighbourhood for selected center

*Rules mentioned in the payload will get created/updated. The rules not mentioned in the payload will get deleted*

*Here, API is simply updating the list of rules available*

+ Parameters
  + selector (string, `rules`) ... Selector ID (returns exact response with 'rules')

+ Request (application/json)

        {
           "centerId": 82,
           "ruleList": [
              {
                 "value": "1510m",
                 "$type$": "MaxDuration"
              },
              {
                 "roomTypeId": 52,
                 "$type$": "OnlyDuringWorkHours"
              },
              {
                 "$type$": "MaxLeadTime",
                 "value": "1580m",
                 "roomId": 41932
              },
              {
                 "$type$": "IncludeAllMembers",
                 "value": "true",
                 "neighborhoodId": 41
             }
           ]
        }

+ Response 200
      {  
         "name": "Reservation Center",
         "rules": "{\"centerId\":82,\"ruleList\":[{\"value\":\"1510m\",\"$type$\":\"MaxDuration\"},{\"roomTypeId\":52,\"$type$\":\"OnlyDuringWorkHours\"},{\"roomId\":41932,\"value\":\"1580m\",\"$type$\":\"MaxLeadTime\"},{\"neighborhoodId\":41,\"$type$\":\"IncludeAllMembers\"}]}",
         "id": 82
      }

## Promo Content []
Promo Content Collection

*Most of the Promo Content related APIs are related to Center section*

### Notification [GET /notifications/{?limit}]
The following attribute is required to get a Notification: `limit`.

+ Parameters
    + limit (optional, number, `500`) ... Reservations List limit to query from

+ Response 200
    []

### Services [GET /system/config/services]

+ Response 200

      {
          "servicesLocation": "https://services-dev.api.iofficeconnect.com",
          "websocketsLocation": "wss://ws-dev.api.iofficeconnect.com",
          "tilesLocation": "https://drawing-tile-default.qa.iofficeconnect.dev/drawings"
      }
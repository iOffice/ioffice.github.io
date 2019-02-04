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
    + startDate (optional, number, `1404410211910`) ... Epoch time of reservation start date
    + endDate (optional, number, `1404421051661`) ... Epoch time of reservation end date
    + buildingId (optional, number, `44`) ... Id of the building to query from
    + roomId (optional, number, `16`) ... Id of the room to query from
    + modifiedOrCreatedAfter (optional, number, '1549319834')... Epoch time to poll recently modified items in the collection.

+ Response 200
    
    [Reservation Collection][]


### Create a Reservation [POST]
The following attributes are required to create a Reservation: `startDate`, `endDate`, `user`, `room`, and `allDay`.

+ Request (application/json)

            {
                "startDate": EPOCH_TIME,
                "endDate": EPOCH_TIME
                "numberOfPeople": INT,
                "allDay": "BOOLEAN",
                "name": "STRING",
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
    [Reservation][]


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

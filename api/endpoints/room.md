# Group Room
Room-related resources of *iOffice API* 

Note: The term "room" has been amended to "space"; all references to a "room" or "rooms" will now be referred to as a "space" or "spaces". This change does not affect current endpoints.  

## Room [/rooms///{id}]
A single room object.


+ Parameters
    + id (string) ... ID of the Room

+ Model (application/json)
    JSON representation of the Room Resource

    + Body

            {
                "id": 52927,
                "floor": {...},
                "reservable": true,
                "name": "010211"
            }

### Retrieve a Single Room [GET]
+ Response 200

    [Room][]

### Edit a Room [PUT]
To update a Room send JSON with the Room's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Room
    
+ Request (application/json)

        {
        	"id": 23,
            "type": {
                "id": 55
            }
        }

+ Response 200
    
    [Room][]

### Remove a Reservation [DELETE]
+ Parameters
    + id (string) ... ID of the Reservation
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

## Room Collection [/rooms///{?includeReservable,includeNonReservable,locationSearch,includeOccupiable,includeNonOccupiable,nearLatitude,nearLongitude,startDate,endDate,numberOfPeople,includeParking,search,buildingId,floorId,type,modifiedOrCreatedAfter}]
Collection of all Rooms.

+ Model (application/json)
    JSON representation of the Room Collection resource.

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

### List of all Rooms [GET]

Note: `floorId` and `buildingId` may be used in tandem but `floorId` will always take preference (i.e. a mismatched buildingId/floorId will not result in an error).

+ Parameters
    + includeReservable (optional, boolean, `true`) ... If true, query will include reservable rooms
    + includeNonReservable (optional, boolean, `false`) ... If true, query will include non-reservable rooms
    + includeOccupiable (optional, boolean, `true`) ... If true, query will include occupiable rooms
    + includeNonOccupiable (optional, boolean, `false`) ... If true, query will include non-occupiable rooms
    + locationSearch (optional, string, `houston tx`) ... Will do a location lookup based on the search string.
    + nearLatitude (optional, number, `29.75613`) ... Latitude to base search on (50 mile radius)
    + nearLongitude (optional, number, `-95.39425`) ... Longitude to base search on (50 mile radius)
    + startDate (optional, number, `1404410211910`) ... Epoch time of room availability start date
    + endDate (optional, number, `1404421051661`) ... Epoch time of room availability end date
    + numberOfPeople (optional, number, `6`) ... Number to search for room by maximum occupancy
    + includeParking (optional, boolean, `true`) ... If true, query will include rooms with parking spaces
    + buildingId (optional, number, `44`) ... Id of building to search in
    + floorId (optional, number, `3443`) ... Id of floor to search on
    + type (optional, number, `65 or 65,32,79`) ... Id of room type to search for (can accept a comma delimited series of Ids)
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time to poll recently modified items in the collection.

+ Response 200
    
    [Room Collection][]

### Create a Room [POST]
The following attributes are required to create a Room: `name`, `floor`, and `type`.

+ Request (application/json)

			{
				"name": "room 101",
				"floor": {
					"id": 16
				},
				"type": {
					"id": 44
				}
			}

+ Response 201

	[Room][]

## Room Types [/rooms/types///{?includeReservable,includeNonReservable,includeOccupiable,includeNonOccupiable,includeParking,modifiedOrCreatedAfter}]
Collection of all Room Types.

+ Model (application/json)
    JSON representation of the Room Types resource.

    + Body

            [
                {
                    "id":21
                    "name":"Office",
                    "sortOrder":5
                }
            ]

### List of all Room Types [GET]
+ Parameters
    + includeReservable (optional, boolean, `true`) ... If true, query will include reservable room types
    + includeNonReservable (optional, boolean, `false`) ... If true, query will include non-reservable room types
    + includeOccupiable (optional, boolean, `true`) ... If true, query will include occupiable room types
    + includeNonOccupiable (optional, boolean, `false`) ... If true, query will include non-occupiable room types
    + includeParking (optional, boolean, `false`) ... If true, query will include parking room types
    + modifiedOrCreatedAfter (optional, number, '1549319834')... Epoch time to poll recently modified items in the collection
    
+ Response 200
	[Room Types][]

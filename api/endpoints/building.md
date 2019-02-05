# Group Building
Building-related resources of *iOffice API*

## Building [/buildings///{id}]
A single building object.


+ Parameters
    + id (string) ... ID of the Building

+ Model (application/json)
    JSON representation of the Building Resource

    + Body

            {
                "id": 43,
                "address": {...},
                "name": "Mystery Inc.",
                "code": "mystery"
            }

### Retrieve a Single Building [GET]
+ Response 200

    [Building][]

### Edit a Building [PUT]
To update a Building send JSON with the Building's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Building
    
+ Request (application/json)

        {
        	"id": 43,
            "address": {
                "postalCode": "77019"
            }
        }

+ Response 200
    
    [Building][]

### Remove a Building [DELETE]
+ Parameters
    + id (string) ... ID of the Building
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

## Building Collection [/buildings///{?includeReservable,includeNonReservable,locationSearch,nearLatitude,nearLongitude,modifiedOrCreatedAfter}]
Collection of all Buildings.

+ Model (application/json)
    JSON representation of the Building Collection resource.

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

### List of all Buildings [GET]

+ Parameters
    + includeReservable (optional, boolean, `true`) ... If true, query will include buildings with reservable rooms
    + includeNonReservable (optional, boolean, `false`) ... If true, query will include buildings with non-reservable rooms
    + locationSearch (optional, string, `houston tx`) ... Will do a location lookup based on the search string.
    + nearLatitude (optional, number, `29.75613`) ... Latitude to base search on (50 mile radius)
    + nearLongitude (optional, number, `-95.39425`) ... Longitude to base search on (50 mile radius)
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time to poll recently modified items in the collection.
    
+ Response 200
    
    [Building Collection][]


### Create a Building [POST]
The following attribute is required to create a Building: `name`.

+ Request (application/json)

            {
                "name": "Headquarters",
            }

+ Response 201

    [Building][]

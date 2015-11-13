# Group Building
Building-related resources of *iOffice API*

## Building [/buildings{id}]
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
To update a Building send JSON with updated value for one or more of the attributes.
    
+ Request (application/json)

        {
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


## Building Collection [/buildings{?includeReservable,includeNonReservable,locationSearch,nearLatitude,nearLongitude}]
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

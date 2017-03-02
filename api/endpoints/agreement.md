# Group Agreement
Agreement-related resources of *iOffice API*

## Agreement [/agreements///{id}]
A single agreement object.


+ Parameters
    + id (string) ... ID of the Agreement

+ Model (application/json)
    JSON representation of the Agreement Resource

    + Body

            {
                "id": 23,
                ...
            }

### Retrieve a Single Agreement [GET]
+ Response 200

    [Agreement][]

### Edit a Agreement [PUT]
To update a Agreement send JSON with the id and updated value for one or more of the attributes.
    
+ Request (application/json)

        {
            "id": 23,
            "attributeName": "value"
        }

+ Response 200
    
    [Agreement][]

### Remove an Agreement [DELETE]
+ Parameters
    + id (string) ... ID of the Agreement
+ Response 200

## Agreement Collection [/agreements]
Collection of all Agreements.

+ Model (application/json)
    JSON representation of the Agreement Collection resource.

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

### List of all Agreements [GET]

+ Response 200
    
    [Agreement Collection][]


### Create a Agreement [POST]
To create a Agreement send JSON with the values the new agreement should have.
The field `type` is required in order to create a new agreement.

+ Response 201

    [Agreement][]



# Group Category  Depth
Category Depth related resources of *iOffice API*

## Depth Collection [/categories/depths]
Collection of all Depths.

+ Model (application/json)
    JSON representation of the Depth Collection Resource

    + Body
    
            [
                {
                    "code": "d1",
                    "dateCreated": 1439399515923,
                    "level": 0,
                    "name": "depth one",
                    "id": 71,
                    "category": {
                        "code": "cat-code",
                        "color": {},
                        "name": "category one",
                        "id": "65"
                    }
                },
                {
                    "code": "d2",
                    "dateCreated": 1439399567183,
                    "level": 0,
                    "name": "depth2",
                    "id": 72
                    "category": {
                        "code": "cat-two",
                        "color": {},
                        "name": "category two",
                        "id": "65"
                    }
                },
                {
                    "code": "d3",
                    "dateCreated": 1439399627200,
                    "level": 1,
                    "name": "depth3",
                    "id": 73
                    "category": {
                        "code": "cat-code",
                        "color": {},
                        "name": "category one",
                        "id": "65"
                    }
                } 
            ]

### List of all Depths [GET]
+ Response 200
    [Depth Collection][]

## Depth [/categories/depth///{id}]
A Single Depth object.

+ Model (application/json)
    JSON representation of the Depth Resource

    + Body

              {
                    "code": "d1",
                    "dateCreated": 1439399515923,
                    "level": 0,
                    "name": "depth one",
                    "id": 71,
                    "category": {
                        "code": "cat-code",
                        "color": {},
                        "name": "category one",
                        "id": "65"
                    }
                }

### Retrieve a Single Depth [GET]
+ Parameters
    + id (string) ... ID of the Depth
+ Response 200
    [Depth][]

### Create a Depth [POST]
The following attributes are required to create a Depth:

+ Request (application/json)
    
        {
            "name": "new depth",
            "code": "new-depth-code",
            "level": 3,
            "category": {
                "id": 65
            }
        }

+ Response 200
    + Body
        
            {
                "id": 23,
                "name": "new depth",
                "code": "new-depth-code",
                "category": {
                    "code": "cat-code",
                    "color": {},
                    "name": "category one",
                    "id": "65"
                },
                "dateCreated": 1434561059383
            }

### Edit a Depth [PUT /categories/depths///{id}]
To update a Depth send JSON with the Depth's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Depth
    
+ Request (application/json)
    
        {
            "id": 23,
            "name": "a Different name",
            "code": "a-diff-code"
        }

+ Response 200
    + Body

            {
                "id": 23,
                "name": "a different name",
                "code": "a-diff-code",
                "category": {
                    "code": "cat-code",
                    "color": {},
                    "name": "category one",
                    "id": "65"
                },
                "dateUpdated": 143567975913,
                "dateCreated": 1434561059383
            }

### Remove a Depth [DELETE]
+ Parameters
    + id (string) ... ID of the Category
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

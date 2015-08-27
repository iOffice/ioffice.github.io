# Group Cost Center Depth
Cost Center Depth related resources of *iOffice API*

## Depth Collection [/costcenters/depths]
Collection of all Depths.

+ Model (application/json)
    JSON representation of the Depth Collection Resource

    + Body
    
            [
                {
                    "code": "rcat2",
                    "dateCreated": 1439399515923,
                    "name": "rando cat 2",
                    "id": 71
                },
                {
                    "code": "rc3",
                    "dateCreated": 1439399567183,
                    "name": "rcat3",
                    "id": 72
                },
                {
                    "code": "rc4",
                    "dateCreated": 1439399627200,
                    "name": "rcat4",
                    "id": 73
                } 
            ]

### List of all Depths [GET]
+ Response 200
    [Depth Collection][]

## Depth [/costcenters/depth/{id}]
A Single Depth object.

+ Model (application/json)
    JSON representation of the Depth Resource

    + Body

              {
                "code": "rcat2",
                "dateCreated": 1439399515923,
                "name": "rando cat 2",
                "id": 71
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
            "level": 2,
            "category": {
                "id": 31
            }
        }

+ Response 200
    + Body
        
            {
                "id": 23,
                "name": "new depth",
                "code": "new-depth-code",
                "dateCreated": 1434561059383
            }

### Edit a Depth [PUT]
To update a Depth send JSON with updated value for one of more of the attributes.
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
                "name": "a Different name",
                "code": "a-diff-code",
                "dateCreated": 1434561059383,
                "dateUpdated": 1435679209637 
            }

### Remove a Depth [DELETE]
+ Response 200

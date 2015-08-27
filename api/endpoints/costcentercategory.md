# Group Cost Center Category
Cost Center Category related resources of iOffice API*

## Category Collection [/costcenters/categories]
Collection of all Categories.

+ Model (application/json)
    JSON representation of the Category Collection resource

    + Body
        
            [
                {
                    "code": "co",
                    "name": "Company",
                    "id": 27
              },
              {
                    "code": "fpp",
                    "name": "Film Production",
                    "id": 28
              },
              {
                    "code": "mv",
                    "name": "Movie",
                    "id": 29
              } 
            ]

### List of all Categories [GET]
+ Response 200
    [Category Collection][]

## Cost Center Category [/costcenters/categories/{id}]
A Single Depth object.

+ Model (application/json)
    JSON representation of the Category Resource

    + Body
    
            {
                "code": "co",
                "name": "Company",
                "id": 27 
            }

### Retrieve a single Category [GET]
+ Parameters
    + id (string) ... ID of the Category
+ Response 200
    [Cost Center Category][]

### Create a Category [POST]
The following attributes are required to create a Category

+ Request (application/json)

            {
                "name": "new category",
                "code": "new category code"
            }

+ Response 200
    + Body

            {
                "id": 28,
                "name": "new category",
                "code": "new category code",
                "dateCreated": 1434561059383
            }

### Edit a Category [PUT]
+ Parameters
    + id (string) ... ID of the Category

+ Request (application/json)

        {
            "id": 28,
            "name": "a new name",
            "code": "a new code"
        }

+ Response 200
    + Body

            { 
                "id": 28,
                "name": "a new name",
                "code": "a new code",
                "dateCreated": 1434561059383,
                "dateUpdated": 1435679209637
            }

### Remove a Category [DELETE]
+ Parameters
    + id (string) ... ID of the Category
+ Response 200


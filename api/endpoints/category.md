# Group Category
Category related resources of *iOffice API*

## Category Collection [/categories{?modifiedOrCreatedAfter}]
Collection of all Categories.

+ Model (application/json)
    JSON representation of the Category Collection resource

    + Body
        
            [
                {
                    "code": "co",
                    "color": {},
                    "name": "Company",
                    "id": 27,
                    "dateUpdated": 143567975913
                },
                {
                    "code": "fpp",
                    "color": {},
                    "name": "Film Production",
                    "id": 28
                    "dateUpdated": 143567975913
                },
                {
                    "code": "mv",
                    "color": {},
                    "name": "Movie",
                    "id": 29
                    "dateUpdated": 143567975913
                } 
            ]

### List of all Categories [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.
    
+ Response 200
    [Category Collection][]

### Category Details While Adding Rule [GET /categories/type///{categoryTypeId}/{?limit,selector}]

This API returns category details while adding new rule (after clicking on 'Add Rule' button)

+ Parameters
    + categoryTypeId (optional, number, `1`) ... Category Type Id
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

## Cost Center Category [/categories///{id}]
A Single Depth object.

+ Model (application/json)
    JSON representation of the Category Resource

    + Body
    
                {
                    "code": "co",
                    "color": {},
                    "name": "Company",
                    "id": 27,
                    "dateUpdated": 143567975913
                },

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
                "color": {},
                "code": "new category code",
                "dateCreated": 1434561059383
            }

### Edit a Category [PUT]
To update a Category send JSON with the Category's `ID` and updated value for one or more of the attributes.

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
                "color": {},
                "name": "a new name",
                "code": "a new code",
                "dateCreated": 1434561059383,
                "dateUpdated": 1435679209637
            }

### Remove a Category [DELETE]
+ Parameters
    + id (string) ... ID of the Category
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }


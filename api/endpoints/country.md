# Group Country
Country-related resources of *iOffice API*

## Country [/countries///{id}]
A single country object.


+ Parameters
    + id (string) ... ID of the Country

+ Model (application/json)
    JSON representation of the Country Resource

    + Body

            {
                "id": 223,
                "defaultSelected": true,
                "name": "United States"
            }

### Retrieve a Single Country [GET]
+ Response 200

    [Country][]

### Edit a Country [PUT]
Countries cannot be modified.

+ Response 500

### Remove a Country [DELETE]
+ Parameters
    + id (string) ... ID of the Country
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

## Country Collection [/countries{?modifiedOrCreatedAfter}]
Collection of all Countries.

+ Model (application/json)
    JSON representation of the Country Collection resource.

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

### List of all Countries [GET]

+ Parameters 
    + modifiedOrCreatedAfter (optional, number, `1549319834`)... Epoch time to poll recently modified items in the collection.

+ Response 200
    
    [Country Collection][]


### Create a Country [POST]
Countries cannot be modified.

+ Response 500

    [Country][]

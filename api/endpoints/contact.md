# Group Contact
Contact-related resources of *iOffice API*

## Contact [/contacts///{id}]
A single contact object.


+ Parameters
    + id (string) ... ID of the Contact

+ Model (application/json)
    JSON representation of the Contact Resource

    + Body

            {
                "id": 23,
                ...
            }

### Retrieve a Single Contact [GET]
+ Response 200

    [Contact][]

### Edit a Contact [PUT]
To update a Contact send JSON with the Contact's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Contact
    
+ Request (application/json)

        {
            "id": 23,
            "attributeName": "value"
        }

+ Response 200
    
    [Contact][]

### Remove a Contact [DELETE]
+ Parameters
    + id (string) ... ID of the Contact
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

## Contact Collection [/contacts{?modifiedOrCreatedAfter}]
Collection of all Contacts.

+ Model (application/json)
    JSON representation of the Contact Collection resource.

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

### List of all Contacts [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`)... Epoch time to poll recently modified items in the collection.

+ Response 200
    
    [Contact Collection][]


### Create a Contact [POST]
To create a Contact send JSON with the values the new contact should have.

+ Response 201

    [Contact][]

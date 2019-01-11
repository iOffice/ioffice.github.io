# Group Asset
Asset-related resources of *iOffice API*

## Asset [/assets///{id}]
A single asset object.


+ Parameters
    + id (string) ... ID of the Asset

+ Model (application/json)
    JSON representation of the Asset Resource
    Note: An asset can be assigned to either a room or an owner. If assigned to an owner
    then the json object will have an `owner` property and not a `room` property and visa versa.

    + Body

            {
                "id": 11,
                "model": {...},
                "managed": false,
                "boxLength": "STRING",
                "titleLocation": "STRING",
                "name": "Computer",
                "dateCreated": 1382994855640,
                "active": "BOOLEAN",
                "room": {...},
                "owner": {...}
                "dateUpdated": 1382994855640
            }

### Retrieve a Single Asset [GET]
+ Response 200

    [Asset][]

### Edit a Asset [PUT]
To update a Asset send JSON with updated value for one or more of the attributes.
    
+ Request (application/json)

			{
				"id": 1,
				"printerName": "NEW PRINTER TEST NAME"
			}

+ Response 200
    
    [Asset][]

### Remove an Asset [DELETE]
+ Parameters
    + id (string) ... ID of the Asset
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

## Asset Collection [/assets///{?search,searchSerialNumber,typeId,buildingId,floorId,roomId,owner}]
Collection of all Assets.

+ Model (application/json)
    JSON representation of the Asset Collection resource.

    + Body

            [
                {
                    "id":11
                    ...
                },
                {
                    "id":12
                    ...
                },
                {
                    "id":13
                    ...
                }
            ]

### List of all Assets [GET]

+ Parameters
    + search (optional, string, `apple`) ... String to search for asset by model name, owner name, room name, localUID, or serialNumber
    + searchSerialNumber (optional, string, `11111111`) ... Search by serial number only
    + typeId (optional, number) ... Id of the type to query from
    + buildingId (optional, number) ... Id of the building to query from
    + floorId (optional, number) ... Id of the floor to query from
    + roomId (optional, number) ... Id of the room to query from
    + owner (optional, number) ... Id of the owner to query from

+ Response 200
    
    [Asset Collection][]


### Create a Asset [POST]
The following attributes are required to create a Asset: `model` and (`room` or `owner`).

+ Request (application/json)

            {
                "model": {
                    "id": 454
                },         
                "room": {
                    "id": "57"
                }
            }

+ Response 201

    [Asset][]

## Verify an asset [/assets///{id}/verify]

Create a record of the time and user that audited an asset.

+ Parameters

    + id (string) ... Id of the Asset

### Verify Asset [PUT]
+ Response 204

## Attach Asset Image [/assets///{id}/attachImage]
Attach an image to a asset

+ Parameters

    + id (string) ... Id of the Asset

+ Model (application/json)
    JSON representation of an attachment object

    + Body

            {
                "id": "ID"
                "storedFile": {
                    "id": "INTERNAL_STORAGEID"
                }
                "downloadURL": "URL_RELATIVE_TO_SITE"
                "description": "DESCRIPTION"
                "name": "IMAGE_NAME"
                "fileName": "FILE_NAME"
                "dateCreated": "EPOCH_TIME"
                "image": "BOOLEAN"
                "storageId": "INTERNAL_STORAGEID"
            }

### Attach an Image to a Asset[POST]

+ Request (application/json)

        {
            "image": "BASE-64-IMAGE-STRING"
        }

+ Response 200
    [Attach Asset Image][]

## Asset Type Collection [/assets/types]
Asset Type

+ Model (application/json)
    JSON representation of an attachment type object

    + Body

            [
                {
                    "id": 11,
                    "meteringEnabled": true,
                    "description": "Desktop Computers",
                    "sortOrder": 0,
                    "name": "Computer",
                    "active": true,
                    "dateCreated": 1262626862660,
                    "code": "COMP",
                    "unitPriceEnabled": true,
                    "dateUpdated": 1262626862660
                },
                {
                    "id":12
                    ...
                },
                {
                    "id":13
                    ...
                }
            ]

### List of all Asset Types [GET]

+ Response 200
    
    [Asset Type Collection][]

## Asset Model Collection [/assets/models]
Asset Model

+ Model (application/json)
    JSON representation of an attachment type object

    + Body

            [
                {
                    "id": 11,
                    ...
                },
                {
                    "id":12
                    ...
                },
                {
                    "id":13
                    ...
                }
            ]

### List of all Asset Models [GET]

+ Response 200
    
    [Asset Model Collection][]

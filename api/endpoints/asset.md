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
To update an Asset send JSON with the Asset's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Asset
    
+ Request (application/json)

			{
				"id": 11,
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

## Asset Collection [/assets///{?search,searchSerialNumber,typeId,buildingId,floorId,roomId,owner,modifiedOrCreatedAfter}]
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
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection

+ Response 200
    
    [Asset Collection][]


### Create a Asset [POST]
NOTE: An Asset Model `id` is required for creating an Asset.

+ Request (application/json)

            {
                "model": {
                    "id": 454
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
                "id": "11"
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

## Asset Types [/assets/types///{id}]

+ Parameters
    + id (string) ... ID of the Asset Type

+ Model (application/json)
    JSON representation of the Asset Type Resource

    + Body

            {
				"dateCreated": 1572645873930,
				"unitPriceEnabled": true,
				"name": "Computers",
				"active": true,
				"meteringEnabled": true,
				"id": 46,
				"dateUpdated": 1572645873930
            }

### Retrieve a Single Asset Type[GET]
+ Response 200

    [Asset Types][]
    
### Edit an Asset Type [PUT]
To update an Asset Type send JSON with the Asset Type's `ID` and updated value for one or more of the attributes.

+ Parameters
	+ id (string) ... ID of the Asset Type
	
+ Request (application/json)

			{
				"id": 14,
				"name": "Copy/Print/Fax",
				"code": "Copy/Print/Fax",
				"description": "copy print fax description",
				"meteringEnabled": true,
				"unitPriceEnabled": true,
				"sortOrder": 9,
				"centerLinks": 
				[
					{
						"center": 
							{
								"name": "Test Asset",
								"id": 78
							}
					},
					{
						"center":
						{
							"name": "copy asset center",
							"id": 79
						}
					}
				],
				"fields": 
				[
					{
						"baseField": 
						{
							"name": "Building",
							"id": 129
						},
						"required": false,
						"sortOrder": 1
					}
				],
				"meterTypes": 
				[
					{
						"code": "P-COL",
						"name": "Print Color",
						"id": 2
					}
				],
				"queueColumns":
				[
					{
						"name": "Manufacturer",
						"field": 
						{
							"name": "Manufacturer",
							"id": 126,
							"sortOrder": 0
						},
						"sortOrder": 1
					}
				]
			}

+ Response 200
	
	[Asset Types][]
    
### Remove an Asset Type [DELETE]

+ Parameters
    + id (string) ... ID of the Asset Type

+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

## Asset Type Collection [/assets/types///{?savedSearchId}]

+ Model (application/json)
    JSON representation of the Asset Type Collection resource.

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

## List of all Asset Types [GET]

+ Parameters
    + savedSearchId (optional, string) ... Saved Search Id used to filter Asset Types list.

+ Response 200
    
    [Asset Type Collection][]
    
### Create an Asset Type [POST]
The following attributes are required to create an Asset Type: name, meteringEnabled, unitPriceEnabled, centerLinks with at least one Center.
    
+ Request (application/json)

			{
				"name": "Computers",
				"meteringEnabled": true,
				"unitPriceEnabled": true,
				"centerLinks": 
				[
					{
						"center": 
							{
								"name": "Test Asset",
								"id": 78
							}
					}
				]
			}

+ Response 201

	[Asset Types][]
	
## Quick Search [/assets/types/quicksearch]

+ Model (application/json)
    JSON representation of the Asset Type Collection resource.

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


## Asset Types Quick Search [POST]

Gets a collection of Asset Types filtered by the search object posted.

Note:

- matchingType = true -> Match all filters.
- matchingType = false -> Match any filter.
    
+ Request (application/json)

			{
            	"availability": "EVERYONE",
            	"filters": 
            	[
            		{
            			"qualifier": "CONTAINS",
            			"valueString": "Computer",
            			"isEditMode": true,
            			"propertyPath": "name",
            			"name": ""
            		}
            	],
            	"itemClassName": "com.iofficeconnect.asset.AssetType",
            	"matchingType": false,
            	"name": ""
            }

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

## Meter Types [/assets/types/metertypes]

+ Model (application/json)
    JSON representation of the Asset Meter Type Collection resource.

    + Body

            [
                {
					"code": "P-BW",
					"dateCreated": 1132265366990,
					"sortOrder": 1,
					"name": "Print BW",
					"active": true,
					"meterCode": "P-BW",
					"dateUpdated": 1132265366990
                },
                {
                    "code": "P-COL",
                    ...
                },
                {
                    "code": "C-BW",
                    ...
                }
            ]

## List of all Meter Types [GET]

+ Response 200
    
    [Meter Types][]

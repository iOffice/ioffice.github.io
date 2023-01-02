# Group Floor
Floor-related resources of *iOffice API*

## Floor [/floors///{id}]
A single floor object.


+ Parameters
    + id (string) ... ID of the Floor

+ Model (application/json)
    JSON representation of the Floor Resource

    + Body

            {
                "id": 5,
                "building": {...},
                "area": 2000,
                "name": "1st Floor"
            }

### Retrieve a Single Floor [GET]
+ Response 200

    [Floor][]

### Edit a Floor [PUT]
To update a Floor send JSON with the Floor's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Floor
    
+ Request (application/json)

        {
        	"id": 5,
            "name": "2nd Floor"
        }

+ Response 200
    
    [Floor][]

### Remove a Floor [DELETE]
+ Parameters
    + id (string) ... ID of the Floor
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

## Floor Collection [/floors///{?buildingId,modifiedOrCreatedAfter}]
Collection of all Floors.

+ Parameters
    + buildingId (optional,string) ... Id building to query from
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Model (application/json)
    JSON representation of the Floor Collection resource.

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

### List of all Floors [GET]

+ Parameters
    + buildingId (optional, number, `3`) ... Id of building to base query
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Floor Collection][]


### Create a Floor [POST]
The following attributes are required to create a Floor: `name` and `building`.

+ Request (application/json)

            {
                "name": "3rd Floor",
                "building": {
                    "id": 45
                }
            }

+ Response 201

    [Floor][]

### Place Markers [PUT /floors/markers]
+ Request (application/json)
	{
	  "id": 429,
	  "position": {
		"x": 1232.6363636365732,
		"y": 901.3686868689745
	  }
	}
	
+ Response 200
			{
			  "dateCreated": 1572466544443,
			  "id": 429,
			  "dateUpdated": 1670871013942
			}

### Edit Markers [PUT /floors/markers/types/{id}]
+ Request (application/json)
	{
	  "hexColor": "BEA5FA",
	  "dateCreated": 1559926966786,
	  "name": "WAYFINDING",
	  "description": "",
	  "iconUid": "ios7:pioneer-wagon",
	  "markerTypeGroup": {
		"id": 18
	  },
	  "id": 19,
	  "dateUpdated": 1582233086343
	}
	
+ Response 200
			{
			  "hexColor": "BEA5FA",
			  "dateCreated": 1559926966786,
			  "name": "WAYFINDING",
			  "description": "",
			  "iconUid": "ios7:pioneer-wagon",
			  "markerTypeGroup": {
				"code": "$@IOFFICE_DEVICES@$",
				"dateCreated": 1559926966740,
				"name": "iOFFICE Kiosk Devices",
				"id": 18
			  },
			  "id": 19,
			  "dateUpdated": 1670871301387
			}
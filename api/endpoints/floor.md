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
	
## Annotations [/floors/annotation]

### Retrieve Annotations [GET]

+ Parameters
    + floorId (number, `12`) ... Id of Floor
 	+ limit (optional, number, `2`)
	+ selector (`type%2Ctext%2Clayer%2Cfxg`)
	
+ Response 200
			[
			  {
				"fxg": "<s:Group height=\"409\" width=\"892\" x=\"1546\" y=\"-456\">\n        <s:RichText height=\"409\" width=\"892\" fontFamily=\"Helvetica\" fontSize=\"32\"\n          fontStyle=\"normal\" fontWeight=\"normal\" textAlign=\"center\" textDecoration=\"none\"\n          color=\"0x000000\" backgroundAlpha=\"1.00\" backgroundColor=\"0xFFFFFF\" borderAlpha=\"1.00\"\n          borderColor=\"0x000000\" paddingLeft=\"0\">\n        </s:RichText>\n      </s:Group>",
				"name": "Text Test",
				"text": "Testing Text",
				"id": 1183,
				"type": "RichText",
				"layer": {
				  "name": "sammy test",
				  "id": 38
				}
			  },
			  {
				"fxg": "<s:Group height=\"257.0612244897819\" width=\"257.0612244897819\" x=\"1024.416326527784\" y=\"-495.0102040821838\">\n        <s:Path data=\"M0,0 L8.204081632543648,224.2448979592304 L207.83673469376663,257.0612244897819 L216.0408163265015,92.97959183682741 L139.46938775513945,57.42857142856934 L125.79591836737882,131.26530612241027 L62.897959183596186,131.26530612241027 L43.755102040799784,5.469387755037019 L0,0\" height=\"257.0612244897819\" width=\"216.0408163265015\" x=\"0\" y=\"0\">\n          <s:fill>\n            <s:SolidColor alpha=\"0\" color=\"#FFFFFF\"/>\n          </s:fill>\n          <s:stroke>\n            <s:SolidColorStroke alpha=\"1\" caps=\"round\" color=\"#000000\" joints=\"round\" weight=\"2\"/>\n          </s:stroke>\n        </s:Path>\n      </s:Group>",
				"name": "Polygon Test",
				"id": 1184,
				"layer": {
				  "name": "",
				  "id": 49
				}
			  }
			]

### Create Annotation [POST]
Creates different types of annotations i.e Shape, Polygon and Text.
This categorization is done using "type" parameter in the request body where: 
- type = "Shape" -> To Create Shape Annotation
- type = null -> To Create Polygon Annotation
- type = "RichText" -> To Create Text Annotation

Also, fxg parameter in request body will be different based on the type of annotation (i.e Shape, Polygon or Text) being created.

+ Request (application/json)
	{
	  "name": "",
	  "type":{type},
	  "layer": {
		"id": 38
	  },
	  "fxg": "<s:Group height=\"100\" width=\"100\" x=\"1965.5087425933582\" y=\"-363.596060628774\">\n        <s:Shape iconId=\"m_rounded:rounded-square\" alpha=\"1\" height=\"100\" width=\"100\" x=\"0\" y=\"0\"></s:Shape>\n      </s:Group>",
	  "model": {
		"name": "SquareShape"
	  }
	}

+ Response 201
			{
			  "dateCreated": 1671014536856,
			  "name": "SquareShape",
			  "id": 1197
			}
	
### Update Annotation [POST]
Note: 
Here, same request type(POST) along with same Endpoint of "Create Annotation" are being used for "Update Annotation", with below minor differences:
- "id" parameter is being added in the request main body which must have value as: {id of the annotation which is being updated}.
- "fxg" parameter in request body will be different, based on the type of annotation (i.e Shape, Polygon or Text) being edited.
- The response code of this POST call is 200, howevere in "Create Annotation" it is 201.

+ Request (application/json)
	{
	  "id": 1194,
	  "fxg": "<s:Group height=\"100\" width=\"100\" x=\"1196.6703241181406\" y=\"60.38390554125603\">\n        <s:Shape iconId=\"external-regular-kawalan-studio:external-square-shape-regular-kawalan-studio\" alpha=\"1\" height=\"100\" width=\"100\" x=\"0\" y=\"0\"></s:Shape>\n      </s:Group>",
	  "layer": {
		"id": 38
	  },
	  "model": {
		"name": "NewShapess",
		"width": 100,
		"height": 100,
		"x": 0,
		"y": 0
	  }
	}

+ Response 200
			{
			  "name": "NewShapess",
			  "id": 1194,
			  "dateUpdated": 1671094453187
			}
			
### Delete Annotation [DELETE /floors/annotation/{id}]
+ Parameters
    + id (number, `1197`) ... ID of the Shape/Polygon/Text
    
+ Response 200
			{"response":"Successfully removed"}
	
## Layers [/floors/annotation/layers]

### Retrieve Layers [GET]

+ Parameters
    + floorId (number, `12`) ... Id of Floor
 	+ limit (optional, number, `2`)
	+ selector (`drawing,availability,enteredBy`)
	
+ Response 200
			[
			  {
				"drawing": {
				  "name": "LEVEL 20",
				  "id": 39
				},
				"name": "sammy test",
				"availability": "EVERYONE",
				"id": 38,
				"enteredBy": {
				  "name": "asdf0 Service",
				  "id": 1
				}
			  },
			  {
				"drawing": {
				  "name": "LEVEL 20",
				  "id": 39
				},
				"name": "",
				"availability": "EVERYONE",
				"id": 49,
				"enteredBy": {
				  "name": "asdf0 Service",
				  "id": 1
				}
			  }
			]
			
### Create Layer [POST]

+ Request (application/json)
	{
	  "name": "NewLayer",
	  "availability": "EVERYONE",
	  "drawing": {
		"id": 39
	  }
	}
	
+ Response 201
			{
			  "dateCreated": 1671095761328,
			  "name": "NewLayer",
			  "id": 62
			}
			
### Update Layer [POST]
Note: 
Here, same request type(POST) along with same Endpoint of "Create Layer" are being used for "Update Layer" with below minor differences:
- In the request body "id" parameter is being added which must have value as: {id of the layer which is being updated}.
- The response code of this POST call is 200, howevere in "Create Layer" it is 201.

+ Request (application/json)
	{
	  "id": 62,
	  "name": "NewLayerss",
	  "availability": "EVERYONE"
	}
	
+ Response 200
			{
			  "name": "NewLayerss",
			  "id": 62,
			  "dateUpdated": 1671095766360
			}
			
### Delete Layer [DELETE /floors/annotation/layers/{id}]

+ Parameters
    + id (number, `58`) ... Id of the Layer
    
+ Response 200
	
    {"response":"Successfully removed"}
	
## Markers [/floors/markers]

### Place Markers [PUT]
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
	
## Marker Groups [/floors/markers/groups]

### Create Marker Group [POST]
+ Parameters 
    + selector (`availability%2Ccode%2Cdescription%2CvisibleByDefault`)
	
+ Request (application/json)
	{
	  "visibleByDefault": false,
	  "availability": "EVERYONE",
	  "name": "NewMarkerGroup",
	  "description": ""
	}

+ Response 201
			{
			  "code": "NEWMARKERGROUP",
			  "visibleByDefault": false,
			  "name": "NewMarkerGroup",
			  "description": "",
			  "availability": "EVERYONE",
			  "id": 88
			}
			
### Update Marker Group [POST]
Note: 
Here, Same request type(POST) along with same Endpoint of "Create Marker Group" are being used for "Update Marker Group" with below minor difference:
- "id" parameter is being added in the request body which must have values as:{id of the Marker Group which is being updated}.
- "code" parameter is being added in the request body which must have values as:{code of the Marker Group which is being updated}.
- The response code of this POST call is 200, howevere in "Create Marker Group" it is 201.

+ Parameters 
    + selector (`availability%2Ccode%2Cdescription%2CvisibleByDefault`)
	
+ Request (application/json)
	{
	  "code": "NEWMARKERGROUP",
	  "visibleByDefault": false,
	  "name": "NewMarkerGroups",
	  "description": "",
	  "availability": "EVERYONE",
	  "id": 88
	}

+ Response 200
			{
			  "code": "NEWMARKERGROUPS",
			  "visibleByDefault": false,
			  "name": "NewMarkerGroups",
			  "description": "",
			  "availability": "EVERYONE",
			  "id": 88
			}

### Delete Marker Group [DELETE /floors/markers/groups/{id}]

+ Parameters
    + id (number, `88`) ... Id of the Marker Group
    
+ Response 200
	
	{"response":"Successfully removed"}
# Group Saved Search
Saved Search related resources of *iOffice API*

## Saved Search [/savedsearches///{id}]
A single saved search object.

+ Parameters
    + id (string) ... ID of the Saved Search

+ Model (application/json)
    JSON representation of the Saved Search Resource

    + Body

            {
            	"id": 79,
				"itemClass": {
					 "name": "com.iofficeconnect.asset.AssetType"
				 },
				 "sortOrder": 0,
				 "name": "Computers",
				 "availability": "EVERYONE",
				 "filters": [
					 {
						 "valueString": "Comp",
						 "qualifier": "CONTAINS",
						 "property": {
							 "path": [
								 {
									 "name": "Name",
									 "collection": false
								 }
							 ],
							 "entryPointClass": {
								 "name": "com.iofficeconnect.asset.AssetType"
							 },
							 "name": "Name",
							 "pathString": "name",
							 "propertyClass": {
								 "name": "java.lang.String"
							 }
						 },
						 "id": 86,
						 "propertyPath": "name",
						 "value": {}
					 }
				 ],
				 "matchingType": "ANY"
            }

### Retrieve a Single Saved Search [GET]
+ Response 200

    [Saved Search][]


### Edit a Saved Search [PUT]
To update a Saved Search send JSON with the Saved Search's `ID` and updated value for one or more of the attributes.

Note:

- matchingType = true -> Match all filters.
- matchingType = false -> Match any filter.

+ Parameters
	+ id (string) ... ID of the Saved Search
	
+ Request (application/json)

			{
            	"id": 79,
            	"availability": "EVERYONE",
            	"filters": 
            	[
            		{
            			"id": 86,
            			"qualifier": "CONTAINS",
            			"valueString": "Comp",
            			"propertyPath": "name",
            		}
            	],
            	"itemClassName": "com.iofficeconnect.asset.AssetType",
            	"matchingType": false,
            	"name": "Computers"
            }

+ Response 200
	
	[Saved Search][]
	
### Remove a Saved Search [DELETE]

+ Parameters
    + id (string) ... ID of the Saved Search

+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

## Saved Searches Collection [/savedsearches///{?search}]

+ Model (application/json)
    JSON representation of the Saved Search Collection resource.

    + Body

            [
                {
                	 "id": 79,
					 "itemClass": {
						 "name": "com.iofficeconnect.asset.AssetType"
					 },
					 "sortOrder": 0,
					 "name": "Computers",
					 "availability": "EVERYONE",
					 "filters": [
						 {
							 "valueString": "Comp",
							 "qualifier": "CONTAINS",
							 "property": {
								 "path": [
									 {
										 "name": "Name",
										 "collection": false
									 }
								 ],
								 "entryPointClass": {
									 "name": "com.iofficeconnect.asset.AssetType"
								 },
								 "name": "Name",
								 "pathString": "name",
								 "propertyClass": {
									 "name": "java.lang.String"
								 }
							 },
							 "id": 86,
							 "propertyPath": "name",
							 "value": {}
						 }
					 ],
					 "matchingType": "ANY",
					 "dateUpdated": 1572969944120
				 },
                {
                    "id": 80
                    ...
                },
                {
                    "id": 81
                    ...
                }
            ]

## List of Saved Searches [GET]

+ Parameters
    + searchType (optional, string, `user, asset, move`) ... String to filter list by saved search type. If no searchType is sent, searchType defaults to `asset`.

+ Response 200
    
    [Saved Searches Collection][]
    
### Create a Saved Search [POST]
The following attributes are required to create a Saved Search: name, availability, matchingType and itemClassName.

Note:

- matchingType = true -> Match all filters.
- matchingType = false -> Match any filter.
- itemClassName: `com.iofficeconnect.asset.AssetType, com.iofficeconnect.move.Request, com.iofficeconnect.user.User`, 


+ Request (application/json)

			{
				"name": "Computers",
				"availability": "EVERYONE",
				"matchingType": false,
				"itemClassName": "com.iofficeconnect.asset.AssetType",
				"filters": [
					{
						"propertyPath": "name",
						"qualifier": "CONTAINS",
						"valueString": "comp"
					}
				]
			}

+ Response 201

	[Saved Search][]

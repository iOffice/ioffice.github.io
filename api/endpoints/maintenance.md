# Group Maintenance
Maintenance-related resources of *iOffice API*

iOffice Service Request is known as the maintenance module internally.


## Request [/maintenance/requests///{id}]
A single request object.  The Request resource is the main component of the service request api.


+ Parameters
    + id (string) ... ID of the Request

+ Model (application/json)
    JSON representation of the Request Resource

    + Body

            {
                "requestStatus": {...},
                "requester": {...},
                "requesterPrimaryContact": "BOOLEAN",
                "type": {...},
                "totalOperatorsNeeded": INT,
                "dateRequired": EPOCH_TIME,
                "contact": {...},
                "assetStatus": "STATUS_STRING",
                "dateUpdated": EPOCH_TIME,
                "center": {...},
                "id": REQUEST_ID,
                "fieldValue": [...],
                "priority": {...},
                "dateCreated": EPOCH_TIME,
                "scheduledTask": "BOOLEAN",
                "operators": [],
                "attachments": [...],
                "warning": {...},
                "room": {...},
                "fields": [...],
                "completed": "BOOLEAN",
                "supplies": [...],
                "valueFields": [...]
            }

#### Retrieve a Single Request [GET]
+ Response 200

    [Request][]

#### Edit a Request [PUT]
To update a Request send JSON with the Request's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Request
    
+ Request (application/json)

        {
        	"id": 23,
            "room": {
                "id": 5
            }
        }

+ Response 200
    
    [Request][]

### Cancel a Request [DELETE]
+ Parameters
    + id (string) ... ID of the Request
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }
                      
## Archive a Request [POST /maintenance/requests///{id}/archive]
+ Parameters
    + id (string) ... ID of the Request
+ Response 200

		{ }
		
## Archived Requests [/maintenance/requests/archived///{id}]
A single archived maintenance request

+ Parameters
	+ id (String) ... ID of the archived maintenance request
+ Model (application/json)
	JSON representation of the Archived Maintenance Resource
	
	+ Body
		
		{
          "requester": {
            "costCenter1": "",
            "assistantName": "",
            "jobTitle": "",
            "postalCode": "",
            "custom02": "",
            "custom01": "",
            "custom04": "",
            "custom03": "",
            "custom06": "",
            "knownAs": "",
            "custom05": "",
            "custom08": "",
            "custom07": "",
            "custom09": "",
            "id": 1,
            "state": "",
            "fax": "",
            "costCenter2": "",
            "floorWarden": false,
            "custom30": "",
            "firstName": "Customer",
            "phone": "",
            "name": "Customer Service",
            "userType": {
              "dateCreated": 1430925560737,
              "name": "Employee",
              "id": 1
            },
            "lastName": "Service",
            "extension": "",
            "color": "#694A9F",
            "city": "",
            "specialNeeds": false,
            "custom20": "",
            "custom22": "",
            "custom21": "",
            "custom24": "",
            "custom23": "",
            "dateCreated": 1099859525000,
            "custom26": "",
            "custom25": "",
            "custom28": "",
            "custom27": "",
            "custom29": "",
            "company": "",
            "department": "",
            "email": "",
            "address": "",
            "comments": "",
            "mobile": "",
            "employeeId": "",
            "userName": "ioffice",
            "dateUpdated": 1611635287623,
            "custom11": "",
            "custom10": "",
            "custom13": "",
            "custom12": "",
            "custom15": "",
            "custom14": "",
            "custom17": "",
            "custom16": "",
            "custom19": "",
            "custom18": "",
            "middleName": ""
          },
          "center": {
            "allowRequestCancel": false,
            "allowInvoicing": false,
            "allowReferenceNumber": true,
            "name": "Service Request",
            "id": 70,
            "autoArchiveEnabled": true,
            "requestResolutionRequired": false
          },
          "completed": false,
          "priority": {
            "color": {},
            "sortOrder": 3,
            "name": "Normal",
            "id": 3,
            "colorHex": "ffffff",
            "noticeTime": 60
          },
          "type": {
            "estimatedTime": 0,
            "priorityEnableForCustomer": true,
            "product": {
              "dateCreated": 1119905163000,
              "sortOrder": 1,
              "name": "Copier/Printer/Fax Service Request",
              "id": 22,
              "dateUpdated": 1119905163000
            },
            "code": "HW02",
            "defaultPriority": {
              "color": {},
              "sortOrder": 3,
              "name": "Normal",
              "id": 3,
              "colorHex": "ffffff",
              "noticeTime": 60
            },
            "center": {
              "allowRequestCancel": false,
              "allowInvoicing": false,
              "allowReferenceNumber": true,
              "name": "Service Request",
              "id": 70,
              "autoArchiveEnabled": true,
              "requestResolutionRequired": false
            },
            "SLAMinutes": 480,
            "type": "maint",
            "dateUpdated": 1237323109463,
            "dateCreated": 1237323109463,
            "dateRequiredEnabledForCustomer": true,
            "supplies": [],
            "name": "Jamming",
            "assetRequired": true,
            "defaultText": "Inhibited paper movement",
            "edgeDispatch": true,
            "id": 123,
            "fields": [],
            "totalOperatorsRequired": 1
          },
          "room": {
            "area": 0.0,
            "dateCreated": 1562710595393,
            "reservable": false,
            "name": "18",
            "description": "",
            "id": 1,
            "type": {
              "hexColor": "03ff68",
              "contentFlag": 3,
              "cost": 0.0,
              "color": {},
              "name": "WKST",
              "occupiable": true,
              "id": 99,
              "parkingSpace": false,
              "dateUpdated": 1597239189720,
              "typeCode": ""
            },
            "floor": {
              "area": 16978.2167,
              "dateCreated": 1562710593540,
              "drawingAvailable": true,
              "interiorGross": 0.0,
              "name": "1",
              "leaseArea": 0.0,
              "id": 1,
              "building": {
                "address": {
                  "country": {
                    "defaultSelected": true,
                    "subdivisionCategoryName": "state",
                    "alpha2Code": "US",
                    "isoCode": "US",
                    "name": "United States of America (the)",
                    "id": 223
                  },
                  "city": "Houston",
                  "street": "5300 Memorial Drive",
                  "postalCode": "",
                  "state": {
                    "country": {
                      "defaultSelected": true,
                      "subdivisionCategoryName": "state",
                      "alpha2Code": "US",
                      "isoCode": "US",
                      "name": "United States of America (the)",
                      "id": 223
                    },
                    "defaultSelected": false,
                    "code": "TX",
                    "name": "Texas",
                    "id": 61,
                    "categoryName": "state"
                  }
                },
                "code": "HQ",
                "dateCreated": 1107466065320,
                "metric": false,
                "name": "Headquarters",
                "location": {},
                "revitLink": "",
                "id": 43,
                "dateUpdated": 1600451429900,
                "costCenters": []
              },
              "dateUpdated": 1588684856300
            },
            "capacity": 1,
            "dateUpdated": 1586888194553
          },
          "dateArchived": 1582920182000,
          "dateCreated": 1582916446000,
          "dateRequired": 1582920046000,
          "requestId": 383,
          "supplies": [],
          "contact": {
            "costCenter1": "",
            "assistantName": "",
            "jobTitle": "",
            "postalCode": "",
            "custom02": "",
            "custom01": "",
            "custom04": "",
            "custom03": "",
            "custom06": "",
            "knownAs": "",
            "custom05": "",
            "custom08": "",
            "custom07": "",
            "custom09": "",
            "id": 1,
            "state": "",
            "fax": "",
            "costCenter2": "",
            "floorWarden": false,
            "custom30": "",
            "firstName": "Customer",
            "phone": "",
            "name": "Customer Service",
            "userType": {
              "dateCreated": 1430925560737,
              "name": "Employee",
              "id": 1
            },
            "lastName": "Service",
            "extension": "",
            "color": "#694A9F",
            "city": "",
            "specialNeeds": false,
            "custom20": "",
            "custom22": "",
            "custom21": "",
            "custom24": "",
            "custom23": "",
            "dateCreated": 1099859525000,
            "custom26": "",
            "custom25": "",
            "custom28": "",
            "custom27": "",
            "custom29": "",
            "company": "",
            "department": "",
            "email": "",
            "address": "",
            "comments": "",
            "mobile": "",
            "employeeId": "",
            "userName": "ioffice",
            "dateUpdated": 1611635287623,
            "custom11": "",
            "custom10": "",
            "custom13": "",
            "custom12": "",
            "custom15": "",
            "custom14": "",
            "custom17": "",
            "custom16": "",
            "custom19": "",
            "custom18": "",
            "middleName": ""
          },
          "id": 1,
          "requestStatus": {
            "code": "rejc",
            "dateCreated": 1127156190817,
            "name": "Rejected",
            "id": 7,
            "dateUpdated": 1127156190817
          }
        }
	

## Retrieve a single Archived Request [GET]

+ Response 200

	[Archived Requests][]
	
## Archived Collection [/maintenance/requests/archived///{?modifiedOrCreatedAfter}]

+ Parameters
	+ modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified/created items in the collection.

+ Model (application/json)
	
	JSON representation of the archived maintenance collection resource
	
	+ Body
		
		[
		   {
             "requester": {
               "costCenter1": "",
               "assistantName": "",
               "jobTitle": "",
               "postalCode": "",
               "custom02": "",
               "custom01": "",
               "custom04": "",
               "custom03": "",
               "custom06": "",
               "knownAs": "",
               "custom05": "",
               "custom08": "",
               "custom07": "",
               "custom09": "",
               "id": 1,
               "state": "",
               "fax": "",
               "costCenter2": "",
               "floorWarden": false,
               "custom30": "",
               "firstName": "Customer",
               "phone": "",
               "name": "Customer Service",
               "userType": {
                 "dateCreated": 1430925560737,
                 "name": "Employee",
                 "id": 1
               },
               "lastName": "Service",
               "extension": "",
               "color": "#694A9F",
               "city": "",
               "specialNeeds": false,
               "custom20": "",
               "custom22": "",
               "custom21": "",
               "custom24": "",
               "custom23": "",
               "dateCreated": 1099859525000,
               "custom26": "",
               "custom25": "",
               "custom28": "",
               "custom27": "",
               "custom29": "",
               "company": "",
               "department": "",
               "email": "",
               "address": "",
               "comments": "",
               "mobile": "",
               "employeeId": "",
               "userName": "ioffice",
               "dateUpdated": 1611635287623,
               "custom11": "",
               "custom10": "",
               "custom13": "",
               "custom12": "",
               "custom15": "",
               "custom14": "",
               "custom17": "",
               "custom16": "",
               "custom19": "",
               "custom18": "",
               "middleName": ""
             },
             "center": {
               "allowRequestCancel": false,
               "allowInvoicing": false,
               "allowReferenceNumber": true,
               "name": "Service Request",
               "id": 70,
               "autoArchiveEnabled": true,
               "requestResolutionRequired": false
             },
             "completed": false,
             "priority": {
               "color": {},
               "sortOrder": 3,
               "name": "Normal",
               "id": 3,
               "colorHex": "ffffff",
               "noticeTime": 60
             },
             "type": {
               "estimatedTime": 0,
               "priorityEnableForCustomer": true,
               "product": {
                 "dateCreated": 1119905163000,
                 "sortOrder": 1,
                 "name": "Copier/Printer/Fax Service Request",
                 "id": 22,
                 "dateUpdated": 1119905163000
               },
               "code": "HW02",
               "defaultPriority": {
                 "color": {},
                 "sortOrder": 3,
                 "name": "Normal",
                 "id": 3,
                 "colorHex": "ffffff",
                 "noticeTime": 60
               },
               "center": {
                 "allowRequestCancel": false,
                 "allowInvoicing": false,
                 "allowReferenceNumber": true,
                 "name": "Service Request",
                 "id": 70,
                 "autoArchiveEnabled": true,
                 "requestResolutionRequired": false
               },
               "SLAMinutes": 480,
               "type": "maint",
               "dateUpdated": 1237323109463,
               "dateCreated": 1237323109463,
               "dateRequiredEnabledForCustomer": true,
               "supplies": [],
               "name": "Jamming",
               "assetRequired": true,
               "defaultText": "Inhibited paper movement",
               "edgeDispatch": true,
               "id": 123,
               "fields": [],
               "totalOperatorsRequired": 1
             },
             "room": {
               "area": 0.0,
               "dateCreated": 1562710595393,
               "reservable": false,
               "name": "18",
               "description": "",
               "id": 1,
               "type": {
                 "hexColor": "03ff68",
                 "contentFlag": 3,
                 "cost": 0.0,
                 "color": {},
                 "name": "WKST",
                 "occupiable": true,
                 "id": 99,
                 "parkingSpace": false,
                 "dateUpdated": 1597239189720,
                 "typeCode": ""
               },
               "floor": {
                 "area": 16978.2167,
                 "dateCreated": 1562710593540,
                 "drawingAvailable": true,
                 "interiorGross": 0.0,
                 "name": "1",
                 "leaseArea": 0.0,
                 "id": 1,
                 "building": {
                   "address": {
                     "country": {
                       "defaultSelected": true,
                       "subdivisionCategoryName": "state",
                       "alpha2Code": "US",
                       "isoCode": "US",
                       "name": "United States of America (the)",
                       "id": 223
                     },
                     "city": "Houston",
                     "street": "5300 Memorial Drive",
                     "postalCode": "",
                     "state": {
                       "country": {
                         "defaultSelected": true,
                         "subdivisionCategoryName": "state",
                         "alpha2Code": "US",
                         "isoCode": "US",
                         "name": "United States of America (the)",
                         "id": 223
                       },
                       "defaultSelected": false,
                       "code": "TX",
                       "name": "Texas",
                       "id": 61,
                       "categoryName": "state"
                     }
                   },
                   "code": "HQ",
                   "dateCreated": 1107466065320,
                   "metric": false,
                   "name": "Headquarters",
                   "location": {},
                   "revitLink": "",
                   "id": 43,
                   "dateUpdated": 1600451429900,
                   "costCenters": []
                 },
                 "dateUpdated": 1588684856300
               },
               "capacity": 1,
               "dateUpdated": 1586888194553
             },
             "dateArchived": 1582920182000,
             "dateCreated": 1582916446000,
             "dateRequired": 1582920046000,
             "requestId": 383,
             "supplies": [],
             "contact": {
               "costCenter1": "",
               "assistantName": "",
               "jobTitle": "",
               "postalCode": "",
               "custom02": "",
               "custom01": "",
               "custom04": "",
               "custom03": "",
               "custom06": "",
               "knownAs": "",
               "custom05": "",
               "custom08": "",
               "custom07": "",
               "custom09": "",
               "id": 1,
               "state": "",
               "fax": "",
               "costCenter2": "",
               "floorWarden": false,
               "custom30": "",
               "firstName": "Customer",
               "phone": "",
               "name": "Customer Service",
               "userType": {
                 "dateCreated": 1430925560737,
                 "name": "Employee",
                 "id": 1
               },
               "lastName": "Service",
               "extension": "",
               "color": "#694A9F",
               "city": "",
               "specialNeeds": false,
               "custom20": "",
               "custom22": "",
               "custom21": "",
               "custom24": "",
               "custom23": "",
               "dateCreated": 1099859525000,
               "custom26": "",
               "custom25": "",
               "custom28": "",
               "custom27": "",
               "custom29": "",
               "company": "",
               "department": "",
               "email": "",
               "address": "",
               "comments": "",
               "mobile": "",
               "employeeId": "",
               "userName": "ioffice",
               "dateUpdated": 1611635287623,
               "custom11": "",
               "custom10": "",
               "custom13": "",
               "custom12": "",
               "custom15": "",
               "custom14": "",
               "custom17": "",
               "custom16": "",
               "custom19": "",
               "custom18": "",
               "middleName": ""
             },
             "id": 1,
             "requestStatus": {
               "code": "rejc",
               "dateCreated": 1127156190817,
               "name": "Rejected",
               "id": 7,
               "dateUpdated": 1127156190817
             }
           },
			...
        ]
        
## List of all Archived Requests [GET]

+ Response 200

	[Archived Collection][]	

### Requests Collection [/maintenance/requests///{?priority,assigned,pastDue,requestTypeId,modifiedOrCreatedAfter}]
Collection of all Requests.

+ Model (application/json)
    JSON representation of the Resource Collection Resource.

    + Body

            [
                {
                    "id":49
                    ...
                },
                {
                    "id":50
                    ...
                },
                {
                    "id":51
                    ...
                }
            ]

#### List of all Requests [GET]

+ Parameters

    + priority (optional, string)

        Query for high or low priority tickets:

        high (sortOrder less than or equal to 2)

        low (sortOrder greater than 2)

        + Values
            + `low`
            + `high`

    + assigned (optional, string)

        Query for tickets assigned to logged in user

        + Values
            + `me`

    + pastDue (optional, boolean)
    
    	If true, query will return past due items
    
    + requestTypeId (optional, number)
    
    	number of request type Id
    	
    + modifiedOrCreatedAfter (optional, number, `1549319834`)
  
        Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Requests Collection][]

#### Create a Request [POST]
The following attributes are required to create a Request: `dateRequired`, `requester`, `type`, `priority`, and `room`.

NOTE: If the request type's "assetRequest" attribute is TRUE, then an "asset" attribute is required as well.

+ Request (application/json)

        {
            "dateRequired": EPOCH_TIME,
            "requester": {
                "id": REQUESTER_ID,
            },
            "type": {
                "id": TYPE_ID,
            },
            "priority": {
                "id": PRIORITY_ID,
            },
            "room": {
                "id": ROOM_ID,
            }
        }

+ Response 201

    [Request][]

### Requests Collection Stats [/maintenance/requests/stats]
Statistics of Requests relative to the requesting user.

The Stats resource has the following attributes:

- assignedCount (*number of requests assigned to this user*)
- highPriorityCount (*number or requests who's type have a sortOrder less than or equal to 2*)
- lowPriorityCount (*number or requests who's type have a sortOrder greater than to 2*)
- pastDueCount (*number or requests that are past due*)
- totalCount (*total number or requests in the global queue*)

+ Model (application/json)
    JSON representation of the Resource Collection Resource.

    + Body

            {
                "assignedCount": INT
                "highPriorityCount": INT
                "lowPriorityCount": INT
                "pastDueCount": INT
                "totalCount": INT
            }

#### Request Statistics [GET]
+ Response 200
    
    [Requests Collection Stats][]


### Add Comment [/maintenance/requests///{id}/addComment]

Add a comment to a request

+ Parameters

    + id (string) ... Id of the Request

+ Model (application/json)
    HTML string of all comments for the request

    + Body

            {
                "comments": "<div class='Content'>YOUR COMMENT</div></div>"
            }
            

#### Add a comment to a Request [POST]

+ Request (application/json)

            {
                "comment": "Your new comment string"
            }

+ Response 200

    [Add Comment][]


### Attach Request Image [/maintenance/requests///{id}/attachImage]
Attach an image to a request

+ Parameters

    + id (string) ... Id of the Request

+ Model (application/json)
    JSON representation of an attachment object

    + Body

            {
                "id": ID
                "storedFile": {
                    "id": "INTERNAL_STORAGEID"
                }
                "downloadURL": "URL_RELATIVE_TO_SITE"
                "description": "DESCRIPTION"
                "name": "IMAGE_NAME"
                "fileName": "FILE_NAME"
                "dateCreated": EPOCH_TIME
                "image": "BOOLEAN"
                "storageId": "INTERNAL_STORAGEID"
            }

#### Attach an Image to a Request[POST]

+ Request (application/json)

        {
            "image": "BASE-64-IMAGE-STRING"
        }

+ Response 200
    [Attach Request Image][]


### Accept Request [/maintenance/requests///{id}/accept]
** User must be a valid operator**

Set operator's status for a request as accepted.

+ Parameters

    + id (string) ... ID of the Request

#### Accept a Request [PUT]
+ Response 200
    [Request][]


### Reject Request [/maintenance/requests///{id}/reject]
** User must be a valid operator**

Set operator's status for a request as rejected.

+ Parameters

    + id (string) ... ID of the Request

#### Reject a Request [PUT]
+ Response 200
    [Request][]


### Start Request [/maintenance/requests///{id}/start]
** User must be a valid operator**

Set operator's status for a request as started.

+ Parameters

    + id (string) ... ID of the Request

#### Start a Request [PUT]
+ Response 200
    [Request][]

### Hold Request [/maintenance/requests///{id}/hold]
** User must be a valid operator**

Set operator's status for a request as on hold.

+ Parameters

    + id (string) ... ID of the Request

#### Hold a Request [PUT]
+ Response 200
    [Request][]


### Resume Request [/maintenance/requests///{id}/resume]
** User must be a valid operator**

Set operator's status for a request as resumed.

+ Parameters

    + id (string) ... ID of the Request

#### Resume a Request [PUT]
+ Response 200
    [Request][]


### Complete Request [/maintenance/requests///{id}/complete]
** User must be a valid operator**

Set operator's status for a request as complete.

+ Parameters

    + id (string) ... ID of the Request

#### Complete a Request [PUT]
+ Response 200
    [Request][]


## Request Type [/maintenance/types///{id}]

The Request Type is the building block from which requests are created.

A single request type object.

+ Parameters
    + id (string) ... ID of the Request Type

+ Model (application/json)
    JSON representation of the Request Type Resource

    + Body

            {
                "defaultPriority": {
                    "id": 3,
                    "color": {...},
                    "sortOrder": 3,
                    "name": "Normal"
                },
                "type": "ship",
                "priorityEnableForCustomer": "true",
                "dateRequiredEnabledForCustomer": "true",
                "dateUpdated": 1126109927833,
                "totalOperatorsRequired": 1,
                "product": {
                    "id": 10,
                    "sortOrder": 4,
                    "name": "Arwing",
                    "dateCreated": 1126040636373,
                    "dateUpdated": 1127922019337
                },
                "id": 68,
                "SLAMinutes": 0,
                "estimatedTime": 0,
                "name": "Thruster Repair",
                "dateCreated": 1126109927833,
                "fields": [...]
            }

#### Retrieve a Single Request Type [GET]
+ Response 200

    [Request Type][]

### Request Types Collection [/maintenance/types{?modifiedOrCreatedAfter}]
Collection of all Request Types.

+ Model (application/json)
    JSON representation of the Resource Collection Resource.

    + Body

            [
                {
                    "id":65
                    ...
                },
                {
                    "id":66
                    ...
                },
                {
                    "id":67
                    ...
                }
            ]

#### List of all Request Types [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`)... Epoch time (milliseconds) to poll recently modified items in the collection.
+ Response 200
    
    [Request Types Collection][]

#### Create a Request Type [POST]
The following attributes are required to create a Request Type: `product` and `name`.


+ Request Type (application/json)

            {
                "name": "Ship Wing Repair",
                "Product": {
                    "id": 78
                },
            }

+ Response 201

    [Request Type][]



## Category [/maintenance/categories///{id}]

The Category resource gives access to Products from which you can derive Request Types.

A single category object.


+ Parameters
    + id (string) ... ID of the Category

+ Model (application/json)
    JSON representation of the Category Resource

    + Body

            {
                "id": ID,
                "name": "STRING",
                "products": [...]
            }

#### Retrieve a Single Category [GET]
+ Response 200

    [Category][]

### Categories Collection [/maintenance/categories{?modifiedOrCreatedAfter}]
Collection of all Categories.

+ Model (application/json)
    JSON representation of the Resource Collection Resource.

    + Body

            [
                {
                    "id":49
                    ...
                },
                {
                    "id":50
                    ...
                },
                {
                    "id":51
                    ...
                }
            ]

#### List of all Categories [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`)... Epoch time (milliseconds) to poll recently modified items in the collection.
    
+ Response 200
    
    [Categories Collection][]

#### Create a Category [POST]
The following attributes are required to create a Category: `center` and `name`.


+ Category (application/json)

            {
                "name": "Create Copier/Printer Equipment Service Request",
                "center": {
                    "id": 70,
                },
            }

+ Response 201

    [Category][]


### Product [/maintenance/products///{id}]
A single product object.


+ Parameters
    + id (string) ... ID of the Product

+ Model (application/json)
    JSON representation of the Product Resource

    + Body

            {
                "id": 23,
                "name": "Copier",
                "dateCreated": 1403633288547,
                "dateUpdated": 1403633288547
            }

#### Retrieve a Single Product [GET]
+ Response 200

    [Product][]

### Products Collection [/maintenance/products{?modifiedOrCreatedAfter}]
Collection of all Products.

+ Model (application/json)
    JSON representation of the Resource Collection Resource.

    + Body

            [
                {
                    "id": 23,
                    "name": "Copier",
                    "dateCreated": 1403633288547,
                    "dateUpdated": 1403633288547
                },
                {
                    "id":24
                    ...
                },
                {
                    "id":25
                    ...
                }
            ]

#### List of all Products [GET]

+ Parameters 
    + modifiedOrCreatedAfter (optional, number, `1549319834`)... Epoch time (milliseconds) to poll recently modified items in the collection.
    
+ Response 200
    
    [Products Collection][]

#### Create a Product [POST]
The following attribute is required to create a Product: `name`.


+ Product (application/json)

            {
                "name": "Printer Equipment Service Request",
            }

+ Response 201

    [Product][]



### Priority [/maintenance/priorities///{id}]
The Priority resource gives access to Products from which you can derive Request Types.

A single priority object.

+ Parameters
    + id (string) ... ID of the Priority

+ Model (application/json)
    JSON representation of the Priority Resource

    + Body

            {
                "id": 1,
                "color": {
                    "red": 102,
                    "green": 51,
                    "blue": 153
                },
                "sortOrder": 1,
                "name": "Urgent"
            }

#### Retrieve a Single Priority [GET]
+ Response 200

    [Priority][]

### Priorities Collection [/maintenance/priorities{?modifiedOrCreatedAfter}]
Collection of all Priorities.

+ Model (application/json)
    JSON representation of the Resource Collection Resource.

    + Body

            [
                {
                    "id":49
                    ...
                },
                {
                    "id":50
                    ...
                },
                {
                    "id":51
                    ...
                }
            ]

#### List of all Priorities [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.
    
+ Response 200
    
    [Priorities Collection][]

#### Create a Priority [POST]
The following attributes are required to create a Priority: `name` and `sortOrder`.


+ Priority (application/json)

            {
                "name": "Create Copier/Printer Equipment Service Request",
                "sortOrder": 3,
            }

+ Response 201

    [Priority][]



### Get Earliest Required Date [/maintenance/priorities///{id}/earliestRequiredDate///{?typeId,centerId}]

Get the earliest available date that a Request can be required to be completed by.

The time is calculated based on the following:

    + Request Type
    + Request Priority
    + Service Level Agreement (SLA) for the Request type
    + Center hours of operation

+ Parameters
    + id (string) ... ID of the Request.
    + typeId (required, number) ... Request Type Id
    + centerId (required, number) ... Request's Center Id

#### Get Date [GET]
+ Response 200 (application/json)

    + Body

            { "time": 1404839102117 }

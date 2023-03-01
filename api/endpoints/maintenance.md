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

### Retrieve a Single Request [GET]
+ Response 200

    [Request][]

### Create a Request [POST]
The following attributes are required to create a Request: `dateRequired`, `requester`, `type`,`priority`, and `room`.
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

### Update a Request [PUT]
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
            "response": "Request cancelled"
        }

### Request Statistics [GET /maintenance/requests/stats]

Statistics of Requests relative to the requesting user.

The Stats resource has the following attributes:

- assignedCount (*number of requests assigned to this user*)
- highPriorityCount (*number or requests who's type have a sortOrder less than or equal to 2*)
- lowPriorityCount (*number or requests who's type have a sortOrder greater than to 2*)
- pastDueCount (*number or requests that are past due*)
- totalCount (*total number or requests in the global queue*)

+ Response 200

                 {
                      "assignedCount": INT
                      "highPriorityCount": INT
                      "lowPriorityCount": INT
                      "pastDueCount": INT
                      "totalCount": INT
                 }
         
### Add a comment to a Request [POST /maintenance/requests///{id}/addComment]
Add a comment to a request

+ Parameters

    + id (string) ... Id of the Request
+ Request (application/json)

            {
                "comment": "Your new comment string"
            }

+ Response 200

            {
                "comments": "<div class='Content'>YOUR COMMENT</div></div>"
            }
  
### Attach an Image to a Request[POST /maintenance/requests///{id}/attachImage]
Attach an image to a request

+ Parameters

    + id (string) ... Id of the Request
+ Request (application/json)

        {
            "image": "BASE-64-IMAGE-STRING"
        }

+ Response 200

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

### Accept a Request [PUT /maintenance/requests///{id}/accept]
** User must be a valid operator**

Set operator's status for a request as accepted.

+ Parameters

    + id (string) ... ID of the Request

+ Response 200
    [Request][]

### Reject a Request [PUT /maintenance/requests///{id}/reject]
** User must be a valid operator**

Set operator's status for a request as rejected.

+ Parameters

    + id (string) ... ID of the Request
+ Response 200
    [Request][]

### Start a Request [PUT /maintenance/requests///{id}/start]
** User must be a valid operator**

Set operator's status for a request as started.

+ Parameters

    + id (string) ... ID of the Request

+ Response 200
    [Request][]

### Hold a Request [PUT /maintenance/requests///{id}/hold] 
** User must be a valid operator**

Set operator's status for a request as on hold.

+ Parameters

    + id (string) ... ID of the Request

+ Response 200
    [Request][]

### Resume a Request [PUT /maintenance/requests///{id}/resume]
** User must be a valid operator**

Set operator's status for a request as resumed.

+ Parameters

    + id (string) ... ID of the Request

+ Response 200
    [Request][]

### Add Resolution Note to Request[PUT /maintenance/requests///{id}/addResolution]
** User must be a valid operator**

Add Resolution Note before Completing Request

+ Parameters

    + id (string) ... ID of the Request

+ Request (application/json)

              {
                 "resolution": "Resolved Ticket",
                 "operator": {
                      "id": 11855
                 }
              }

+ Response 200

           {
             "requester": { ... },
             "attachments": [...],
             "comments": "",
             "center": { ... },
             "totalOperatorsNeeded": 1,
             "vendedItems": false,
             "priority": { ... },
             "type": { ... },
             "enteredBy": { ... },
             "resolution": "Rainforest SiteAdmin1234 (Feb 16, 2023 01:11 PM GMT) : Resolved Ticket",
             "room": {... },
             "dateCreated": 1676546622000,
             "dateRequired": 1676550300000,
             "dateStarted": 1676553106000,
             "operators": [... ],
             "dateCompleted": 1676553119000,
             "supplies": [... ],
             "contact": {... },
             "id": 14260,
             "fields": [... ],
             "requestStatus": {
                 "code": "comp",
                 "name": "Completed",
                 "id": 4
             }
           }

### Complete a Request [PUT /maintenance/requests///{id}/complete]
** User must be a valid operator**

Set operator's status for a request as complete.

+ Parameters

    + id (string) ... ID of the Request
+ Response 200
    [Request][]

### Archive a Request [POST /maintenance/requests///{id}/archive]
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
                      "name": "Rainforest SiteAdmin1234",
                      "id": 2094,
                      "email": "siteadmin1234@eptura.com"
                 },
                 "attachments": [ ... ],
                 "comments": "...",
                 "center": {
                      "allowRequestCancel": false,
                      "allowInvoicing": false,
                      "allowReferenceNumber": false,
                      "name": "Service Request",
                      "timeZone": {
                          "ID": "Europe/London"
                          },
                      "hoursOfOperation": [
                        {
                          "endTimeMinutes": 0,
                          "dayId": 2,
                          "startTimeMinutes": 0,
                          "endTimeHour": 17,
                          "id": 349,
                          "startTimeHour": 8
                        }, ...
                      ],
                      "id": 70,
                      "autoArchiveEnabled": false,
                      "requestResolutionRequired": false
                 },
                 "totalOperatorsNeeded": 1,
                 "priority": {
                      "color": {
                          "red": 252,
                          "green": 5,
                          "blue": 5
                      },
                 "name": "Urgent",
                 "id": 1
                 },
              "type": {
                 "priorityEnableForCustomer": true,
                 "priorities": [
                      {
                          "color": {
                              "red": 255,
                              "green": 255,
                              "blue": 255
                              },
                          "name": "Priority1404845",
                          "id": 280
                          },... ],
                 "product": {
                     "name": "Air Conditioning and Heating",
                     "id": 7,
                     "category": {
                          "name": "Work Order",
                          "id": 100
                          }
                     },
                 "dateRequiredEnabledForCustomer": true,
                 "assetRequest": false,
                 "supplies": [... ],
                 "operatorInstructions": [... ],
                 "name": "Too cold",
                 "edgeDispatch": false,
                 "id": 52,
                 "fields": [... ]
                 },
              "resolution": "Rainforest SiteAdmin1234 (Feb 16, 2023 03:22 PM GMT) : Ticket Resolved",
              "room": {... },
              "dateArchived": 1676561013000,
              "dateCreated": 1676560912000,
              "dateRequired": 1678720860000,
              "dateStarted": 1676560937000,
              "operators": [... ],
              "dateCompleted": 1676560942000,
              "requestId": 14366,
              "supplies": [... ],
              "contact": {... },
              "id": 4897,
              "fields": [... ],
              "requestStatus": {
                  "code": "comp",
                  "name": "Completed",
                  "id": 4
                  }
             }

### Retrieve a single Archived Request [GET]

+ Response 200
  [Archived Requests][]

### Archived Collection [/maintenance/requests/archived///{?modifiedOrCreatedAfter}]
Collection of archived maintenance requests

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified/created items in the collection.
+ Model (application/json)
  JSON representation of the Archived Maintenance Resource

    + Body

            [
              {
                 "requester": {
                      "name": "Rainforest SiteAdmin1234",
                      "id": 2094,
                      "email": "siteadmin1234@eptura.com"
                 },
                 "attachments": [ ... ],
                 "comments": "...",
                 "center": {
                      "allowRequestCancel": false,
                      "allowInvoicing": false,
                      "allowReferenceNumber": false,
                      "name": "Service Request",
                      "timeZone": {
                          "ID": "Europe/London"
                          },
                      "hoursOfOperation": [
                        {
                          "endTimeMinutes": 0,
                          "dayId": 2,
                          "startTimeMinutes": 0,
                          "endTimeHour": 17,
                          "id": 349,
                          "startTimeHour": 8
                        }, ...
                      ],
                      "id": 70,
                      "autoArchiveEnabled": false,
                      "requestResolutionRequired": false
                 },
                 "totalOperatorsNeeded": 1,
                 "priority": {
                      "color": {
                          "red": 252,
                          "green": 5,
                          "blue": 5
                      },
                 "name": "Urgent",
                 "id": 1
                 },
              "type": {
                 "priorityEnableForCustomer": true,
                 "priorities": [
                      {
                          "color": {
                              "red": 255,
                              "green": 255,
                              "blue": 255
                              },
                          "name": "Priority1404845",
                          "id": 280
                          },... ],
                 "product": {
                     "name": "Air Conditioning and Heating",
                     "id": 7,
                     "category": {
                          "name": "Work Order",
                          "id": 100
                          }
                     },
                 "dateRequiredEnabledForCustomer": true,
                 "assetRequest": false,
                 "supplies": [... ],
                 "operatorInstructions": [... ],
                 "name": "Too cold",
                 "edgeDispatch": false,
                 "id": 52,
                 "fields": [... ]
                 },
              "resolution": "Rainforest SiteAdmin1234 (Feb 16, 2023 03:22 PM GMT) : Ticket Resolved",
              "room": {... },
              "dateArchived": 1676561013000,
              "dateCreated": 1676560912000,
              "dateRequired": 1678720860000,
              "dateStarted": 1676560937000,
              "operators": [... ],
              "dateCompleted": 1676560942000,
              "requestId": 14366,
              "supplies": [... ],
              "contact": {... },
              "id": 4897,
              "fields": [... ],
              "requestStatus": {
                  "code": "comp",
                  "name": "Completed",
                  "id": 4
                  }
             },...
          ]


### List of all Archived Requests [GET]

+ Response 200
  [Archived Collection][]

## Requests Collection [/maintenance/requests///{?priority,assigned,pastDue,requestTypeId,modifiedOrCreatedAfter,limit,orderBy,orderByType,showOnlyMyRequests,selector}]
Collection of all Requests.

+ Model (application/json)
  JSON representation of the Requests Collection Resource.
    
    + Body

          [
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
            },...
          ]

### List of all Requests [GET]

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

    + limit (optional, number, `5`)

      Request List limit to query from.

    + orderBy (optional, string)

      If id List displayed by id.

    + orderByType (optional, string)

      If desc List displayed by Descending Order.

    + showOnlyMyRequests (optional, boolean)

      If true then shows only Request related to User.

    + selector (optional, string)

      If id then selects requests based on id.

+ Response 200
  [Requests Collection][]

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

### Retrieve a Single Request Type [GET]
+ Response 200
    [Request Type][]

### Create a Request Type [POST]
The following attributes are required to create a Request Type: `product` and `name`.

+ Request (application/json)

            {
                "name": "Ship Wing Repair",
                "Product": {
                    "id": 78
                },
            }

+ Response 201
  [Request Type][]

### Update a Request Type [PUT /maintenance/types]
To update a Request Type send JSON with the Category's `ID` and updated value for one or more of the attributes.


+ Request (application/json)

                       {
                           "id": 1041,
                           "iconUid": "external-flaticons-lineal-color-flat-icons:external-pin-sewing-flaticons-lineal-color-flat-icons-2"
                       }

+ Response 200

                     {
                        "product": {
                             "name": "Break Room",
                             "id": 20,
                             "category": {
                                       "name": "Work Order",
                                       "id": 100
                             }
                        },
                             "code": "",
                             "name": "RequestType - 2658487",
                             "iconUid": "external-flaticons-lineal-color-flat-icons:external-pin-sewing-flaticons-lineal-color-flat-icons-2",
                             "id": 1041
                     }

### Delete a Request Type [DELETE]
+ Parameters
    + id (string) ... ID of the Request Type
+ Response 200

        {
            "response": "Successfully removed"
        }

### Request Types Collection [/maintenance/types{?modifiedOrCreatedAfter,centerId}]
Collection of all Request Types.

+ Model (application/json)
  JSON representation of the Request Type Resource

    + Body

          [  
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
            },...
           ]

### List of all Request Types [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`)... Epoch time (milliseconds) to poll recently modified items in the collection.
    + centerId (optional, number, `70`) ... Id of center to query from.
+ Response 200
   [Request Types Collection][]

### Request Types Recent Requests Collection [/maintenance/types/recent{?modifiedOrCreatedAfter,centerId,assetRequestTypesOnly}]
Collection of all recent Request Types.

+ Model (application/json)
  JSON representation of the Requests Types Recent Requests Collection Resource.

    + Body

                      [
                        {
                           "product": {
                                "name": "Product 3104688",
                                "id": 222,
                                "category": {
                                      "hidden": false,
                                      "name": "Category 3769587",
                                      "id": 318
                                      }
                                },
                           "code": "",
                           "assetRequest": false,
                           "center": {
                                 "name": "Service Request",
                                 "id": 70
                                 },
                           "name": "RequestType - 9745771",
                           "id": 525
                        },...
                      ]

### List of Recent Request Types [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`)... Epoch time (milliseconds) to poll recently modified items in the collection.
    + centerId (optional, number, `70`) ... Id of center to query from.
    + assetRequestTypesOnly (optional, boolean, `false`) ...If Request is Asset Type then assetRequestTypesOnly should be true.

+ Response 200
  [Request Types Recent Requests Collection][]

### Request Types Common Requests Collection [/maintenance/types/recent{?modifiedOrCreatedAfter,centerId,assetRequestTypesOnly}]
Collection of all Common Request Types.

+ Model (application/json)
  JSON representation of the Requests Types Common Requests Collection Resource.

    + Body

                      [
                        {
                           "product": {
                                "name": "Product 3104688",
                                "id": 222,
                                "category": {
                                      "hidden": false,
                                      "name": "Category 3769587",
                                      "id": 318
                                      }
                                },
                           "code": "",
                           "assetRequest": false,
                           "center": {
                                 "name": "Service Request",
                                 "id": 70
                                 },
                           "name": "RequestType - 9745771",
                           "id": 525
                        },...
                      ]

### List of Common Request Types [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`)... Epoch time (milliseconds) to poll recently modified items in the collection.
    + centerId (optional, number, `70`) ... Id of center to query from.
    + assetRequestTypesOnly (optional, boolean, `false`) ...If Request is Asset Type then assetRequestTypesOnly should be true.
+ Response 200
  [Request Types Common Requests Collection][]

### Get Earliest SLA Date [/maintenance/types/{id}/earliestSlaDate///{?centerId,startDate,modifiedOrCreatedAfter}]

Get the earliest SLA date that a Request can be required to be completed by.

+ Parameters
    + id (required, number) ... Request Type Id
    + centerId (required, number) ... Request's Center Id
    + startDate (required, number) ... Request's Start Date
    + modifiedOrCreatedAfter (optional, number, `1549319834`)... Epoch time (milliseconds) to poll recently modified items in the collection.

### Get SLA Date [GET]

+ Response 200 (application/json)

    + Body

            {"time":1676546617455}

## Scheduled Task [/maintenance/scheduled///{id}]
A single scheduled task object.  The scheduled task resource is the component of the service request api.


+ Parameters
    + id (string) ... ID of the Scheduled task

+ Model (application/json)
  JSON representation of the Scheduled task Resource

    + Body

                   [
                       {
                         "comments": "",
                         "nextRequiredDate": 1673883180000,
                         "requestType": {
                              "code": "",
                              "name": "Elevator Moves Too Fast (3on, 3oasac)",
                              "id": 998
                              },
                         "center": {
                               "name": "Service Request",
                               "id": 70
                               },
                         "taskDescription": "Test",
                         "active": true,
                         "howOftenCount": 1,
                         "fieldValue": [... ],
                         "requestor": {
                               "name": "Rainforest SiteAdmin1234",
                               "id": 2094
                               },
                         "room": {
                                "name": "1-400",
                                "id": 1121,
                                "floor": {
                                     "name": "1",
                                     "id": 42,
                                     "building": {
                                           "code": "DO NOT REMOVE",
                                           "name": "Reservation",
                                           "id": 66
                                           }
                                     }
                                },
                         "howOften": "everyday",
                         "notificationDayCount": 1,
                         "scheduleValues": "1,2,3,4,5,6,7",
                         "dateCreated": 1672912412000,
                         "taskFrequency": "daily",
                         "contact": {
                                "name": "Rainforest SiteAdmin1234",
                                "id": 2094
                         },
                         "howOftenDay": 0,
                         "howOftenWeek": 0,
                         "nextSubmissionDate": 1673796780000,
                         "id": 156,
                         "startDate": 1673883180000
                       }
                   ]

### Retrieve a Single Scheduled Task [GET]
+ Response 200
  [Scheduled Task][]

### Create a Scheduled Task [POST]
The following attributes are required to create a Request: `dateRequired`, `requester`, `type`,`priority`, and `room`.
NOTE: If the request type's "assetRequest" attribute is TRUE, then an "asset" attribute is required as well.

+ Request (application/json)

                 [
                     {
                        "comments": "",
                        "nextRequiredDate": 1673883180000,
                        "requestType": {
                              "code": "",
                              "name": "Elevator Moves Too Fast (3on, 3oasac)",
                              "id": 998
                              },
                        "center": {
                              "name": "Service Request",
                              "id": 70
                              },
                        "taskDescription": "Test",
                        "active": true,
                        "howOftenCount": 1,
                        "fieldValue": [... ],
                        "requestor": {
                             "name": "Rainforest SiteAdmin1234",
                             "id": 2094
                             },
                        "room": {
                             "name": "1-400",
                             "id": 1121,
                             "floor": {
                                  "name": "1",
                                  "id": 42,
                                  "building": {
                                       "code": "DO NOT REMOVE",
                                       "name": "Reservation",
                                       "id": 66
                                       }
                                  }
                             },
                        "howOften": "everyday",
                        "notificationDayCount": 1,
                        "scheduleValues": "1,2,3,4,5,6,7",
                        "dateCreated": 1672912412000,
                        "taskFrequency": "daily",
                        "contact": {
                             "name": "Rainforest SiteAdmin1234",
                             "id": 2094
                             },
                        "howOftenDay": 0,
                        "howOftenWeek": 0,
                        "nextSubmissionDate": 1673796780000,
                        "id": 156,
                        "startDate": 1673883180000
                     }
                 ]
+ Response 201    
  [Scheduled Task][]

### Update a Scheduled Task [PUT]
To update a Scheduled Task send JSON with the Request's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Scheduled Task

+ Request (application/json)

                      {
                           "comments": "",
                           "nextRequiredDate": 1669475640000,
                           "requestType": {
                                "id": 1069
                                },
                           "center": {
                                "id": 70
                                },
                           "taskDescription": "Need Chair123",
                           "active": true,
                           "howOftenCount": 1,
                           "requestor": {
                                "id": 2094
                                },
                           "room": {
                                "id": 1090
                                },
                           "howOften": "scheduled",
                           "notificationDayCount": 1,
                           "scheduleValues": "",
                           "dateCreated": 1669281370000,
                           "taskFrequency": "daily",
                           "contact": {
                                 "id": 2094
                                 },
                           "howOftenDay": 0,
                           "howOftenWeek": 0,
                           "nextSubmissionDate": 1669389240000,
                           "id": 147,
                           "startDate": 1669475640000,
                           "fieldValueMap": {... },
                           "buildingName": "Reservation",
                           "asset": null
                      }

+ Response 200
  [Scheduled Task][]

### Cancel a Scheduled Task [DELETE]
+ Parameters
    + id (string) ... ID of the Scheduled Task
+ Response 200

        {
            "response": "Request cancelled"
        }

## Scheduled Task Collection [/maintenance/scheduled///{?centerId,includeActive,includeInactive,orderBy,orderByType,startAt,modifiedOrCreatedAfter,search}]
Collection of all Scheduled Tasks.

+ Model (application/json)
  JSON representation of the Scheduled Tasks Collection Resource.

    + Body
          
                  [
                       {
                           "comments": "",
                           "nextRequiredDate": 1669475640000,
                           "requestType": {
                                "id": 1069
                                },
                           "center": {
                                "id": 70
                                },
                           "taskDescription": "Need Chair123",
                           "active": true,
                           "howOftenCount": 1,
                           "requestor": {
                                "id": 2094
                                },
                           "room": {
                                "id": 1090
                                },
                           "howOften": "scheduled",
                           "notificationDayCount": 1,
                           "scheduleValues": "",
                           "dateCreated": 1669281370000,
                           "taskFrequency": "daily",
                           "contact": {
                                 "id": 2094
                                 },
                           "howOftenDay": 0,
                           "howOftenWeek": 0,
                           "nextSubmissionDate": 1669389240000,
                           "id": 147,
                           "startDate": 1669475640000,
                           "fieldValueMap": {... },
                           "buildingName": "Reservation",
                           "asset": null
                      },...
                  ]

### List of all Scheduled Task [GET]

+ Parameters

    + centerId (optional, number)

      id of center

    + includeActive (optional, boolean)

      If true, query will return includeActive
  
    + includeInactive (optional, boolean)

      If true, query will return includeInactive
  
    + startAt (optional, number)

      Start time of Request

    + modifiedOrCreatedAfter (optional, number, `1549319834`)

      Epoch time (milliseconds) to poll recently modified items in the collection.
  
    + orderBy (optional, string)
       
      If taskDescription then Scheduled Task List by taskDescription.

    + orderByType (optional, string)

      If asc then Scheduled Task List in Ascending Order.

+ Response 200
  [Scheduled Task Collection][]

### Count of all Scheduled Task [GET /maintenance/scheduled/count{??centerId,includeActive,includeInactive,modifiedOrCreatedAfter,search}]
Count of Scheduled Task.

+ Parameters

    + modifiedOrCreatedAfter (optional, number, `1676615686024`)... Epoch time (milliseconds) to poll recently modified items in the collection.
  
    + centerId (optional, number)

        id of center

    + includeActive (optional, boolean)

        If true, query will return includeActive

    + includeInactive (optional, boolean)

        If true, query will return includeInactive

    + modifiedOrCreatedAfter (optional, number, `1549319834`)

        Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200

                   {
                      "count": 634
                   }

## Category [/maintenance/categories///{id}]

The Category resource gives access to Products from which you can derive Request Types.

A single category object.


+ Parameters
    + id (string) ... ID of the Category
    + name (string) ... NAME of the Category

+ Model (application/json)
    JSON representation of the Category Resource

    + Body

                    {
                        "hidden": false,
                        "center": {
                              "name": "Service Request",
                              "id": 70
                              },
                        "name": "Category 8143004",
                        "id": 107,
                        "products": [
                             {
                                  "center": {
                                       "name": "Service Request",
                                       "id": 70
                                  },
                                  "name": "Product 3420221",
                                  "id": 28,
                                  "requestTypes": [
                                       {
                                           "code": "",
                                           "assetRequest": false,
                                           "center": {
                                               "name": "Service Request",
                                               "id": 70
                                               },
                                           "name": "RequestType - 1883603",
                                           "assetRequired": false,
                                           "id": 189
                                       },...
                                  ]
                             }
                        ]
                    }

### Retrieve a Single Category [GET]
+ Response 200
    [Category][]

### Create a Category [POST]
The following attributes are required to create a Category: `center` and `name`.

+ Request (application/json)

            {
                "name": "Create Copier/Printer Equipment Service Request",
                "center": {
                    "id": 70,
                },
            }

+ Response 201
  [Category][]

### Update a Category [PUT]
To update a Category send JSON with the Category's `ID` and updated value for one or more of the attributes.


+ Request (application/json)

                       {
                          "hidden": false,
                          "name": "demo1",
                          "id": 971,
                          "products": [... ]
                       }

+ Response 200
  [Category][]

### Delete a Category [DELETE]
+ Parameters
    + id (string) ... ID of the Category.
+ Response 200

        {
           {"response":"Successfully removed"}
        }

### Categories Collection [/maintenance/categories{?modifiedOrCreatedAfter}]
Collection of all Categories.

+ Model (application/json)
    JSON representation of the Categories Collection Resource.

    + Body

               [
                    {
                        "hidden": false,
                        "center": {
                              "name": "Service Request",
                              "id": 70
                              },
                        "name": "Category 8143004",
                        "id": 107,
                        "products": [
                             {
                                  "center": {
                                       "name": "Service Request",
                                       "id": 70
                                  },
                                  "name": "Product 3420221",
                                  "id": 28,
                                  "requestTypes": [
                                       {
                                           "code": "",
                                           "assetRequest": false,
                                           "center": {
                                               "name": "Service Request",
                                               "id": 70
                                               },
                                           "name": "RequestType - 1883603",
                                           "assetRequired": false,
                                           "id": 189
                                       },...
                                  ]
                             }
                        ]
                    },...
               ]

### List of all Categories [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`)... Epoch time (milliseconds) to poll recently modified items in the collection.
    
+ Response 200
    [Categories Collection][]

### Count of all Categories [GET /maintenance/categories/count{?modifiedOrCreatedAfter}]
Count of Categories.

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1676615686024`)... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200

             {
               "count": 634
             }

## Product [/maintenance/products///{id}]
A single product object.

+ Parameters
    + id (string) ... ID of the Product

+ Model (application/json)
    JSON representation of the Product Resource

    + Body

                   {
                        "name": "QATEst",
                        "id": 815,
                        "category": {
                            "name": "QATest555555",
                            "id": 994
                        },
                        "type": "facility",
                        "requestTypes": [... ]
                   }

### Retrieve a Single Product [GET]
+ Response 200
    [Product][]

### Create a Product [POST]
The following attribute is required to create a Product: `name`,`type` and `category`.


+ Request (application/json)

            {
                 "name": "QATEst",
                 "type": "facility",
                 "category": {
                               "id": 994
                 }
            }

+ Response 201
  [Product][]

### Update a Product [PUT]
The following attribute is required to Edit a Product: `name`,`type` and `category`.
To update a Product send JSON with the Product's `ID` and updated value for one or more of the attributes.

+ Request (application/json)

            {
                 "name": "QATEst",
                 "type": "facility",
                 "category": {
                               "id": 994
                 }
            }

+ Response 200
  [Product][]

### Delete a Product [DELETE]
+ Parameters
    + id (string) ... ID of the Product.
+ Response 200

        {
           {"response":"Successfully removed"}
        }

### Products Collection [/maintenance/products{?modifiedOrCreatedAfter}]
Collection of all Products.

+ Model (application/json)
    JSON representation of the Products Collection Resource.

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

### List of all Products [GET]

+ Parameters 
    + modifiedOrCreatedAfter (optional, number, `1549319834`)... Epoch time (milliseconds) to poll recently modified items in the collection.
    
+ Response 200
   [Products Collection][]

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

### Retrieve a Single Priority [GET]
+ Response 200
    [Priority][]

### Create a Priority [POST]
The following attributes are required to create a Priority: `name` and `sortOrder`.


+ Request (application/json)

            {
                "name": "Create Copier/Printer Equipment Service Request",
                "sortOrder": 3,
            }

+ Response 201
  [Priority][]

### Priorities Collection [/maintenance/priorities{?modifiedOrCreatedAfter}]
Collection of all Priorities.

+ Model (application/json)
    JSON representation of the Priorities Collection Resource.

    + Body

          [
             {
               "id": 1,
               "color": {
                   "red": 102,
                   "green": 51,
                   "blue": 153
               },
               "sortOrder": 1,
               "name": "Urgent"
             },...
          ]


### List of all Priorities [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.
    
+ Response 200
     [Priorities Collection][]

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

### Get Date [GET]
+ Response 200 (application/json)

    + Body

            { "time": 1404839102117 }

## Assets Collection [/maintenance/assets///{?modifiedOrCreatedAfter,limits,search}]
Collection of Assets.

+ Model (application/json)
  JSON representation of the Assets Collection Resource.

    + Body

                  [
                       {
                           "center": {
                                 "name": "Asset Center",
                                 "id": 69
                                 },
                           "name": "Asset",
                           "model": {
                                  "name": "demomodel",
                                  "id": 460
                                  },
                           "id": 1215
                       }
                  ]

### List of Assets [GET]

+ Parameters

    + limits (optional, number, `1`)

      Assets List limit to query from

    + modifiedOrCreatedAfter (optional, number, `1549319834`)

      Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
  [Assets Collection][]

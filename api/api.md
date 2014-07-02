# iOffice API
The iOffice API provides access to many iOffice modules for CRUD operations

## Endpoints
The base URL will be https://[siteaddress]/external/api/rest/v2/

All endpoints in the document are relative to this url.

Note: on development servers this will be http over port 8080 so there will be a need to specify protocol, but default to https (if not specified)


## Authentication
In order to authenticate your request, in each request include the following in the header.
+ Headers
            x-auth-password:PASSWORD
            x-auth-username:USERNAME

All requests are made over https. 

## Media Types
Where applicable this API uses the JSON media-type to represent resources states and affordances.

Requests with a message-body are using plain JSON to set or update resource states.

## Error States
The common [HTTP Response Status Codes](https://github.com/for-GET/know-your-http-well/blob/master/status-codes.md) are used.

## Global Request Params
| Paramater  | Value |
| ------------- | ------------- |
| limit | maximum results to show (default: 50)  |
| startAt | for pagination, the offset of where to start (default: 0)  |

## Resource Requests
NOTE: When creating/updating an object, all that is needed is the ID of new object
        
        e.g. Upating a resource's contact to another with an ID of 5
        + Request (application/json)
                {
                    contact: {
                        id: 5
                    }
                }


# Group Maintenance Request
iOffice Service Request is known as the maintenance module internally.

## Request [/maintenance/requests/{id}]
A single request object.  The Request resource is the main component of the service request api.

The Request resource has the following attributes: 

-id
-dateCreated
-dateRequired
-dateUpdated
-type
-requestStatus
-requester
-requesterPrimaryContact
-totalOperatorsNeeded
-contact
-assetStatus
-center
-fieldValue
-priority
-asset
-scheduledTask
-operators
-attachments
-warning
-room
-fields
-completed
-supplies
-valueFields

+ Parameters
    + id (string) ... ID of the Request

+ Model (application/json)
    JSON representation of the Request Resource

    + Body

            {
                requestStatus: {},
                requester: {},
                requesterPrimaryContact: BOOLEAN,
                type: {},
                totalOperatorsNeeded: INT,
                dateRequired: EPOCH_TIME,
                contact: {},
                assetStatus: STATUS_STRING,
                dateUpdated: EPOCH_TIME,
                center: {},
                id: REQUEST_ID,
                fieldValue: [ ],
                priority: {},
                dateCreated: EPOCH_TIME,
                scheduledTask: BOOLEAN,
                operators: [],
                attachments: [ ],
                warning: {},
                room: {},
                fields: [ ],
                completed: BOOLEAN,
                supplies: [ ],
                valueFields: [ ]
            }

### Retrieve a Single Request [GET]
+ Response 200

    [Request][]

### Edit a Request [PUT]
To update a Request send JSON with updated value for one or more of the attributes.
+ Request (application/json)

        {
            "room": {
                id: 5
            }
        }
+ Response 200
    
    [Request][]

## Requests Collection [/maintenance/requests]
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

### List of all Requests [GET]
+ Response 200
    
    [Requests Collection][]

### Create a Request [POST]
The following attributes are required to create a Request: *dateRequired*, *requester*, *type*, *priority*, *room*

NOTE: If the request type's "assetRequest" attribute is TRUE, then an "asset" attribute is required as well.

+ Request (application/json)

        {
            "dateRequired": EPOCH_TIME,
            "requester": {
                id: REQUESTER_ID,
            },
            "type": {
                id: TYPE_ID,
            },
            "priority": {
                id: PRIORITY_ID,
            },
            "room": {
                id: ROOM_ID,
            }
        }

+ Response 201

    [Request][]

## Requests Collection Stats [/maintenance/requests/stats]
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
                assignedCount: INT
                highPriorityCount: INT
                lowPriorityCount: INT
                pastDueCount: INT
                totalCount: INT
            }

### Request Statistics [GET]
+ Response 200
    
    [Requests Collection Stats][]


## Add Comment [/maintenance/requests/{id}/addComment]
Add a comment to a request

+ Parameters

    + id (string) ... ID of the Request

+ Model (application/json)
    HTML string of all comments for the request

    + Body

            <div class='Content'>YOUR COMMENT</div></div>

### Add a comment to a Request [POST]

+ Request (application/json)

        {
            "dateRequired": COMMENT_STRING
        }

+ Response 200

        <div class='Content'>YOUR COMMENT</div></div>


## Attach Image [/maintenance/requests/{id}/attachImage]
Attach an image to a request

+ Parameters

    + id (string) ... ID of the Request

+ Model (application/json)
    JSON representation of an attachment object

    + Body

            {
                id: ID
                storedFile: {
                    id: INTERNAL_STORAGEID
                }
                downloadURL: URL_RELATIVE_TO_SITE
                description: DESCRIPTION
                name: IMAGE_NAME
                fileName: FILE_NAME
                dateCreated: EPOCH_TIME
                image: BOOLEAN
                storageId: INTERNAL_STORAGEID
            }

### Attach an Image to a Request[POST]

+ Request (application/json)

        {
            "image": BASE-64-IMAGE-STRING
        }

+ Response 200
    [Attach Image][]


## Accept Request [/maintenance/requests/{id}/accept]
** User must be a valid operator**

Set operator's status for a request as accepted.

+ Parameters

    + id (string) ... ID of the Request

### Accept a Request [PUT]
+ Response 200
    [Request][]


## Reject Request [/maintenance/requests/{id}/reject]
** User must be a valid operator**

Set operator's status for a request as rejected.

+ Parameters

    + id (string) ... ID of the Request

### Reject a Request [PUT]
+ Response 200
    [Request][]


## Start Request [/maintenance/requests/{id}/start]
** User must be a valid operator**

Set operator's status for a request as started.

+ Parameters

    + id (string) ... ID of the Request

### Start a Request [PUT]
+ Response 200
    [Request][]

## Hold Request [/maintenance/requests/{id}/hold]
** User must be a valid operator**

Set operator's status for a request as on hold.

+ Parameters

    + id (string) ... ID of the Request

### Hold a Request [PUT]
+ Response 200
    [Request][]


## Resume Request [/maintenance/requests/{id}/resume]
** User must be a valid operator**

Set operator's status for a request as resumed.

+ Parameters

    + id (string) ... ID of the Request

### Resume a Request [PUT]
+ Response 200
    [Request][]


## Complete Request [/maintenance/requests/{id}/complete]
** User must be a valid operator**

Set operator's status for a request as complete.

+ Parameters

    + id (string) ... ID of the Request

### Complete a Request [PUT]
+ Response 200
    [Request][]



# Group Maintenance Category
The Category resource gives access to Products from which you can derive Request Types.

## Category [/maintenance/categories/{id}]
A single category object.

The Request resource has the following attributes: 

-id
-name
-products

+ Parameters
    + id (string) ... ID of the Category

+ Model (application/json)
    JSON representation of the Category Resource

    + Body

            {
                id: ID,
                name: STRING,
                products: []
            }

### Retrieve a Single Category [GET]
+ Response 200

    [Category][]

## Categories Collection [/maintenance/categories]
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

### List of all Categories [GET]
+ Response 200
    
    [Categories Collection][]



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

# Group User
User API

## User [/users/{id}]
A single user object.

The User resource has the following attributes: 

- id
- name
- userName
- firstName
- middleName
- lastName
- email
- phone
- extension
- mobile
- fax
- room
- employeeId
- department
- dateUpdated
- jobTitle
- knownAs
- company
- dateCreated
- costCenter1
- costCenter2
- comments


+ Parameters
    + id (string) ... ID of the User

+ Model (application/json)
    JSON representation of the User Resource

    + Body

            {
                employeeId: "34a43518334a4",
                custom02: "",
                phone: "55555555555",
                custom01: "",
                custom04: "",
                custom03: "",
                department: "",
                custom06: "",
                custom05: "",
                custom08: "",
                custom07: "",
                custom09: "",
                dateUpdated: 1382483811150,
                id: 9,
                firstName: "Fox",
                middleName: "",
                lastName: "McCloud",
                name: "Fox McCloud",
                userName: "foxmc",
                jobTitle: "developer",
                knownAs: "",
                costCenter2: "",
                fax: "",
                extension: "",
                email: "fmccloud@iofficecorp.com",
                company: "",
                dateCreated: 1382483811150,
                costCenter1: "",
                comments: "",
                mobile: "",
                room: {...}
            }

### Retrieve a Single User [GET]
+ Response 200

    [User][]

### Edit a User [PUT]
To update a User send JSON with updated value for one or more of the attributes.
    
+ Request (application/json)

        {
            "room": {
                id: 4
            }
        }

+ Response 200
    
    [User][]

## User Collection [/users{?search}{?centerId}{?role}]
Collection of all Users.

+ Model (application/json)
    JSON representation of the User Collection resource.

    + Body

            [
                {
                    "id":6
                    ...
                },
                {
                    "id":7
                    ...
                },
                {
                    "id":8
                    ...
                }
            ]

### List of all Users [GET]

+ Parameters
    + search (optional, string, `mario`) ... String to search for user by firstName, lastName, or email
    + centerId (optional, number, `12`) ... Id of center to query from. If `centerId` is provided `role` is _required_
    + role (optional, string, `operator`) ... Role name to query from. Valid values are: _administrator_, _operator_, _customer_, _manager_, and _technician_. If `role` is provided `centerId` is _required_
    

+ Response 200
    
    [User Collection][]


### Create a User [POST]
The following attributes are required to create a User: `firstName`, `lastName`, `email`.

+ Request (application/json)

            {
                firstName: 'Falco',
                lastName: 'Lombardi',
                email: flombardi@iofficecorp.com
            }

+ Response 201

    [User][]


# Group Building
Building API

## Building [/buildings/{id}]
A single building object.

The Building resource has the following attributes: 

- id
- address
- name
- code


+ Parameters
    + id (string) ... ID of the Building

+ Model (application/json)
    JSON representation of the Building Resource

    + Body

            {
                id: 43,
                address: {...},
                name: "Mystery Inc.",
                code: "mystery"
            }

### Retrieve a Single Building [GET]
+ Response 200

    [Building][]

### Edit a Building [PUT]
To update a Building send JSON with updated value for one or more of the attributes.
    
+ Request (application/json)

        {
            "address": {
                "postalCode": "77019"
            }
        }

+ Response 200
    
    [Building][]

## Building Collection [/buildings]
Collection of all Buildings.

+ Model (application/json)
    JSON representation of the Building Collection resource.

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

### List of all Buildings [GET]

+ Response 200
    
    [Building Collection][]


### Create a Building [POST]
The following attribute is required to create a Building: `name`.

+ Request (application/json)

            {
                name: 'Headquarters',
            }

+ Response 201

    [Building][]


# Group Floor
Floor API

## Floor [/floors/{id}]
A single floor object.

The Floor resource has the following attributes: 

- id
- building
- area
- name


+ Parameters
    + id (string) ... ID of the Floor

+ Model (application/json)
    JSON representation of the Floor Resource

    + Body

            {
                id: 5,
                building: {...},
                area: 2000,
                name: "1st Floor"
            }

### Retrieve a Single Floor [GET]
+ Response 200

    [Floor][]

### Edit a Floor [PUT]
To update a Floor send JSON with updated value for one or more of the attributes.
    
+ Request (application/json)

        {
            "name": "2nd Floor"
        }

+ Response 200
    
    [Floor][]

## Floor Collection [/floors{?buildingId}]
Collection of all Floors.

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

+ Response 200
    
    [Floor Collection][]


### Create a Floor [POST]
The following attributes are required to create a Floor: `name` and `building`.

+ Request (application/json)

            {
                name: '3rd Floor',
                building: {
                    "id": 45
                }
            }

+ Response 201

    [Floor][]


# Group Room
Room API

## Room [/rooms/{id}]
A single room object.

The Room resource has the following attributes: 

- id
- floor
- reservable
- name


+ Parameters
    + id (string) ... ID of the Room

+ Model (application/json)
    JSON representation of the Room Resource

    + Body

            {
                id: 52927,
                floor: {...},
                reservable: true,
                name: "010211"
            }

### Retrieve a Single Room [GET]
+ Response 200

    [Room][]

### Edit a Room [PUT]
To update a Room send JSON with updated value for one or more of the attributes.
    
+ Request (application/json)

        {
            "type": {
                id: 55
            }
        }

+ Response 200
    
    [Room][]

## Room Collection [/rooms{?includeReservable}{?includeNonReservable}{?locationSearch}{?nearLatitude}{?nearLongitude}{?startDate}{?endDate}{?numberOfPeople}{?search}{?building}{?roomType}{?floor}]
Collection of all Rooms.

+ Model (application/json)
    JSON representation of the Room Collection resource.

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

### List of all Rooms [GET]

+ Parameters
    + includeReservable (optional, boolean, `true`) ... If true, query will include reservable rooms
    + includeNonReservable (optional, boolean, `false`) ... If true, query will include non-reservable rooms
    + locationSearch (optional, string, `houston tx`) ... Will do a location lookup based on the search string.
    + nearLatitude (optional, number, `29.75613`) ... Latitude to base search on (50 mile radius)
    + nearLongitude (optional, number, `-95.39425`) ... Longitude to base search on (50 mile radius)
    + startDate (optional, number, `1404410211910`) ... Epoch time of room availablilty start date
    + endDate (optional, number, `1404421051661`) ... Epoch time of room availablilty end date
    + search (optional, string, `conference`) ... String to search for room by name
    + building (optional, number, `44`) ... Id of building to search in
    + floor (optional, number, `3443`) ... Id of floor to search on
    + roomType (optional, number, `65`) ... Id of room type to search for

+ Response 200
    
    [Room Collection][]


### Create a Room [POST]
The following attributes are required to create a Room: `name` and `type`.

+ Request (application/json)

            {
                name: 'room 101',
                type: {
                    id: 44
                }
            }

+ Response 201

    [Room][]


# Group Reservation
Reservation booking management

## Reservation [/reservations/{id}]
A single reservation object.

The Reservation resource has the following attributes: 

- id
- center
- numberOfPeople
- allDay
- name
- user
- dateUpdated
- room


+ Parameters
    + id (string) ... ID of the Reservation

+ Model (application/json)
    JSON representation of the Reservation Resource

    + Body

            {
                id: ID,
                center: {},
                numberOfPeople: INT,
                allDay: BOOLEAN,
                name: STRING,
                user: {},
                dateUpdated: EPOCH_TIME,
                room: {}
            }

### Retrieve a Single Reservation [GET]
+ Response 200

    [Reservation][]

### Edit a Reservation [PUT]
To update a Reservation send JSON with updated value for one or more of the attributes.
    
+ Request (application/json)

        {
            "user": {
                id: 56
            }
        }

+ Response 200
    
    [Reservation][]

## Reservation Collection [/reservations{?includeCancelled}{?includePastReservations}{?includeNonCancelled}{?showOnlyMyReservations}]
Collection of all Reservations.

+ Parameters
    + includeCancelled = `false` (optional, boolean, , `true`) ... If true, query will include cancelled reservations
    + includeNonCancelled = `true` (optional, boolean, , `false`) ... If true, query will include non-cancelled reservations
    + includePastReservations = `false` (optional, boolean, `true`) ... If true, query will include past reservations
    + showOnlyMyReservations = `true` (optional, boolean, `false`) ... If true, query will only include logged in user's reservations

+ Model (application/json)
    JSON representation of the Reservation Collection resource.

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

### List of all Reservations [GET]
+ Response 200
    
    [Reservation Collection][]


### Create a Reservation [POST]
The following attributes are required to create a Reservation: `startDate`, `endDate`, `user`, `room`, and `allDay`.

+ Request (application/json)

            {
                id: ID,
                startDate: EPOCH_TIME,
                endDate: EPOCH_TIME
                numberOfPeople: INT,
                allDay: BOOLEAN,
                name: STRING,
                user: {},
                guests: [],
                room: {},
                notes: STRING
            }

+ Response 201

    [Reservation][]

## Cancel [/reservations/{id}/cancel]
Cancel Reservation

+ Parameters

    + id (string) ... ID of the Reservation

### Cancel Reservation [PUT]
+ Response 200
    [Reservation][]


## Check In [/reservations/{id}/checkIn]
Reservation Check In

+ Parameters

    + id (string) ... ID of the Reservation

### Reservation Check In [PUT]
+ Response 200
    [Reservation][]


## Check Out [/reservations/{id}/checkOut]
Reservation Check Out

*Not available through the desktop app*

+ Parameters

    + id (string) ... ID of the Reservation

### Reservation Check Out [PUT]
+ Response 200
    [Reservation][]



# Group Maintenance Request
iOffice Service Request is known as the maintenance module internally.

## Request [/maintenance/requests/{id}]
A single request object.  The Request resource is the main component of the service request api.

The Request resource has the following attributes: 

- id
- dateCreated
- dateRequired
- dateUpdated
- type
- requestStatus
- requester
- requesterPrimaryContact
- totalOperatorsNeeded
- contact
- assetStatus
- center
- fieldValue
- priority
- asset
- scheduledTask
- operators
- attachments
- warning
- room
- fields
- completed
- supplies
- valueFields


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
The following attributes are required to create a Request: `dateRequired`, `requester`, `type`, `priority`, and `room`.

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

    + id (string) ... Id of the Request

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

    + id (string) ... Id of the Request

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

- id
- name
- products
- dateCreated
- dateRequired
- dateUpdated

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

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
User-related resources of *iOffice API*

## User [/users/{id}]
A single user object.

<!-- The User resource has the following attributes: 

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
- comments -->


+ Parameters
    + id (string) ... ID of the User

+ Model (application/json)
    JSON representation of the User Resource

    + Body

            {
                "employeeId": "34a43518334a4",
                "custom02": "",
                "phone": "55555555555",
                "custom01": "",
                "custom04": "",
                "custom03": "",
                "department": "",
                "custom06": "",
                "custom05": "",
                "custom08": "",
                "custom07": "",
                "custom09": "",
                "dateUpdated": 1382483811150,
                "id": 9,
                "firstName": "Fox",
                "middleName": "",
                "lastName": "McCloud",
                "name": "Fox McCloud",
                "userName": "foxmc",
                "jobTitle": "developer",
                "knownAs": "",
                "costCenter2": "",
                "fax": "",
                "extension": "",
                "email": "fmccloud@iofficecorp.com",
                "company": "",
                "dateCreated": 1382483811150,
                "costCenter1": "",
                "comments": "",
                "mobile": "",
                "room": {...}
            }

### Retrieve a Single User [GET]
+ Response 200

    [User][]

### Edit a User [PUT]
To update a User send JSON with updated value for one or more of the attributes.
    
+ Request (application/json)

        {
            "room": {
                "id": 4
            }
        }

+ Response 200
    
    [User][]

## User Collection [/users{?search, centerId, role}]
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
                "firstName": "Falco",
                "lastName": "Lombardi",
                "email": "flombardi@iofficecorp.com"
            }

+ Response 201

    [User][]

## Get current logged in user [/users/me]

Get data for currently logged in user

### Hold a Request [GET]
+ Response 200
    [User][]


# Group Building
Building-related resources of *iOffice API*

## Building [/buildings/{id}]
A single building object.

<!-- The Building resource has the following attributes: 

- id
- address
- name
- code -->


+ Parameters
    + id (string) ... ID of the Building

+ Model (application/json)
    JSON representation of the Building Resource

    + Body

            {
                "id": 43,
                "address": {...},
                "name": "Mystery Inc.",
                "code": "mystery"
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
                "name": "Headquarters",
            }

+ Response 201

    [Building][]


# Group Floor
Floor-related resources of *iOffice API*

## Floor [/floors/{id}]
A single floor object.

<!-- The Floor resource has the following attributes: 

- id
- building
- area
- name -->


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
                "name": "3rd Floor",
                "building": {
                    "id": 45
                }
            }

+ Response 201

    [Floor][]


# Group Room
Room-related resources of *iOffice API*

## Room [/rooms/{id}]
A single room object.

<!-- The Room resource has the following attributes: 

- id
- floor
- reservable
- name -->


+ Parameters
    + id (string) ... ID of the Room

+ Model (application/json)
    JSON representation of the Room Resource

    + Body

            {
                "id": 52927,
                "floor": {...},
                "reservable": true,
                "name": "010211"
            }

### Retrieve a Single Room [GET]
+ Response 200

    [Room][]

### Edit a Room [PUT]
To update a Room send JSON with updated value for one or more of the attributes.
    
+ Request (application/json)

        {
            "type": {
                "id": 55
            }
        }

+ Response 200
    
    [Room][]

## Room Collection [/rooms{?includeReservable, includeNonReservable, locationSearch, nearLatitude, nearLongitude, startDate, endDate, numberOfPeople, search, building, roomType, floor}]
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
                "name": "room 101",
                "type": {
                    "id": 44
                }
            }

+ Response 201

    [Room][]


# Group Asset
Asset-related resources of *iOffice API*

## Asset [/assets/{id}]
A single asset object.

<!-- The Asset resource has the following attributes: 

- id
- name
- model(asset model)
- managed
- boxLength
- titleLocation
- dateCreated
- dateUpdated
- active -->

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
            "model": {
                "id": 78
            }
        }

+ Response 200
    
    [Asset][]

## Asset Collection [/assets{?search, searchSerialNumber, typeId, buildingId, floorId, roomId, owner}]
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
The following attributes are required to create a Asset: `model`, `serialNumber`, and (`room` or `owner`).

+ Request (application/json)

            {
                "model": {
                    "id": 454
                },
                "serialNumber": "49867233"
                "room": {
                    "id": "57"
                }
            }

+ Response 201

    [Asset][]

## Verify an asset [/assets/{id}/verify]

Create a record of the time and user that audited an asset.

+ Parameters

    + id (string) ... Id of the Asset

### Verify Asset [PUT]
+ Response 204

## Attach Asset Image [/assets/{id}/attachImage]
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


# Group Reservation
Reservation-related resources of *iOffice API*

## Reservation [/reservations/{id}]
A single reservation object.

<!-- The Reservation resource has the following attributes: 

- id
- center
- numberOfPeople
- allDay
- name
- user
- dateUpdated
- room -->


+ Parameters
    + id (string) ... ID of the Reservation

+ Model (application/json)
    JSON representation of the Reservation Resource

    + Body

            {
                "id": ID,
                "center": {...},
                "numberOfPeople": INT,
                "allDay": "BOOLEAN",
                "name": "STRING",
                "user": {...},
                "dateUpdated": EPOCH_TIME,
                "room": {...}
            }

### Retrieve a Single Reservation [GET]
+ Response 200

    [Reservation][]

### Edit a Reservation [PUT]
To update a Reservation send JSON with updated value for one or more of the attributes.
    
+ Request (application/json)

        {
            "user": {
                "id": 56
            }
        }

+ Response 200
    
    [Reservation][]

## Reservation Collection [/reservations{?includeCancelled, includePastReservations, includeNonCancelled, showOnlyMyReservations}]
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
                "id": ID,
                startDate: EPOCH_TIME,
                "endDate": EPOCH_TIME
                "numberOfPeople": INT,
                "allDay": "BOOLEAN",
                "name": "STRING",
                "user": {...},
                "guests": [..],
                "room": {...},
                "notes": "STRING"
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


# Group Maintenance
Maintenance-related resources of *iOffice API*

iOffice Service Request is known as the maintenance module internally.


## Request [/maintenance/requests/{id}]
A single request object.  The Request resource is the main component of the service request api.

<!-- The Request resource has the following attributes: 

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
- valueFields -->


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
To update a Request send JSON with updated value for one or more of the attributes.

+ Request (application/json)

        {
            "room": {
                "id": 5
            }
        }
+ Response 200
    
    [Request][]

### Requests Collection [/maintenance/requests{?priority,?assigned,?pastDue}]
Collection of all Requests.

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


### Add Comment [/maintenance/requests/{id}/addComment]

Add a comment to a request

+ Parameters

    + id (string) ... Id of the Request

+ Model (application/json)
    HTML string of all comments for the request

    + Body

            <div class='Content'>YOUR COMMENT</div></div>

#### Add a comment to a Request [POST]

+ Request (application/json)

        {
            "dateRequired": "COMMENT_STRING"
        }

+ Response 200

        <div class='Content'>YOUR COMMENT</div></div>


### Attach Request Image [/maintenance/requests/{id}/attachImage]
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


### Accept Request [/maintenance/requests/{id}/accept]
** User must be a valid operator**

Set operator's status for a request as accepted.

+ Parameters

    + id (string) ... ID of the Request

#### Accept a Request [PUT]
+ Response 200
    [Request][]


### Reject Request [/maintenance/requests/{id}/reject]
** User must be a valid operator**

Set operator's status for a request as rejected.

+ Parameters

    + id (string) ... ID of the Request

#### Reject a Request [PUT]
+ Response 200
    [Request][]


### Start Request [/maintenance/requests/{id}/start]
** User must be a valid operator**

Set operator's status for a request as started.

+ Parameters

    + id (string) ... ID of the Request

#### Start a Request [PUT]
+ Response 200
    [Request][]

### Hold Request [/maintenance/requests/{id}/hold]
** User must be a valid operator**

Set operator's status for a request as on hold.

+ Parameters

    + id (string) ... ID of the Request

#### Hold a Request [PUT]
+ Response 200
    [Request][]


### Resume Request [/maintenance/requests/{id}/resume]
** User must be a valid operator**

Set operator's status for a request as resumed.

+ Parameters

    + id (string) ... ID of the Request

#### Resume a Request [PUT]
+ Response 200
    [Request][]


### Complete Request [/maintenance/requests/{id}/complete]
** User must be a valid operator**

Set operator's status for a request as complete.

+ Parameters

    + id (string) ... ID of the Request

#### Complete a Request [PUT]
+ Response 200
    [Request][]


## Request Type [/maintenance/types/{id}]

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

### Request Types Collection [/maintenance/types]
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



## Category [/maintenance/categories/{id}]

The Category resource gives access to Products from which you can derive Request Types.

A single category object.

<!-- The Request resource has the following attributes: 

- id
- name
- products
- dateCreated
- dateRequired
- dateUpdated -->

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

### Categories Collection [/maintenance/categories]
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


### Product [/maintenance/products/{id}]
A single product object.

<!-- The Request resource has the following attributes: 

- id
- name
- products
- dateCreated
- dateRequired
- dateUpdated -->

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

### Products Collection [/maintenance/products]
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



### Priority [/maintenance/priorities/{id}]
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

### Priorities Collection [/maintenance/priorities]
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



### Get Earliest Required Date [/maintenance/priorities/{id}/earliestRequiredDate{?typeId, centerId}]

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





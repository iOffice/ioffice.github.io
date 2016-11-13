# Group User
User-related resources of *iOffice API*

## User [/users{id}]
A single user object.

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

### Remove a User [DELETE]
+ Parameters
    + id (string) ... ID of the User
+ Response 200

## User Collection [/users{?search,centerId,role,siteAdmin,hasRoom}]
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
    + centerId (optional, number, `12`) ... Id of center to query from. If `centerId` is provided `role` is _required_
    + userTypeId (optional, number, `23`) ... If of user type to query from.
    + role (optional, string, `operator`) ... Role name to query from. Valid values are: _administrator_, _operator_, _customer_, _manager_, and _technician_. If `role` is provided `centerId` is _required_
    + siteAdmin (optional, boolean, `true`) ... If true, query will include users with Admin permissions
    + hasRoom (optional, boolean, `true`) ... If true, query will include users with rooms
    + hasDefaultVisitorCenter (optional, boolean, `true`) ... If true, query will include users with a default visitor center

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


### Retrieve Current User [GET]
+ Response 200
    [User][]

## Get Current User Report Auth Data [/users/me/reportAuth]

Get current user report auth data

### Retrieve Current User Report Auth Data [GET]
+ Response 200
    [User][]

## Get Current User Report Auth Data [/users/me/supportAuth]

Get current user report auth data

### Retrieve Current User Support Auth Data [GET]
+ Response 200
    [User][]
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
              "floorWarden": false,
              "lastName": "McCloud",
              "firstName": "Fox",
              "dateCreated": 1464727067663,
              "color": "#89ffa1",
              "name": "Fox McCloud",
              "id": 420,
              "userType": {
                "dateCreated": 1430925570820,
                "name": "Employee",
                "id": 1,
                "fields": [
                  {
                    "code": "company",
                    "name": "Company",
                    "id": 1
                  },
                  {
                    "code": "jobTitle",
                    "name": "Job Title",
                    "id": 2
                  },
                  {
                    "code": "phone",
                    "name": "Phone",
                    "id": 3
                  },
                  {
                    "code": "extension",
                    "name": "Extension",
                    "id": 4
                  },
                  {
                    "code": "mobile",
                    "name": "Mobile Phone Number",
                    "id": 6
                  },
                  {
                    "code": "employeeId",
                    "name": "Employee ID",
                    "id": 8
                  },
                  {
                    "code": "floorWarden",
                    "name": "Floor Warden",
                    "id": 12
                  },
                  {
                    "code": "specialNeeds",
                    "name": "Special Needs",
                    "id": 13
                  },
                  {
                    "code": "comments",
                    "name": "Comments",
                    "id": 14
                  },
                  {
                    "code": "alternateDelivery",
                    "name": "Alternate Delivery",
                    "id": 16
                  },
                  {
                    "code": "knownAs",
                    "name": "Known As",
                    "id": 17
                  }
                ]
              },
              "userName": "foxmc",
              "specialNeeds": false,
              "email": "fmccloud@iofficecorp.com",
              "dateUpdated": 1479077061110
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

### Attach a User Avatar [/users/{{id}/attachAvatar]
Attach an avatar to a User

+ Parameters

    + image: (string) ... Base64 binary encoded string of an image file.
    + fileName: (string) ... Name of the image file.

+ Model (application/json)
    JSON representation of an attachment object

    + Body

            {
                "image": "BASE-64-IMAGE-STRING",
                "fileName": "tiny_cat_12573_8950.jpg"
            }

#### Attach an Avatar to a User[PUT]

+ Request (application/json)

           {
                "image": "BASE-64-IMAGE-STRING",
                "fileName": "tiny_cat_12573_8950.jpg"
           }

+ Response 200

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
    + userTypeId (optional, number, `23`) ... Id of user type to query from.
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

### Get current logged in user [/users/me]

Get data for currently logged in user


### Retrieve Current User [GET]
+ Response 200
    [User][]

## Get availability of a username [/users/username/{{username}]

Get boolean value if {username} already exists


### Check if Username Exists [GET]

+ Response 200 (application/json)

            {
                "available": "true",
            }

## Get Current User Report Auth Data [/users/me/reportAuth]

Get current user report auth data

### Retrieve Current User Report Auth Data [GET]

+ Response 200 (application/json)

            {
                "server:" "http://andross.arwing.com",
                "authToken:" "a234893fmdfjhdkjh345897djhdjkh59",
                "orgId:" "dev_fmcloud",
                "username: "foxmccloud"
            }

## Get Current User Report Auth Data [/users/me/supportAuth]

Get current user report auth data

### Retrieve Current User Support Auth Data [GET]

+ Response 200 (application/json)

            {
                "server:" "http://support.andross.arwing.com",
                "authToken:" "imp_46436454_3452345345dgdg3q5345dsgdgsdg_=dev_fmccloud_420"
            }

## Reset User Password [/users/{{id}/resetPassword]

Sends password reset email to user

### Reset User Password [PUT]
+ Response 200
    [User][]

## Get User Permission Data [/users/{{id}/permissions]

Get user permission data

### Retrieve User Permissions [GET]

+ Response 200 (application/json)

            [
              {
                "role":"ADMINISTRATOR",
                "center":{
                  "name":"Asset Center",
                  "id":69
                }
              },
              {
                "role":"MANAGER",
                "center":{
                  "name":"Copy Center",
                  "id":67
                }
              },
              {
                "role":"OPERATOR",
                "center":{
                  "name":"File Room",
                  "id":77
                }
              },
              {
                "role":"ADMINISTRATOR",
                "center":{
                  "name":"Inventory Center",
                  "id":73
                }
              },
              {
                "role":"MANAGER",
                "center":{
                  "name":"Mail Center",
                  "id":68
                }
              },
              {
                "role":"CUSTOMER",
                "center":{
                  "name":"Move",
                  "id":76
                }
              },
              {
                "role":"OPERATOR",
                "center":{
                  "name":"Pending Queue",
                  "id":71
                }
              },
              {
                "role":"ADMINISTRATOR",
                "center":{
                  "name":"Pokestop",
                  "id":79
                }
              },
              {
                "role":"CUSTOMER",
                "center":{
                  "name":"Reservation",
                  "id":74
                }
              },
              {
                "role":"OPERATOR",
                "center":{
                  "name":"Reservation Center",
                  "id":78
                }
              },
              {
                "role":"MANAGER",
                "center":{
                  "allowRequestCancel":false,
                  "allowReferenceNumber":false,
                  "name":"Service Request",
                  "id":70,
                  "requestResolutionRequired":false
                }
              },
              {
                "role":"ADMINISTRATOR",
                "center":{
                  "name":"Space",
                  "id":75
                }
              },
              {
                "role":"CUSTOMER",
                "center":{
                  "name":"Visitors Center",
                  "id":72
                }
              }
            ]
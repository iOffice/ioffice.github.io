# Group User
User-related resources of *iOffice API*

## User [/users///{id}]
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
            "jobTitle": "Developer",
        }

+ Response 200

### Remove a User [DELETE]
+ Parameters
    + id (string) ... ID of the User
    
+ Response 200
    [User][]



## Attach an Avatar to a User [/users///{id}/attachAvatar]
Attach an Avatar to a User

+ Parameters
    + id (string) ... ID of the User

### Attach an Avatar to a User [PUT]
The following attributes are required to attach an avatar: `image`, `fileName`.

+ Request (application/json)

           {
                "image": "BASE-64-IMAGE-STRING",
                "fileName": "tiny_cat_12573_8950.jpg"
           }

+ Response 200
    [User][]


## User Collection [/users{?search,centerId,userTypeId,role,siteAdmin,hasRoom,hasDefaultVisitorCenter}]
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

## Get availability of a username [/users/username///{username}]
Get boolean value if {username} already exists

+ Parameters
    + username (string) ... 


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

## Reset User Password [/users///{id}/resetPassword]
Sends password reset email to user

### Reset User Password [PUT]
+ Parameters
    + id (string) ... ID of the User
    
+ Response 200
    [User][]

## User Permission Data [/users///{id}/permissions]

User permission data for a single user 

### Retrieve User Permissions [GET]
+ Parameters
    + id (string) ... ID of the User  
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
                "role":"CUSTOMER",
                "center":{
                  "name":"Inventory Center",
                  "id":22
                }
            ]

### Edit User Permissions [PUT]
+ Parameters
    + id (string) ... ID of the User 

+ Request (application/json)  
    
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
                "role":"CUSTOMER",
                "center":{
                  "name":"Inventory Center",
                  "id":22
                }
            ]
            
+ Response 200
    [User][]

# Group Mail
Mail-related resources of *iOffice API*

## User [/mail/items//{id}]
A single mail item object.

+ Parameters
    + id (string) ... ID of the Mail Item


+ Model (application/json)
    JSON representation of the User Resource

    + Body

{
  "itemType": "INBOUND",
  "originalTrackingNumber": "1234567890",
  "deliveryType": "Other",
  "packageType": {
    "code": "env",
    "dateCreated": 1345679479550,
    "sortOrder": 3,
    "name": "Envelope",
    "id": 1,
    "dateUpdated": 1465239263837
  },
  "deliverTo": {
    "costCenter1": "Finance",
    "lastName": "Rodriguez",
    "extension": "",
    "color": "#9df9f6",
    "jobTitle": "",
    "specialNeeds": false,
    "dateCreated": 1366306611990,
    "custom06": "false",
    "id": 126,
    "costCenter2": "FIN001",
    "email": "null@null.com",
    "costCenter": {
      "hexColor": "ffff66",
      "code": "F001",
      "depth": {
        "code": "CC",
        "dateCreated": 1453906967017,
        "level": 3,
        "name": "Cost Center",
        "id": 19,
        "category": {
          "code": "CC56",
          "dateCreated": 1448996782500,
          "color": {},
          "name": "Cost Center Level",
          "id": 1,
          "dateUpdated": 1495646953000
        },
        "dateUpdated": 1468549300793
      },
      "color": {},
      "name": "FIN001",
      "id": 13,
      "category": {
        "code": "CC56",
        "dateCreated": 1448996782500,
        "color": {},
        "name": "Cost Center Level",
        "id": 1,
        "dateUpdated": 1495646953000
      },
      "costCenterParent": {
        "hexColor": "ffff99",
        "code": "FIN",
        "depth": {
          "code": "DEPT",
          "dateCreated": 1383752891820,
          "level": 2,
          "name": "Department",
          "id": 5,
          "category": {
            "code": "CC56",
            "dateCreated": 1448996782500,
            "color": {},
            "name": "Cost Center Level",
            "id": 1,
            "dateUpdated": 1495646953000
          },
          "dateUpdated": 1468549307390
        },
        "color": {},
        "name": "Finance",
        "id": 12,
        "category": {
          "code": "CC56",
          "dateCreated": 1448996782500,
          "color": {},
          "name": "Cost Center Level",
          "id": 1,
          "dateUpdated": 1495646953000
        },
        "costCenterParent": {
          "hexColor": "ffffcc",
          "code": "FP",
          "depth": {
            "code": "DIV",
            "dateCreated": 1181403908747,
            "level": 1,
            "name": "Division",
            "id": 1,
            "category": {
              "code": "CC56",
              "dateCreated": 1448996782500,
              "color": {},
              "name": "Cost Center Level",
              "id": 1,
              "dateUpdated": 1495646953000
            },
            "dateUpdated": 1459547103227
          },
          "color": {},
          "name": "Financial Planning",
          "id": 11,
          "category": {
            "code": "CC56",
            "dateCreated": 1448996782500,
            "color": {},
            "name": "Cost Center Level",
            "id": 1,
            "dateUpdated": 1495646953000
          },
          "costCenterParent": {
            "hexColor": "e3c85c",
            "code": "iOffice",
            "dateCreated": 1383754710773,
            "depth": {
              "code": "COMP",
              "dateCreated": 1415645409253,
              "level": 0,
              "name": "Company",
              "id": 7,
              "category": {
                "code": "CC56",
                "dateCreated": 1448996782500,
                "color": {},
                "name": "Cost Center Level",
                "id": 1,
                "dateUpdated": 1495646953000
              },
              "dateUpdated": 1471543311517
            },
            "color": {},
            "name": "iOffice",
            "id": 21,
            "category": {
              "code": "CC56",
              "dateCreated": 1448996782500,
              "color": {},
              "name": "Cost Center Level",
              "id": 1,
              "dateUpdated": 1495646953000
            },
            "dateUpdated": 1493898776903
          },
          "dateUpdated": 1454939726510
        },
        "dateUpdated": 1350512529593
      },
      "dateUpdated": 1350512529593
    },
    "mobile": "",
    "employeeId": "",
    "userName": "jrod",
    "room": {
      "area": 172.3,
      "dateCreated": 1337878957120,
      "reservable": false,
      "name": "620",
      "description": "",
      "id": 236,
      "mailStop": {
        "name": "Stop 1",
        "id": 139
      },
      "type": {
        "hexColor": "e591eb",
        "color": {},
        "name": "OFFICE",
        "occupiable": true,
        "id": 2,
        "parkingSpace": false,
        "dateUpdated": 1511306354367
      },
      "floor": {
        "area": 22126.75,
        "dateCreated": 1337878873300,
        "drawingAvailable": true,
        "name": "06",
        "id": 3,
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
            "street": "1598 Dallas",
            "postalCode": "77539",
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
          "dateCreated": 1107466065320,
          "metric": false,
          "name": "Houston Tower 2",
          "location": {},
          "id": 43,
          "dateUpdated": 1510606074980
        },
        "dateUpdated": 1412626222507
      },
      "capacity": 1,
      "dateUpdated": 1412626223240
    },
    "dateUpdated": 1502134536563,
    "firstName": "Jessica",
    "phone": "",
    "name": "Jessica Rodriguez",
    "mailStop": {
      "name": "Houston Stop 1",
      "id": 152
    },
    "userType": {
      "dateCreated": 1428954498147,
      "name": "Employee",
      "id": 1,
      "fields": [
        {
          "code": "company",
          "name": "Company",
          "id": 1
        },
        ...
        {
          "code": "costCenter2",
          "name": "Cost Center - Legacy",
          "id": 60
        }
      ],
      "dateUpdated": 1510088654037
    }
  },
  "currentQueue": "IN",
  "toUser": {
    "costCenter1": "Finance",
    "lastName": "Rodriguez",
    "extension": "",
    "color": "#9df9f6",
    "jobTitle": "",
    "specialNeeds": false,
    "dateCreated": 1366306611990,
    "custom06": "false",
    "knownAs": "",
    "company": "",
    "id": 126,
    "department": "",
    "fax": "",
    "costCenter2": "FIN001",
    "email": "null@null.com",
    "floorWarden": false,
    "comments": "",
    "costCenter": {
      "hexColor": "ffff66",
      "code": "F001",
      "depth": {
        "code": "CC",
        "dateCreated": 1453906967017,
        "level": 3,
        "name": "Cost Center",
        "id": 19,
        "category": {
          "code": "CC56",
          "dateCreated": 1448996782500,
          "color": {},
          "name": "Cost Center Level",
          "id": 1,
          "dateUpdated": 1495646953000
        },
        "dateUpdated": 1468549300793
      },
      "color": {},
      "name": "FIN001",
      "id": 13,
      "category": {
        "code": "CC56",
        "dateCreated": 1448996782500,
        "color": {},
        "name": "Cost Center Level",
        "id": 1,
        "dateUpdated": 1495646953000
      },
      "costCenterParent": {
        "hexColor": "ffff99",
        "code": "FIN",
        "depth": {
          "code": "DEPT",
          "dateCreated": 1383752891820,
          "level": 2,
          "name": "Department",
          "id": 5,
          "category": {
            "code": "CC56",
            "dateCreated": 1448996782500,
            "color": {},
            "name": "Cost Center Level",
            "id": 1,
            "dateUpdated": 1495646953000
          },
          "dateUpdated": 1468549307390
        },
        "color": {},
        "name": "Finance",
        "id": 12,
        "category": {
          "code": "CC56",
          "dateCreated": 1448996782500,
          "color": {},
          "name": "Cost Center Level",
          "id": 1,
          "dateUpdated": 1495646953000
        },
        "costCenterParent": {
          "hexColor": "ffffcc",
          "code": "FP",
          "depth": {
            "code": "DIV",
            "dateCreated": 1181403908747,
            "level": 1,
            "name": "Division",
            "id": 1,
            "category": {
              "code": "CC56",
              "dateCreated": 1448996782500,
              "color": {},
              "name": "Cost Center Level",
              "id": 1,
              "dateUpdated": 1495646953000
            },
            "dateUpdated": 1459547103227
          },
          "color": {},
          "name": "Financial Planning",
          "id": 11,
          "category": {
            "code": "CC56",
            "dateCreated": 1448996782500,
            "color": {},
            "name": "Cost Center Level",
            "id": 1,
            "dateUpdated": 1495646953000
          },
          "costCenterParent": {
            "hexColor": "e3c85c",
            "code": "iOffice",
            "dateCreated": 1383754710773,
            "depth": {
              "code": "COMP",
              "dateCreated": 1415645409253,
              "level": 0,
              "name": "Company",
              "id": 7,
              "category": {
                "code": "CC56",
                "dateCreated": 1448996782500,
                "color": {},
                "name": "Cost Center Level",
                "id": 1,
                "dateUpdated": 1495646953000
              },
              "dateUpdated": 1471543311517
            },
            "color": {},
            "name": "iOffice",
            "id": 21,
            "category": {
              "code": "CC56",
              "dateCreated": 1448996782500,
              "color": {},
              "name": "Cost Center Level",
              "id": 1,
              "dateUpdated": 1495646953000
            },
            "dateUpdated": 1493898776903
          },
          "dateUpdated": 1454939726510
        },
        "dateUpdated": 1350512529593
      },
      "dateUpdated": 1350512529593
    },
    "mobile": "",
    "employeeId": "",
    "userName": "jrod",
    "room": {
      "area": 172.3,
      "dateCreated": 1337878957120,
      "reservable": false,
      "name": "620",
      "description": "",
      "id": 236,
      "mailStop": {
        "name": "Stop 1",
        "id": 139
      },
      "type": {
        "hexColor": "e591eb",
        "color": {},
        "name": "OFFICE",
        "occupiable": true,
        "id": 2,
        "parkingSpace": false,
        "dateUpdated": 1511306354367
      },
      "floor": {
        "area": 22126.75,
        "dateCreated": 1337878873300,
        "drawingAvailable": true,
        "name": "06",
        "id": 3,
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
            "street": "1598 Dallas",
            "postalCode": "77539",
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
          "dateCreated": 1107466065320,
          "metric": false,
          "name": "Houston Tower 2",
          "location": {},
          "id": 43,
          "dateUpdated": 1510606074980
        },
        "dateUpdated": 1412626222507
      },
      "capacity": 1,
      "dateUpdated": 1412626223240
    },
    "dateUpdated": 1502134536563,
    "firstName": "Jessica",
    "phone": "",
    "name": "Jessica Rodriguez",
    "mailStop": {
      "name": "Houston Stop 1",
      "id": 152
    },
    "userType": {
      "dateCreated": 1428954498147,
      "name": "Employee",
      "id": 1,
      "fields": [
        {
          "code": "company",
          "name": "Company",
          "id": 1
        },
		...
        {
          "code": "costCenter2",
          "name": "Cost Center - Legacy",
          "id": 60
        }
      ],
      "dateUpdated": 1510088654037
    }
  },
  "route": {
    "forShipping": false,
    "dateCreated": 1389629005210,
    "name": "Houston Route 1",
    "id": 56,
    "dateUpdated": 1496351321157
  },
  "courier": {
    "code": "OTHER",
    "dateCreated": 1064937226683,
    "name": "Other",
    "id": 5,
    "dateUpdated": 1066939059227
  },
  "fromName": "Amazon",
  "statuses": [
    {
      "center": {
        "name": "Houston Mail Center",
        "id": 83
      },
      "id": 5082,
      "enteredBy": {
        "floorWarden": false,
        "lastName": "Ortiz",
        "color": "#ffc1ee",
        "userName": "portiz",
        "specialNeeds": false,
        "room": {
          "area": 0,
          "longDescription": "",
          "dateCreated": 1458100900920,
          "reservable": false,
          "name": "bum room",
          "description": "testy two",
          "id": 2262,
          "type": {
            "hexColor": "e591eb",
            "color": {},
            "name": "OFFICE",
            "occupiable": true,
            "id": 2,
            "parkingSpace": false,
            "dateUpdated": 1511306354367
          },
          "floor": {
            "area": 0,
            "dateCreated": 1458100879220,
            "drawingAvailable": false,
            "name": "booty floor",
            "id": 35,
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
                "city": "Dallas",
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
              "dateCreated": 1457965234447,
              "metric": false,
              "name": "Dallas",
              "location": {},
              "id": 89,
              "dateUpdated": 1510606074740
            }
          },
          "capacity": 1,
          "dateUpdated": 1458838307373
        },
        "dateUpdated": 1512069032603,
        "firstName": "Pita",
        "dateCreated": 1449758032933,
        "name": "Pita Ortiz",
        "id": 264,
        "mailStop": {
          "name": "Houston Stop 4",
          "id": 151
        },
        "userType": {
          "dateCreated": 1428954498147,
          "name": "Employee",
          "id": 1,
          "fields": [
            {
              "code": "company",
              "name": "Company",
              "id": 1
            },
            ...
            {
              "code": "costCenter2",
              "name": "Cost Center - Legacy",
              "id": 60
            }
          ],
          "dateUpdated": 1510088654037
        },
        "email": "pita@iofficecorp.com"
      }
    }
  ],
  "id": 3012,
  "trackingNumber": "DJAHABALAB"
}

### Retrieve a Single User [GET]
+ Response 200

    [User][]

### Edit a User [PUT]
To update a User send JSON with updated value for one or more of the attributes.
   <br/><br/>
  **Updating a User's Cost Center(s)**

* To update a User's default Cost Center (Category ID equals 1) send JSON with updated value for the `costCenter` attribute.  
	<br/>
* To update a User's non-default Cost Center(s) (Category ID is greater than 1) send JSON with updated value for the `costCenters` attribute.    
+ Request (application/json)

        {
            "id": 420,
            "jobTitle": "Developer",
            "costCenter": { "id": 88 },
            "costCenters": [
                        	{
                        		"id": 1234
                        	},
                        	{
                        		"id": 5678
                        	}
            ]
        }

+ Response 200

### Remove a User [DELETE]
+ Parameters
    + id (string) ... ID of the User
    
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }
           
## Attach an Avatar to a User [/users///{id}/attachAvatar]
Attach an Avatar to a User

+ Parameters
    + id (string) ... ID of the User

### Attach an Avatar to a User [POST]
The following attributes are required to attach an avatar: `image`, `fileName`.

+ Request (application/json)

           {
                "image": "BASE-64-IMAGE-STRING",
                "fileName": "tiny_cat_12573_8950.jpg"
           }

+ Response 200
    [User][]


## User Collection [/users///{?search,centerId,userTypeId,role,siteAdmin,hasRoom,hasDefaultVisitorCenter}]
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

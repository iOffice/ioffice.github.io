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
To update a User send JSON with the User's `ID` and updated value for one or more of the attributes.
   <br/><br/>
  **Updating a User's Cost Center(s)**

* To update a User's default Cost Center (Category ID equals 1) send JSON with the User's `ID` and updated value for the `costCenter` attribute.  
	<br/>
* To update a User's non-default Cost Center(s) (Category ID is greater than 1) send JSON with the User's `ID` and updated value for the `costCenters` attribute.  

+ Parameters
    + id (string) ... ID of the User
 
+ Request (application/json)

        {
            "id": 23,
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


## User Collection [/users///{?search,centerId,userTypeId,role,siteAdmin,hasRoom,hasDefaultVisitorCenter,modifiedOrCreatedAfter,savedSearchId}]
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
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.
    + savedSearchId (optional, string) ... Saved Search Id used to filter the Users list.

+ Response 200
    
    [User Collection][]
	
### Search Users [GET]

+ Parameters

	+ limit (optional, number, `20`) ... To limit the number of result records
    + orderBy (string, `firstName`) ... To sort the result basis firstName 
    + orderByType (string, `asc`) ... To sort the result in Ascending order 
    + search (string, `API`) ... Text to Search
    + selector: (string, `email%2CfirstName%2Cimage(smallSquare)%2CjobTitle%2ClastName%2CneighborhoodSection(floor(building)%2Cneighborhood%2Crooms(floor(building)))%2Cphone%2Croom(active%2Cfloor(building))%2CseatClassification`)
    + startAt: (number, `0`)

+ Response 200
	
	[
	  {
		"firstName": "API",
		"lastName": "USER",
		"seatClassification": "remote",
		"name": "API USER",
		"id": 3482,
		"email": "vwilliams@iofficecorp.com"
	  },
	  {
		"firstName": "Cutomer",
		"lastName": "API",
		"seatClassification": "remote",
		"name": "Cutomer API",
		"id": 4293,
		"email": "Rushikesh.Mali@eptura.com"
	  },
	  {
		"firstName": "Sergo API",
		"lastName": "Customer",
		"seatClassification": "remote",
		"name": "Sergo API Customer",
		"id": 4294,
		"email": "sergeo.nevdah+4@eptura.com"
	  }
	]
	

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

## User Quick Search Collection [/users/quicksearch]

+ Model (application/json)
    JSON representation of the User Collection resource.

## User Quick Search [POST]

Gets a collection of Users filtered by the search object posted.

Note:

- matchingType = true -> Match all filters.
- matchingType = false -> Match any filter.
    
+ Request (application/json)

			{
            	"availability": "EVERYONE",
            	"filters": 
            	[
            		{
            			"qualifier": "CONTAINS",
                        "valueString": "fox.mccloud",
                        "propertyPath": "email",
                        "name": ""
            		}
            	],
            	"itemClassName": "com.iofficeconnect.user.User",
            	"matchingType": false,
            	"name": ""
            }

+ Response 200
    
    [User Collection][]

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

## Logged In User Details [/users/me]
Details of Logged-In User

### Logged In User Info [GET /users/me/{?selector}]
*'selector' expects email/permissions value in parameter if required*

+ Parameters
    + selector (optional, string, `email%2CfirstName%2CuserName, permissions(center(module)%2Crole)%2CsiteAdmin`) ... Selector ID

+ Response 200

      {
          "floorWarden": false,
          "lastName": "Wagh",
          "color": "#F29373",
          "userName": "ashitosh.wagh",
          "passwordResetAttemptsRemaining": 0,
          "specialNeeds": false,
          "dateUpdated": 1670333174840,
          "firstName": "Ashitosh",
          "dateCreated": 1652274992497,
          "phone": "1246575001001",
          "knownAs": "Admin",
          "passwordResetEmailSentAt": 1667305525963,
          "name": "Admin Wagh",
          "id": 3951,
          "userType": {
              "dateCreated": 1428954498147,
              "name": "Employee",
              "id": 1,
              "dateUpdated": 1669893659410
          },
          "email": "ashitosh.wagh@eptura.com"
      }
	  
## User Types [/users/types]

### Retrieve Collection of User Types [GET]

+ Parameters
    + selector (optional, string, `id,name,fields(id,required,sortOrder,baseField(id))`) ... Selector ID

+ Response 200

   [
	  {
		"name": "Employee",
		"id": 1,
		"fields": [
		  {
			"code": "custom03",
			"sortOrder": 3,
			"name": "Employee ID",
			"id": 95,
			"required": false,
			"baseField": {
			  "code": "custom03",
			  "name": "Employee ID",
			  "id": 25
			}
		  },
		  {
			"code": "phone",
			"sortOrder": 3,
			"name": "Phone",
			"id": 3,
			"required": false,
			"baseField": {
			  "code": "phone",
			  "name": "Phone",
			  "id": 12
			}
		  },
		  {
			"code": "custom04",
			"sortOrder": 4,
			"name": "Custom04 Time_15Mar2023",
			"id": 96,
			"required": false,
			"baseField": {
			  "code": "custom04",
			  "name": "Custom04 Time_15Mar2023",
			  "id": 26
			}
		  },
		  {
			"code": "postalCode",
			"sortOrder": 5,
			"name": "Postal Code",
			"id": 97,
			"required": false,
			"baseField": {
			  "code": "postalCode",
			  "name": "Postal Code",
			  "id": 10
			}
		  },
		  {
			"code": "employeeId",
			"sortOrder": 6,
			"name": "Employee ID",
			"id": 98,
			"required": false,
			"baseField": {
			  "code": "employeeId",
			  "name": "Employee ID",
			  "id": 35
			}
		  },
		  {
			"code": "department",
			"sortOrder": 7,
			"name": "Department",
			"id": 9,
			"required": false,
			"baseField": {
			  "code": "department",
			  "name": "Department",
			  "id": 32
			}
		  }
		]
	  },
	  {
		"name": "Contractors",
		"id": 2,
		"fields": [
		  {
			"code": "company",
			"sortOrder": 1,
			"name": "Company",
			"id": 16,
			"required": true,
			"baseField": {
			  "code": "company",
			  "name": "Company",
			  "id": 21
			}
		  },
		  {
			"code": "jobTitle",
			"sortOrder": 2,
			"name": "Job Titles",
			"id": 80,
			"required": false,
			"baseField": {
			  "code": "jobTitle",
			  "name": "Job Titles",
			  "id": 7
			}
		  }
		]
	  },
	  {
		"name": "Visitor",
		"id": 7,
		"fields": [
		  {
			"code": "phone",
			"sortOrder": 1,
			"name": "Phone",
			"id": 89,
			"required": false,
			"baseField": {
			  "code": "phone",
			  "name": "Phone",
			  "id": 12
			}
		  },
		  {
			"code": "company",
			"sortOrder": 2,
			"name": "Company",
			"id": 90,
			"required": false,
			"baseField": {
			  "code": "company",
			  "name": "Company",
			  "id": 21
			}
		  }
		]
	  },
	  {
		"name": "Client",
		"id": 8,
		"fields": []
	  }
	]
	
### Retrieve Single User Type [GET /users/types/{id}?{selector}]

+ Parameters
    + id (string) ... ID of the User Type
	+ selector (optional, string, `id,name,fields(id,required,sortOrder,baseField(id))`) ... Selector ID

+ Response 200
	{
		"id":8,
		"fields": [],
		"name": "Client"
	}



### Create New User Type [POST]

This API creates new User Type

+ Request (application/json)

    {
		"fields": [],
		"name": "Client"
	}

+ Response 201

    {
		"dateCreated": 1680535828250,
		"name": "Client",
		"id": 8
	}

### Update/Remove User Type [PUT /users/types/{id}]

+ active (optional, boolean, `false`) ... Set it to false to remove a User Type

+ Request (application/json)

    {
	  "name": "Client",
	  "id": 8,
	  "fields": [],
	  "active": false
	}

+ Response 200

    {
	  "name": "Client",
	  "id": 8,
	  "dateUpdated": 1680536803197
	}


## User Fields [/fields]
Fields related resources of *iOffice API*

+ Model (application/json)
  JSON representation of the Category	Resource

### Retrieve Collection of User Fields [GET]
+ Parameters
    + mappingCode (`categoryDepth or building` )

+ Response 200
  [
  {
  "displayType": "Input",
  "code": "description",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Description",
  "dynamic": false,
  "id": 395,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom01",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Hello",
  "dynamic": false,
  "id": 401,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom02",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom02",
  "dynamic": false,
  "id": 402,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom03",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom03",
  "dynamic": false,
  "id": 403,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom04",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom04",
  "dynamic": false,
  "id": 404,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom05",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom05",
  "dynamic": false,
  "id": 405,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom06",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom06",
  "dynamic": false,
  "id": 406,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom07",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom07",
  "dynamic": false,
  "id": 407,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom08",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom08",
  "dynamic": false,
  "id": 408,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom09",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom09",
  "dynamic": false,
  "id": 409,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom10",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom10",
  "dynamic": false,
  "id": 410,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom11",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom11",
  "dynamic": false,
  "id": 411,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom12",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom12",
  "dynamic": false,
  "id": 412,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom13",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom13",
  "dynamic": false,
  "id": 413,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom14",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom14",
  "dynamic": false,
  "id": 414,
  "mappingCode": "categoryDepth",
  "required": false
  },
  {
  "displayType": "Input",
  "code": "custom15",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "Custom15",
  "dynamic": false,
  "id": 415,
  "mappingCode": "categoryDepth",
  "required": false
  }
  ]

### Update Field [PUT]
+ Request (application/json)
  {
  "id":385,
  "name":"My test"
  }
+ Response 200
  {
  "displayType": "Input",
  "code": "custom06",
  "validationAlert": "You must enter a valid value for this field.",
  "dataType": "TEXT",
  "options": "{\"password\":false,\"multiline\":false}",
  "length": 500,
  "name": "My test ",
  "dynamic": false,
  "id": 385,
  "mappingCode": "building",
  "required": false
  }


# Group Move
Move-related resources of *iOffice API*

## Move [/move/requests///{id}]
A single move object.

+ Parameters
    + id (string) ... ID of the Move Request


+ Model (application/json)
    JSON representation of the Move Resource

    + Body

             {  
               {
                 "date": 1504112404863,
                 "requester":{
                       "floorWarden":false,
                       "lastName":"Vader",
                       "firstName":"Darth",
                       "dateCreated":1464727067663,
                       "color":"#89ffa1",
                       "name":"Darth Vader",
                       "id":9,
                       "userType":{
                          "dateCreated":1430925570820,
                          "name":"Employee",
                          "id":1,
                          "fields":[
                             {
                                "code":"company",
                                "name":"Company",
                                "id":1
                             },
                             {
                                "code":"jobTitle",
                                "name":"Job Title",
                                "id":2
                             },
                             {
                                "code":"phone",
                                "name":"Phone",
                                "id":3
                             },
                             {
                                "code":"extension",
                                "name":"Extension",
                                "id":4
                             },
                             {
                                "code":"mobile",
                                "name":"Mobile Phone Number",
                                "id":6
                             },
                             {
                                "code":"employeeId",
                                "name":"Employee ID",
                                "id":8
                             },
                             {
                                "code":"floorWarden",
                                "name":"Floor Warden",
                                "id":12
                             },
                             {
                                "code":"specialNeeds",
                                "name":"Special Needs",
                                "id":13
                             },
                             {
                                "code":"comments",
                                "name":"Comments",
                                "id":14
                             },
                             {
                                "code":"alternateDelivery",
                                "name":"Alternate Delivery",
                                "id":16
                             },
                             {
                                "code":"knownAs",
                                "name":"Known As",
                                "id":17
                             }
                          ]
                       },
                       "userName":"lordvader",
                       "specialNeeds":false,
                       "email":"lordvader@deathstar.com",
                       "dateUpdated":1488566587390
                    },
                 "approved": true,
                 "comments": [
                   {
                     "id": 92,
                     "content": "your comment here!"
                   }
                 ],
                 "dateCreated": 1469818235210,
                 "approvedBy": {
                   "floorWarden": false,
                   "lastName": "Admin",
                   "firstName": "Han",
                   "dateCreated": 1464727067663,
                   "color": "#89ffa1",
                   "name": "Han Solo",
                   "id": 9,
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
                   "userName": "hansolo",
                   "specialNeeds": false,
                   "email": "hansolo@iofficecorp.com",
                   "dateUpdated": 1488566587390
                 },
                 "description": "Customer Service's Move Request (7/09)",
                 "id": 16,
                 "status": {
                   "code": "sub",
                   "dateCreated": 1185984126540,
                   "name": "In Progress",
                   "id": 10
                 }
             }
          

## Retrieve a Single Move Request [GET]
+ Response 200

    [Move][]


## Edit a Move Request [PUT /move/requests]

To update a Move Request send JSON with the Move Request's `ID` and updated value for one or more of the attributes.

+ Request (application/json)

         {
           {
             "id": 23,
             "approved": true,
           }
         }

+ Response 200

          {
             "date": 1504112404863,
             "requester":{
                   "floorWarden":false,
                   "lastName":"Vader",
                   "firstName":"Darth",
                   "dateCreated":1464727067663,
                   "color":"#89ffa1",
                   "name":"Darth Vader",
                   "id":9,
                   "userType":{
                      "dateCreated":1430925570820,
                      "name":"Employee",
                      "id":1,
                      "fields":[
                         {
                            "code":"company",
                            "name":"Company",
                            "id":1
                         },
                         {
                            "code":"jobTitle",
                            "name":"Job Title",
                            "id":2
                         },
                         {
                            "code":"phone",
                            "name":"Phone",
                            "id":3
                         },
                         {
                            "code":"extension",
                            "name":"Extension",
                            "id":4
                         },
                         {
                            "code":"mobile",
                            "name":"Mobile Phone Number",
                            "id":6
                         },
                         {
                            "code":"employeeId",
                            "name":"Employee ID",
                            "id":8
                         },
                         {
                            "code":"floorWarden",
                            "name":"Floor Warden",
                            "id":12
                         },
                         {
                            "code":"specialNeeds",
                            "name":"Special Needs",
                            "id":13
                         },
                         {
                            "code":"comments",
                            "name":"Comments",
                            "id":14
                         },
                         {
                            "code":"alternateDelivery",
                            "name":"Alternate Delivery",
                            "id":16
                         },
                         {
                            "code":"knownAs",
                            "name":"Known As",
                            "id":17
                         }
                      ]
                   },
                   "userName":"lordvader",
                   "specialNeeds":false,
                   "email":"lordvader@deathstar.com",
                   "dateUpdated":1488566587390
                },
             "approved": true,
             "comments": [
               {
                 "id": 92,
                 "content": "your comment here!"
               }
             ],
             "dateCreated": 1469818235210,
             "approvedBy": {
               "floorWarden": false,
               "lastName": "Admin",
               "firstName": "Han",
               "dateCreated": 1464727067663,
               "color": "#89ffa1",
               "name": "Han Solo",
               "id": 9,
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
               "userName": "hansolo",
               "specialNeeds": false,
               "email": "hansolo@iofficecorp.com",
               "dateUpdated": 1488566587390
             },
             "id": 16,
             "items": [
               {
                 "toRoom": {
                   "dateCreated": 1465572191247,
                   "reservable": false,
                   "name": "49.0",
                   "description": "",
                   "id": 416,
                   "floor": {
                     "area": 23600.0167,
                     "dateCreated": 1465572160000,
                     "drawingAvailable": true,
                     "name": "1",
                     "id": 2,
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
                         "postalCode": "",
                         "state": {
                           "defaultSelected": false,
                           "code": "",
                           "name": "Other",
                           "id": 70
                         }
                       },
                       "dateCreated": 1465572158677,
                       "metric": false,
                       "name": "Built",
                       "id": 44,
                       "dateUpdated": 1465572159707
                     },
                     "dateUpdated": 1465572186757
                   },
                   "type": {
                     "hexColor": "33cc99",
                     "color": {},
                     "name": "WKST",
                     "occupiable": true,
                     "id": 1,
                     "parkingSpace": false
                   },
                   "capacity": 1
                 },
                 "toRoomAvailable": true,
                 "name": "Han Solo",
                 "id": 31201,
                 "type": {
                   "dateCreated": 1067272496850,
                   "name": "Employee Move",
                   "id": 2,
                   "fields": [
                     {
                       "code": "firstName",
                       "name": "First Name",
                       "id": 17
                     },
                     {
                       "code": "lastName",
                       "name": "Last Name",
                       "id": 18
                     },
                     {
                       "code": "phone",
                       "name": "Phone",
                       "id": 19
                     },
                     {
                       "code": "extension",
                       "name": "Extension",
                       "id": 20
                     },
                     {
                       "code": "costCenter",
                       "name": "Cost Center",
                       "id": 21
                     },
                     {
                       "code": "employeeId",
                       "name": "Employee ID",
                       "id": 22
                     },
                     {
                       "code": "email",
                       "name": "Email",
                       "id": 23
                     }
                   ],
                   "typeCode": "move"
                 },
                 "user": {
                   "floorWarden": false,
                   "lastName": "Admin",
                   "extension": "",
                   "color": "#8cf7a4",
                   "employeeId": "",
                   "userName": "hansolo",
                   "specialNeeds": false,
                   "dateUpdated": 1488566587390,
                   "firstName": "Han",
                   "dateCreated": 1464727067663,
                   "phone": "",
                   "name": "Han Solo",
                   "mailStop": {
                     "name": "Stop 1",
                     "id": 140
                   },
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
                   "email": "hansolo@iofficecorp.com"
                 },
                 "tasksValueMap":{  
                    "10":{  
                       "other":"Need a Bigger TV",
                       "notes":"Samsung or Sony",
                       "whiteBoard":"Yes",
                       "deskChair":"Yes",
                       "sideChair":"Yes"
                    }
                 }
               }
             ],
             "description": "Customer Service's Move Request (7/09)",
             "status": {
               "code": "sub",
               "dateCreated": 1185984126540,
               "name": "In Progress",
               "id": 10
             }
          }

## Remove a Move Request [DELETE]
+ Parameters
    + id (string) ... ID of the User
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }
        
## Archive a Move Request [POST /move/requests///{id}/archive]
+ Parameters
+ id (string) ... ID of the move request

+ Request (application/json)
                            
        {}

+ Response 200
  + Body

            {
                "date": 1582845814050,
                "requester": {
                    "costCenter1": "",
                    "lastName": "Customer28",
                    "extension": "",
                    "color": "#974B71",
                    "passwordResetAttemptsRemaining": 3,
                    "specialNeeds": false,
                    "custom20": "",
                    "custom22": "",
                    "custom21": "",
                    "custom24": "",
                    "custom23": "",
                    "dateCreated": 1465574697757,
                    "custom26": "",
                    "custom25": "",
                    "knownAs": "",
                    "custom28": "",
                    "custom27": "",
                    "custom29": "",
                    "company": "",
                    "id": 15624,
                    "costCenter2": "North America",
                    "email": "customer28@e.rainforestqa.com",
                    "floorWarden": false,
                    "comments": "",
                    "costCenter": {
                        "hexColor": "ffffcc",
                        "code": "Please do not modify/remove!",
                        "dateCreated": 1464968087173,
                        "depth": {
                            "code": "co",
                            "dateCreated": 1181403908747,
                            "level": 0,
                            "name": "Company",
                            "id": 1,
                            "category": {
                                "code": "Please do not modify/remove!",
                                "dateCreated": 1448999612493,
                                "color": {},
                                "name": "Default Category",
                                "id": 1,
                                "dateUpdated": 1465489481990
                            }
                        },
                        "color": {},
                        "name": "North America",
                        "id": 199,
                        "category": {
                            "code": "Please do not modify/remove!",
                            "dateCreated": 1448999612493,
                            "color": {},
                            "name": "Default Category",
                            "id": 1,
                            "dateUpdated": 1465489481990
                        },
                        "dateUpdated": 1464988286367
                    },
                    "mobile": "",
                    "employeeId": "7307530",
                    "userName": "customer28",
                    "room": {
                        "area": 56.0,
                        "dateCreated": 1573252658877,
                        "reservableByRules": false,
                        "reservable": false,
                        "name": "B02059F",
                        "description": "",
                        "id": 1921,
                        "type": {
                            "hexColor": "7bd081",
                            "contentFlag": 1,
                            "cost": 0.0,
                            "color": {},
                            "name": "WKST",
                            "occupiable": false,
                            "id": 1,
                            "parkingSpace": false,
                            "dateUpdated": 1677431311790,
                            "typeCode": ""
                        },
                        "floor": {
                            "area": 49395.5598,
                            "dateCreated": 1573252598693,
                            "drawingAvailable": true,
                            "interiorGross": 10001.0,
                            "name": "2",
                            "leaseArea": 0.0,
                            "id": 55,
                            "building": {
                                "code": "DO NOT REMOVE",
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
                                    "street": "901 Bagby St",
                                    "postalCode": "77002",
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
                                "name": "Move",
                                "leaseArea": 6000.0,
                                "location": {},
                                "revitLink": "https://a360.co/2IHVNN4",
                                "id": 43,
                                "dateUpdated": 1677538229843,
                                "costCenters": []
                            },
                            "dateUpdated": 1671583701540
                        },
                        "occupied": true,
                        "capacity": 1,
                        "dateUpdated": 1675154843230
                    },
                    "custom30": "",
                    "dateUpdated": 1675154844273,
                    "custom11": "",
                    "firstName": "Rainforest",
                    "custom10": "",
                    "custom13": "",
                    "custom12": "",
                    "custom15": "",
                    "phone": "",
                    "custom14": "",
                    "custom17": "",
                        "custom16": "",
                    "name": "Rainforest Customer28",
                    "custom19": "",
                    "custom18": "",
                    "mailStop": {
                        "name": "Stop 1",
                        "id": 139
                    },
                    "userType": {
                        "dateCreated": 1430925570820,
                        "name": "Employee",
                        "id": 1,
                        "dateUpdated": 1599768189727
                    }
                },
                "approved": false,
                "attachments": [],
                "comments": [],
                "dateCreated": 1582845814057,
                "center": {
                    "name": "Move Center",
                    "id": 77
                },
                "description": "JBen Test Move ",
                "additionalMoveCost": 0.00,
                "id": 203,
                "dateUpdated": 1676567772120,
                "status": {
                    "dateCreated": 1202693678817,
                    "name": "Rejected",
                    "id": 16,
                    "locked": false,
                    "dateUpdated": 1676634643937
                }
            }
                      


## Move Collection [/move/requests///{?statusId,statusCode,modifiedOrCreatedAfter}]

+ Parameters
    + statusId (optional, number, `66`) ... ID of the Move status to query from
    + statusCode (optional, string, `sub`) ... Code of the Move status to query from
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.
    + maintenanceRequestId (optional, number, `14944`) ... ID of the Maintenance to query from

+ Model (application/json)
    JSON representation of the Move Collection resource.

    + Body

            [
                         {
                           "date": 1504112404863,
                           "requester":{
                                 "floorWarden":false,
                                 "lastName":"Vader",
                                 "firstName":"Darth",
                                 "dateCreated":1464727067663,
                                 "color":"#89ffa1",
                                 "name":"Darth Vader",
                                 "id":9,
                                 "userType":{
                                    "dateCreated":1430925570820,
                                    "name":"Employee",
                                    "id":1,
                                    "fields":[
                                       {
                                          "code":"company",
                                          "name":"Company",
                                          "id":1
                                       },
                                       {
                                          "code":"jobTitle",
                                          "name":"Job Title",
                                          "id":2
                                       },
                                       {
                                          "code":"phone",
                                          "name":"Phone",
                                          "id":3
                                       },
                                       {
                                          "code":"extension",
                                          "name":"Extension",
                                          "id":4
                                       },
                                       {
                                          "code":"mobile",
                                          "name":"Mobile Phone Number",
                                          "id":6
                                       },
                                       {
                                          "code":"employeeId",
                                          "name":"Employee ID",
                                          "id":8
                                       },
                                       {
                                          "code":"floorWarden",
                                          "name":"Floor Warden",
                                          "id":12
                                       },
                                       {
                                          "code":"specialNeeds",
                                          "name":"Special Needs",
                                          "id":13
                                       },
                                       {
                                          "code":"comments",
                                          "name":"Comments",
                                          "id":14
                                       },
                                       {
                                          "code":"alternateDelivery",
                                          "name":"Alternate Delivery",
                                          "id":16
                                       },
                                       {
                                          "code":"knownAs",
                                          "name":"Known As",
                                          "id":17
                                       }
                                    ]
                                 },
                                 "userName":"lordvader",
                                 "specialNeeds":false,
                                 "email":"lordvader@deathstar.com",
                                 "dateUpdated":1488566587390
                              },
                           "approved": true,
                           "comments": [
                             {
                               "id": 92,
                               "content": "your comment here!"
                             }
                           ],
                           "dateCreated": 1469818235210,
                           "approvedBy": {
                             "floorWarden": false,
                             "lastName": "Admin",
                             "firstName": "Han",
                             "dateCreated": 1464727067663,
                             "color": "#89ffa1",
                             "name": "Han Solo",
                             "id": 9,
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
                             "userName": "Han Solo",
                             "specialNeeds": false,
                             "email": "hansolo@iofficecorp.com",
                             "dateUpdated": 1488566587390
                           },
                           "id": 16,
                           "items": [
                             {
                               "toRoom": {
                                 "dateCreated": 1465572191247,
                                 "reservable": false,
                                 "name": "49.0",
                                 "description": "",
                                 "id": 416,
                                 "floor": {
                                   "area": 23600.0167,
                                   "dateCreated": 1465572160000,
                                   "drawingAvailable": true,
                                   "name": "1",
                                   "id": 2,
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
                                       "postalCode": "",
                                       "state": {
                                         "defaultSelected": false,
                                         "code": "",
                                         "name": "Other",
                                         "id": 70
                                       }
                                     },
                                     "dateCreated": 1465572158677,
                                     "metric": false,
                                     "name": "Built",
                                     "id": 44,
                                     "dateUpdated": 1465572159707
                                   },
                                   "dateUpdated": 1465572186757
                                 },
                                 "type": {
                                   "hexColor": "33cc99",
                                   "color": {},
                                   "name": "WKST",
                                   "occupiable": true,
                                   "id": 1,
                                   "parkingSpace": false
                                 },
                                 "capacity": 1
                               },
                               "toRoomAvailable": true,
                               "name": "Han Solo",
                               "id": 31201,
                               "type": {
                                 "dateCreated": 1067272496850,
                                 "name": "Employee Move",
                                 "id": 2,
                                 "fields": [
                                   {
                                     "code": "firstName",
                                     "name": "First Name",
                                     "id": 17
                                   },
                                   {
                                     "code": "lastName",
                                     "name": "Last Name",
                                     "id": 18
                                   },
                                   {
                                     "code": "phone",
                                     "name": "Phone",
                                     "id": 19
                                   },
                                   {
                                     "code": "extension",
                                     "name": "Extension",
                                     "id": 20
                                   },
                                   {
                                     "code": "costCenter",
                                     "name": "Cost Center",
                                     "id": 21
                                   },
                                   {
                                     "code": "employeeId",
                                     "name": "Employee ID",
                                     "id": 22
                                   },
                                   {
                                     "code": "email",
                                     "name": "Email",
                                     "id": 23
                                   }
                                 ],
                                 "typeCode": "move"
                               },
                               "user": {
                                 "floorWarden": false,
                                 "lastName": "Admin",
                                 "extension": "",
                                 "color": "#8cf7a4",
                                 "employeeId": "",
                                 "userName": "hansolo",
                                 "specialNeeds": false,
                                 "dateUpdated": 1488566587390,
                                 "firstName": "Han",
                                 "dateCreated": 1464727067663,
                                 "phone": "",
                                 "name": "Han Solo",
                                 "mailStop": {
                                   "name": "Stop 1",
                                   "id": 140
                                 },
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
                                 "email": "hansolo@iofficecorp.com"
                               },
                               "tasksValueMap":{  
                                  "10":{  
                                     "other":"Need a Bigger TV",
                                     "notes":"Samsung or Sony",
                                     "whiteBoard":"Yes",
                                     "deskChair":"Yes",
                                     "sideChair":"Yes"
                                  }
                               }
                             }
                           ],
                           "description": "Customer Service's Move Request (7/09)",
                           "status": {
                             "code": "sub",
                             "dateCreated": 1185984126540,
                             "name": "In Progress",
                             "id": 10
                           }
                         },

                         ...
            ]


## List of all Move Requests [GET]

+ Response 200

    [Move Collection][]


## Create a Move Request [POST /move/requests]
+ The following attributes are required to create a Move Request: status `id` and `description`.

+ Request (application/json)

           {
             "date": 1504112404863,
             "approved": true,
             "comments": [
               {
                 "content": "your comment here!"
               }
             ],
             "description": "your description here!"
             "approvedBy": {
               "id": 9
             },
             "items": [
               {
                 "toRoom": {
                     "id": 2
                  },
                 "type": {
                   "id": 2
                 },
                 "user": {
                   "id": 9,
                   "lastName": "Admin",
                   "extension": "",
                   "employeeId": "",
                   "userName": "hansolo",
                   "specialNeeds": false,
                   "firstName": "Han",
                   "phone": "",
                   "name": "Han Solo",
                   "email": "hansolo@iofficecorp.com"
                 },
                 "tasksValueMap":{  
                    "10":{  
                       "other":"Need a Bigger TV",
                       "notes":"Samsung or Sony",
                       "whiteBoard":"Yes",
                       "deskChair":"Yes",
                       "sideChair":"Yes"
                    }
                 }
               }
             ],
             "status": {
               "id": 10
             },
		  	 "cost": {
				"id": 1
			  },
			  "additionalMoveCost": 1000
           }


+ Response 201

           {
             "date": 1504112404863,
             "requester":{
                   "floorWarden":false,
                   "lastName":"Vader",
                   "firstName":"Darth",
                   "dateCreated":1464727067663,
                   "color":"#89ffa1",
                   "name":"Darth Vader",
                   "id":9,
                   "userType":{
                      "dateCreated":1430925570820,
                      "name":"Employee",
                      "id":1,
                      "fields":[
                         {
                            "code":"company",
                            "name":"Company",
                            "id":1
                         },
                         {
                            "code":"jobTitle",
                            "name":"Job Title",
                            "id":2
                         },
                         {
                            "code":"phone",
                            "name":"Phone",
                            "id":3
                         },
                         {
                            "code":"extension",
                            "name":"Extension",
                            "id":4
                         },
                         {
                            "code":"mobile",
                            "name":"Mobile Phone Number",
                            "id":6
                         },
                         {
                            "code":"employeeId",
                            "name":"Employee ID",
                            "id":8
                         },
                         {
                            "code":"floorWarden",
                            "name":"Floor Warden",
                            "id":12
                         },
                         {
                            "code":"specialNeeds",
                            "name":"Special Needs",
                            "id":13
                         },
                         {
                            "code":"comments",
                            "name":"Comments",
                            "id":14
                         },
                         {
                            "code":"alternateDelivery",
                            "name":"Alternate Delivery",
                            "id":16
                         },
                         {
                            "code":"knownAs",
                            "name":"Known As",
                            "id":17
                         }
                      ]
                   },
                   "userName":"lordvader",
                   "specialNeeds":false,
                   "email":"lordvader@deathstar.com",
                   "dateUpdated":1488566587390
                },
             "approved": true,
             "comments": [
               {
                 "id": 97,
                 "content": "your comment here!"
               }
             ],
             "dateCreated": 1488576779346,
             "approvedBy": {
               "floorWarden": false,
               "lastName": "Admin",
               "firstName": "Han",
               "dateCreated": 1464727067663,
               "color": "#89ffa1",
               "name": "Han Solo",
               "id": 9,
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
               "userName": "hansolo",
               "specialNeeds": false,
               "email": "hansolo@iofficecorp.com",
               "dateUpdated": 1488566587390
             },
             "description": "Customer Service's Move Request (7/09)",
             "id": 34,
             "items": [
               {
                 "toRoom": {
                   "dateCreated": 1465569711690,
                   "reservable": false,
                   "name": "FP4028",
                   "description": "",
                   "id": 2,
                   "floor": {
                     "area": 29612.2818,
                     "dateCreated": 1464726639557,
                     "drawingAvailable": true,
                     "name": "0",
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
                         "city": "",
                         "street": "",
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
                       "code": "BLDG1",
                       "dateCreated": 1107466065320,
                       "metric": false,
                       "name": "Building1",
                       "id": 43
                     },
                     "dateUpdated": 1468875784277
                   },
                   "type": {
                     "hexColor": "33cc99",
                     "color": {},
                     "name": "WKST",
                     "occupiable": true,
                     "id": 1,
                     "parkingSpace": false
                   },
                   "capacity": 1,
                   "dateUpdated": 1468875790390
                 },
                 "toRoomAvailable": true,
                 "name": "Han Solo",
                 "id": 31209,
                 "type": {
                   "dateCreated": 1067272496850,
                   "name": "Employee Move",
                   "id": 2,
                   "fields": [
                     {
                       "code": "firstName",
                       "name": "First Name",
                       "id": 17
                     },
                     {
                       "code": "lastName",
                       "name": "Last Name",
                       "id": 18
                     },
                     {
                       "code": "phone",
                       "name": "Phone",
                       "id": 19
                     },
                     {
                       "code": "extension",
                       "name": "Extension",
                       "id": 20
                     },
                     {
                       "code": "costCenter",
                       "name": "Cost Center",
                       "id": 21
                     },
                     {
                       "code": "employeeId",
                       "name": "Employee ID",
                       "id": 22
                     },
                     {
                       "code": "email",
                       "name": "Email",
                       "id": 23
                     }
                   ],
                   "typeCode": "move"
                 },
                 "user": {
                   "floorWarden": false,
                   "lastName": "Admin",
                   "extension": "",
                   "color": "#ffbcc6",
                   "employeeId": "",
                   "userName": "hansolo",
                   "specialNeeds": false,
                   "dateUpdated": 1488566587390,
                   "firstName": "Han",
                   "dateCreated": 1464727067663,
                   "phone": "",
                   "name": "Han Solo",
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
                   "email": "hansolo@iofficecorp.com"
                 },
                 "tasksValueMap": {  
                    "10": {  
                       "other":"Need a Bigger TV",
                       "notes":"Samsung or Sony",
                       "whiteBoard":"Yes",
                       "deskChair":"Yes",
                       "sideChair":"Yes"
                    }
                 }
               }
             ],
             "dateUpdated": 1488576779926,
             "status": {
               "code": "sub",
               "dateCreated": 1185984126540,
               "name": "In Progress",
               "id": 10
             }
           }
           
## Move Request Items [/move/requests/items///{id}]
A single move request item object.

+ Parameters
    + id (string) ... ID of the Move Request Item
    
+ Model (application/json)
    JSON representation of the Move Item Resource
    
    + Body
    
          {
            "toRoom": {
              "dateCreated": 1465572191247,
              "reservable": false,
              "name": "49.0",
              "description": "",
              "id": 416,
              "floor": {
                "area": 23600.0167,
                "dateCreated": 1465572160000,
                "drawingAvailable": true,
                "name": "1",
                "id": 2,
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
                    "postalCode": "",
                    "state": {
                      "defaultSelected": false,
                      "code": "",
                      "name": "Other",
                      "id": 70
                    }
                  },
                  "dateCreated": 1465572158677,
                  "metric": false,
                  "name": "Built",
                  "id": 44,
                  "dateUpdated": 1465572159707
                },
                "dateUpdated": 1465572186757
              },
              "type": {
                "hexColor": "33cc99",
                "color": {},
                "name": "WKST",
                "occupiable": true,
                "id": 1,
                "parkingSpace": false
              },
              "capacity": 1
            },
            "toRoomAvailable": true,
            "name": "Han Solo",
            "id": 31201,
            "type": {
              "dateCreated": 1067272496850,
              "name": "Employee Move",
              "id": 2,
              "fields": [
                {
                  "code": "firstName",
                  "name": "First Name",
                  "id": 17
                },
                {
                  "code": "lastName",
                  "name": "Last Name",
                  "id": 18
                },
                {
                  "code": "phone",
                  "name": "Phone",
                  "id": 19
                },
                {
                  "code": "extension",
                  "name": "Extension",
                  "id": 20
                },
                {
                  "code": "costCenter",
                  "name": "Cost Center",
                  "id": 21
                },
                {
                  "code": "employeeId",
                  "name": "Employee ID",
                  "id": 22
                },
                {
                  "code": "email",
                  "name": "Email",
                  "id": 23
                }
              ],
              "typeCode": "move"
            },
            "user": {
              "floorWarden": false,
              "lastName": "Admin",
              "extension": "",
              "color": "#8cf7a4",
              "employeeId": "",
              "userName": "hansolo",
              "specialNeeds": false,
              "dateUpdated": 1488566587390,
              "firstName": "Han",
              "dateCreated": 1464727067663,
              "phone": "",
              "name": "Han Solo",
              "mailStop": {
                "name": "Stop 1",
                "id": 140
              },
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
              "email": "hansolo@iofficecorp.com"
            },
            "tasksValueMap": {  
              "10": {  
                "other":"Need a Bigger TV",
                "notes":"Samsung or Sony",
                "whiteBoard":"Yes",
                "deskChair":"Yes",
                "sideChair":"Yes"
              }
            }
          }
    
## Retrieve a single Move Request Item [GET]
+ Response 200
    
    [Move Request Items][]
    
## Edit a Move Request Item [PUT /move/requests/items///{id}]

To update a Move Request Item send JSON with the Move Request Item's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Move Request Item

+ Request (application/json)

         {
           {
             "id": 23,
             "name": 'New Name',
           }
         }

+ Response 200

## Remove a Move Request Item [DELETE]
+ Parameters
    + id (string) ... ID of the Move Request Item
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }
        	
## Create a Move Request Item [POST /move/requests/items/]
The following attributes are required to create a Move Request Item: request `id`, type `id`, 

One or more of the following attributes may also be required depending on the request item type: user `id`, asset `id`, toRoom `id`.

+ Request (application/json)

       {
         "request": {
             "id": 1
         },
         "toRoom": {
             "id": 2
          },
         "type": {
           "id": 2
         },
         "user": {
           "id": 9,
           "lastName": "Admin",
           "extension": "",
           "employeeId": "",
           "userName": "hansolo",
           "specialNeeds": false,
           "firstName": "Han",
           "phone": "",
           "name": "Han Solo",
           "email": "hansolo@iofficecorp.com"
         },
       }

+ Response 201

       {
         "request": {
             "id": 1
         },
         "toRoom": {
             "id": 2
         },
         "type": {
           "id": 2
         },
         "user": {
           "id": 9,
           "lastName": "Admin",
           "extension": "",
           "employeeId": "",
           "userName": "hansolo",
           "specialNeeds": false,
           "firstName": "Han",
           "phone": "",
           "name": "Han Solo",
           "email": "hansolo@iofficecorp.com"
         },
       }
       
      
## Move Item Collection [/move/requests/items///{?requestId}]

+ Parameters
    + requestId(optional, number, `210`) ... Retrieves all move request items associated with the move request specified by the parameter.
    
+ Model (application/json)
    JSON representation of the Move Item Resource
    
    + Body
        	[
               {
                  "toRoom":{
                     "dateCreated":1465572191247,
                     "reservable":false,
                     "name":"49.0",
                     "description":"",
                     "id":416,
                     "floor":{
                        "area":23600.0167,
                        "dateCreated":1465572160000,
                        "drawingAvailable":true,
                        "name":"1",
                        "id":2,
                        "building":{
                           "address":{
                              "country":{
                                 "defaultSelected":true,
                                 "subdivisionCategoryName":"state",
                                 "alpha2Code":"US",
                                 "isoCode":"US",
                                 "name":"United States of America (the)",
                                 "id":223
                              },
                              "city":"Houston",
                              "postalCode":"",
                              "state":{
                                 "defaultSelected":false,
                                 "code":"",
                                 "name":"Other",
                                 "id":70
                              }
                           },
                           "dateCreated":1465572158677,
                           "metric":false,
                           "name":"Built",
                           "id":44,
                           "dateUpdated":1465572159707
                        },
                        "dateUpdated":1465572186757
                     },
                     "type":{
                        "hexColor":"33cc99",
                        "color":{
                           
                        },
                        "name":"WKST",
                        "occupiable":true,
                        "id":1,
                        "parkingSpace":false
                     },
                     "capacity":1
                  },
                  "toRoomAvailable":true,
                  "name":"Han Solo",
                  "id":31201,
                  "type":{
                     "dateCreated":1067272496850,
                     "name":"Employee Move",
                     "id":2,
                     "fields":[
                        {
                           "code":"firstName",
                           "name":"First Name",
                           "id":17
                        },
                        {
                           "code":"lastName",
                           "name":"Last Name",
                           "id":18
                        },
                        {
                           "code":"phone",
                           "name":"Phone",
                           "id":19
                        },
                        {
                           "code":"extension",
                           "name":"Extension",
                           "id":20
                        },
                        {
                           "code":"costCenter",
                           "name":"Cost Center",
                           "id":21
                        },
                        {
                           "code":"employeeId",
                           "name":"Employee ID",
                           "id":22
                        },
                        {
                           "code":"email",
                           "name":"Email",
                           "id":23
                        }
                     ],
                     "typeCode":"move"
                  },
                  "user":{
                     "floorWarden":false,
                     "lastName":"Admin",
                     "extension":"",
                     "color":"#8cf7a4",
                     "employeeId":"",
                     "userName":"hansolo",
                     "specialNeeds":false,
                     "dateUpdated":1488566587390,
                     "firstName":"Han",
                     "dateCreated":1464727067663,
                     "phone":"",
                     "name":"Han Solo",
                     "mailStop":{
                        "name":"Stop 1",
                        "id":140
                     },
                     "userType":{
                        "dateCreated":1430925570820,
                        "name":"Employee",
                        "id":1,
                        "fields":[
                           {
                              "code":"company",
                              "name":"Company",
                              "id":1
                           },
                           {
                              "code":"jobTitle",
                              "name":"Job Title",
                              "id":2
                           },
                           {
                              "code":"phone",
                              "name":"Phone",
                              "id":3
                           },
                           {
                              "code":"extension",
                              "name":"Extension",
                              "id":4
                           },
                           {
                              "code":"mobile",
                              "name":"Mobile Phone Number",
                              "id":6
                           },
                           {
                              "code":"employeeId",
                              "name":"Employee ID",
                              "id":8
                           },
                           {
                              "code":"floorWarden",
                              "name":"Floor Warden",
                              "id":12
                           },
                           {
                              "code":"specialNeeds",
                              "name":"Special Needs",
                              "id":13
                           },
                           {
                              "code":"comments",
                              "name":"Comments",
                              "id":14
                           },
                           {
                              "code":"alternateDelivery",
                              "name":"Alternate Delivery",
                              "id":16
                           },
                           {
                              "code":"knownAs",
                              "name":"Known As",
                              "id":17
                           }
                        ]
                     },
                     "email":"hansolo@iofficecorp.com"
                  },
                  "tasksValueMap":{
                     "10":{
                        "other":"Need a Bigger TV",
                        "notes":"Samsung or Sony",
                        "whiteBoard":"Yes",
                        "deskChair":"Yes",
                        "sideChair":"Yes"
                     }
                  }
               },
               ...
            ]

## List of all Move Request Items [GET]

+ Response 200

	[Move Item Collection][]
	

       
## Archived Move Requests [/move/requests/archived///{id}]
A single archived move request

+ Parameters
	+ id (String) ... ID of the archived move request
+ Model (application/json)
	JSON representation of the Archived Move Resource
	
	+ Body
		
		{
            "date": 1593748206540,
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
                "mailStop": {
                    "name": "Stop 1",
                    "id": 139
                },
                "userType": {
                    "name": "New Type",
                    "id": 2,
                    "dateUpdated": 1576816332180
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
                "address": "",
                "comments": "",
                "mobile": "",
                "employeeId": "",
                "userName": "ioffice",
                "room": {
                    "area": 0.0,
                    "longDescription": "",
                    "reservable": true,
                    "description": "testing 1234",
                    "type": {
                        "hexColor": "03fff7",
                        "contentFlag": 1,
                        "cost": 0.0,
                        "color": {},
                        "name": "OFFICE",
                        "occupiable": false,
                        "id": 100,
                        "parkingSpace": false,
                        "dateUpdated": 1585874142457,
                        "typeCode": ""
                    },
                    "capacity": 5,
                    "dateUpdated": 1595325880387,
                    "dateCreated": 1580232955383,
                    "googleData": {
                        "googleCalResourceId": "MQUeSi6xcKSkkCvlbn65_aOFBjs",
                        "googleCalAddress": "testcalendar.net_1887u0ufemsraieomea5r8p2bdf3m@resource.calendar.google.com"
                    },
                    "name": "NotNewRoomr",
                    "remoteInfo": "",
                    "id": 13,
                    "floor": {
                        "area": 3808.0,
                        "dateCreated": 1563467606570,
                        "drawingAvailable": false,
                        "name": "Conference Room",
                        "id": 2,
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
                                "street": "1210 W Clay St",
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
                            "dateCreated": 1563380090677,
                            "metric": true,
                            "name": "Building 1",
                            "location": {},
                            "id": 44,
                            "revitLink": "",
                            "costCenters": [],
                            "dateUpdated": 1591819645633
                        },
                        "dateUpdated": 1591989677357
                    }
                },
                "dateUpdated": 1563379891283,
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
            "lastUpdatedBy": {
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
                "mailStop": {
                    "name": "Stop 1",
                    "id": 139
                },
                "userType": {
                    "name": "New Type",
                    "id": 2,
                    "dateUpdated": 1576816332180
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
                "address": "",
                "comments": "",
                "mobile": "",
                "employeeId": "",
                "userName": "ioffice",
                "room": {
                    "area": 0.0,
                    "longDescription": "",
                    "reservable": true,
                    "description": "testing 1234",
                    "type": {
                        "hexColor": "03fff7",
                        "contentFlag": 1,
                        "cost": 0.0,
                        "color": {},
                        "name": "OFFICE",
                        "occupiable": false,
                        "id": 100,
                        "parkingSpace": false,
                        "dateUpdated": 1585874142457,
                        "typeCode": ""
                    },
                    "capacity": 5,
                    "dateUpdated": 1595325880387,
                    "dateCreated": 1580232955383,
                    "googleData": {
                        "googleCalResourceId": "MQUeSi6xcKSkkCvlbn65_aOFBjs",
                        "googleCalAddress": "testcalendar.net_1887u0ufemsraieomea5r8p2bdf3m@resource.calendar.google.com"
                    },
                    "name": "NotNewRoomr",
                    "remoteInfo": "",
                    "id": 13,
                    "floor": {
                        "area": 3808.0,
                        "dateCreated": 1563467606570,
                        "drawingAvailable": false,
                        "name": "Conference Room",
                        "id": 2,
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
                                "street": "1210 W Clay St",
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
                            "dateCreated": 1563380090677,
                            "metric": true,
                            "name": "Building 1",
                            "location": {},
                            "id": 44,
                            "revitLink": "",
                            "costCenters": [],
                            "dateUpdated": 1591819645633
                        },
                        "dateUpdated": 1591989677357
                    }
                },
                "dateUpdated": 1563379891283,
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
            "comments": [],
            "center": {
                "name": "Move Center",
                "id": 75
            },
            "description": "Customer Service's Move Request (7/02)",
            "completed": false,
            "enteredBy": {
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
                "mailStop": {
                    "name": "Stop 1",
                    "id": 139
                },
                "userType": {
                    "name": "New Type",
                    "id": 2,
                    "dateUpdated": 1576816332180
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
                "address": "",
                "comments": "",
                "mobile": "",
                "employeeId": "",
                "userName": "ioffice",
                "room": {
                    "area": 0.0,
                    "longDescription": "",
                    "reservable": true,
                    "description": "testing 1234",
                    "type": {
                        "hexColor": "03fff7",
                        "contentFlag": 1,
                        "cost": 0.0,
                        "color": {},
                        "name": "OFFICE",
                        "occupiable": false,
                        "id": 100,
                        "parkingSpace": false,
                        "dateUpdated": 1585874142457,
                        "typeCode": ""
                    },
                    "capacity": 5,
                    "dateUpdated": 1595325880387,
                    "dateCreated": 1580232955383,
                    "googleData": {
                        "googleCalResourceId": "MQUeSi6xcKSkkCvlbn65_aOFBjs",
                        "googleCalAddress": "testcalendar.net_1887u0ufemsraieomea5r8p2bdf3m@resource.calendar.google.com"
                    },
                    "name": "NotNewRoomr",
                    "remoteInfo": "",
                    "id": 13,
                    "floor": {
                        "area": 3808.0,
                        "dateCreated": 1563467606570,
                        "drawingAvailable": false,
                        "name": "Conference Room",
                        "id": 2,
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
                                "street": "1210 W Clay St",
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
                            "dateCreated": 1563380090677,
                            "metric": true,
                            "name": "Building 1",
                            "location": {},
                            "id": 44,
                            "revitLink": "",
                            "costCenters": [],
                            "dateUpdated": 1591819645633
                        },
                        "dateUpdated": 1591989677357
                    }
                },
                "dateUpdated": 1563379891283,
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
            "dateUpdated": 1593748316627,
            "approved": false,
            "dateCreated": 1593748206540,
            "id": 209,
            "status": {
                "code": "sub",
                "dateCreated": 1185984126540,
                "name": "In Progress",
                "id": 10,
                "locked": true
            }
        }
	

## Retrieve a single Archived Request [GET]

+ Response 200

	[Archived Move Requests][]
	

## Archived Move Collection [/move/requests/archived///{?modifiedOrCreatedAfter}]

+ Parameters
	+ modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified/created items in the collection.

+ Model (application/json)
	
	JSON representation of the archived move collection resource
	
	+ Body
		
		[
				   {
					  "date":1593748206540,
					  "requester":{
						 "costCenter1":"",
						 "assistantName":"",
						 "jobTitle":"",
						 "postalCode":"",
						 "custom02":"",
						 "custom01":"",
						 "custom04":"",
						 "custom03":"",
						 "custom06":"",
						 "knownAs":"",
						 "custom05":"",
						 "custom08":"",
						 "custom07":"",
						 "custom09":"",
						 "id":1,
						 "state":"",
						 "fax":"",
						 "costCenter2":"",
						 "floorWarden":false,
						 "custom30":"",
						 "firstName":"Customer",
						 "phone":"",
						 "name":"Customer Service",
						 "mailStop":{
							"name":"Stop 1",
							"id":139
						 },
						 "userType":{
							"name":"New Type",
							"id":2,
							"dateUpdated":1576816332180
						 },
						 "lastName":"Service",
						 "extension":"",
						 "color":"#694A9F",
						 "city":"",
						 "specialNeeds":false,
						 "custom20":"",
						 "custom22":"",
						 "custom21":"",
						 "custom24":"",
						 "custom23":"",
						 "dateCreated":1099859525000,
						 "custom26":"",
						 "custom25":"",
						 "custom28":"",
						 "custom27":"",
						 "custom29":"",
						 "company":"",
						 "department":"",
						 "address":"",
						 "comments":"",
						 "mobile":"",
						 "employeeId":"",
						 "userName":"ioffice",
						 "room":{
							"area":0.0,
							"longDescription":"",
							"reservable":true,
							"description":"testing 1234",
							"type":{
							   "hexColor":"03fff7",
							   "contentFlag":1,
							   "cost":0.0,
							   "color":{
				
							   },
							   "name":"OFFICE",
							   "occupiable":false,
							   "id":100,
							   "parkingSpace":false,
							   "dateUpdated":1585874142457,
							   "typeCode":""
							},
							"capacity":5,
							"dateUpdated":1595325880387,
							"dateCreated":1580232955383,
							"googleData":{
							   "googleCalResourceId":"MQUeSi6xcKSkkCvlbn65_aOFBjs",
							   "googleCalAddress":"testcalendar.net_1887u0ufemsraieomea5r8p2bdf3m@resource.calendar.google.com"
							},
							"name":"NotNewRoomr",
							"remoteInfo":"",
							"id":13,
							"floor":{
							   "area":3808.0,
							   "dateCreated":1563467606570,
							   "drawingAvailable":false,
							   "name":"Conference Room",
							   "id":2,
							   "building":{
								  "address":{
									 "country":{
										"defaultSelected":true,
										"subdivisionCategoryName":"state",
										"alpha2Code":"US",
										"isoCode":"US",
										"name":"United States of America (the)",
										"id":223
									 },
									 "city":"Houston",
									 "street":"1210 W Clay St",
									 "postalCode":"",
									 "state":{
										"country":{
										   "defaultSelected":true,
										   "subdivisionCategoryName":"state",
										   "alpha2Code":"US",
										   "isoCode":"US",
										   "name":"United States of America (the)",
										   "id":223
										},
										"defaultSelected":false,
										"code":"TX",
										"name":"Texas",
										"id":61,
										"categoryName":"state"
									 }
								  },
								  "dateCreated":1563380090677,
								  "metric":true,
								  "name":"Building 1",
								  "location":{
				
								  },
								  "id":44,
								  "revitLink":"",
								  "costCenters":[
				
								  ],
								  "dateUpdated":1591819645633
							   },
							   "dateUpdated":1591989677357
							}
						 },
						 "dateUpdated":1563379891283,
						 "custom11":"",
						 "custom10":"",
						 "custom13":"",
						 "custom12":"",
						 "custom15":"",
						 "custom14":"",
						 "custom17":"",
						 "custom16":"",
						 "custom19":"",
						 "custom18":"",
						 "middleName":""
					  },
					  "lastUpdatedBy":{
						 "costCenter1":"",
						 "assistantName":"",
						 "jobTitle":"",
						 "postalCode":"",
						 "custom02":"",
						 "custom01":"",
						 "custom04":"",
						 "custom03":"",
						 "custom06":"",
						 "knownAs":"",
						 "custom05":"",
						 "custom08":"",
						 "custom07":"",
						 "custom09":"",
						 "id":1,
						 "state":"",
						 "fax":"",
						 "costCenter2":"",
						 "floorWarden":false,
						 "custom30":"",
						 "firstName":"Customer",
						 "phone":"",
						 "name":"Customer Service",
						 "mailStop":{
							"name":"Stop 1",
							"id":139
						 },
						 "userType":{
							"name":"New Type",
							"id":2,
							"dateUpdated":1576816332180
						 },
						 "lastName":"Service",
						 "extension":"",
						 "color":"#694A9F",
						 "city":"",
						 "specialNeeds":false,
						 "custom20":"",
						 "custom22":"",
						 "custom21":"",
						 "custom24":"",
						 "custom23":"",
						 "dateCreated":1099859525000,
						 "custom26":"",
						 "custom25":"",
						 "custom28":"",
						 "custom27":"",
						 "custom29":"",
						 "company":"",
						 "department":"",
						 "address":"",
						 "comments":"",
						 "mobile":"",
						 "employeeId":"",
						 "userName":"ioffice",
						 "room":{
							"area":0.0,
							"longDescription":"",
							"reservable":true,
							"description":"testing 1234",
							"type":{
							   "hexColor":"03fff7",
							   "contentFlag":1,
							   "cost":0.0,
							   "color":{
				
							   },
							   "name":"OFFICE",
							   "occupiable":false,
							   "id":100,
							   "parkingSpace":false,
							   "dateUpdated":1585874142457,
							   "typeCode":""
							},
							"capacity":5,
							"dateUpdated":1595325880387,
							"dateCreated":1580232955383,
							"googleData":{
							   "googleCalResourceId":"MQUeSi6xcKSkkCvlbn65_aOFBjs",
							   "googleCalAddress":"testcalendar.net_1887u0ufemsraieomea5r8p2bdf3m@resource.calendar.google.com"
							},
							"name":"NotNewRoomr",
							"remoteInfo":"",
							"id":13,
							"floor":{
							   "area":3808.0,
							   "dateCreated":1563467606570,
							   "drawingAvailable":false,
							   "name":"Conference Room",
							   "id":2,
							   "building":{
								  "address":{
									 "country":{
										"defaultSelected":true,
										"subdivisionCategoryName":"state",
										"alpha2Code":"US",
										"isoCode":"US",
										"name":"United States of America (the)",
										"id":223
									 },
									 "city":"Houston",
									 "street":"1210 W Clay St",
									 "postalCode":"",
									 "state":{
										"country":{
										   "defaultSelected":true,
										   "subdivisionCategoryName":"state",
										   "alpha2Code":"US",
										   "isoCode":"US",
										   "name":"United States of America (the)",
										   "id":223
										},
										"defaultSelected":false,
										"code":"TX",
										"name":"Texas",
										"id":61,
										"categoryName":"state"
									 }
								  },
								  "dateCreated":1563380090677,
								  "metric":true,
								  "name":"Building 1",
								  "location":{
				
								  },
								  "id":44,
								  "revitLink":"",
								  "costCenters":[
				
								  ],
								  "dateUpdated":1591819645633
							   },
							   "dateUpdated":1591989677357
							}
						 },
						 "dateUpdated":1563379891283,
						 "custom11":"",
						 "custom10":"",
						 "custom13":"",
						 "custom12":"",
						 "custom15":"",
						 "custom14":"",
						 "custom17":"",
						 "custom16":"",
						 "custom19":"",
						 "custom18":"",
						 "middleName":""
					  },
					  "comments":[
				
					  ],
					  "center":{
						 "name":"Move Center",
						 "id":75
					  },
					  "description":"Customer Service's Move Request (7/02)",
					  "completed":false,
					  "enteredBy":{
						 "costCenter1":"",
						 "assistantName":"",
						 "jobTitle":"",
						 "postalCode":"",
						 "custom02":"",
						 "custom01":"",
						 "custom04":"",
						 "custom03":"",
						 "custom06":"",
						 "knownAs":"",
						 "custom05":"",
						 "custom08":"",
						 "custom07":"",
						 "custom09":"",
						 "id":1,
						 "state":"",
						 "fax":"",
						 "costCenter2":"",
						 "floorWarden":false,
						 "custom30":"",
						 "firstName":"Customer",
						 "phone":"",
						 "name":"Customer Service",
						 "mailStop":{
							"name":"Stop 1",
							"id":139
						 },
						 "userType":{
							"name":"New Type",
							"id":2,
							"dateUpdated":1576816332180
						 },
						 "lastName":"Service",
						 "extension":"",
						 "color":"#694A9F",
						 "city":"",
						 "specialNeeds":false,
						 "custom20":"",
						 "custom22":"",
						 "custom21":"",
						 "custom24":"",
						 "custom23":"",
						 "dateCreated":1099859525000,
						 "custom26":"",
						 "custom25":"",
						 "custom28":"",
						 "custom27":"",
						 "custom29":"",
						 "company":"",
						 "department":"",
						 "address":"",
						 "comments":"",
						 "mobile":"",
						 "employeeId":"",
						 "userName":"ioffice",
						 "room":{
							"area":0.0,
							"longDescription":"",
							"reservable":true,
							"description":"testing 1234",
							"type":{
							   "hexColor":"03fff7",
							   "contentFlag":1,
							   "cost":0.0,
							   "color":{
				
							   },
							   "name":"OFFICE",
							   "occupiable":false,
							   "id":100,
							   "parkingSpace":false,
							   "dateUpdated":1585874142457,
							   "typeCode":""
							},
							"capacity":5,
							"dateUpdated":1595325880387,
							"dateCreated":1580232955383,
							"googleData":{
							   "googleCalResourceId":"MQUeSi6xcKSkkCvlbn65_aOFBjs",
							   "googleCalAddress":"testcalendar.net_1887u0ufemsraieomea5r8p2bdf3m@resource.calendar.google.com"
							},
							"name":"NotNewRoomr",
							"remoteInfo":"",
							"id":13,
							"floor":{
							   "area":3808.0,
							   "dateCreated":1563467606570,
							   "drawingAvailable":false,
							   "name":"Conference Room",
							   "id":2,
							   "building":{
								  "address":{
									 "country":{
										"defaultSelected":true,
										"subdivisionCategoryName":"state",
										"alpha2Code":"US",
										"isoCode":"US",
										"name":"United States of America (the)",
										"id":223
									 },
									 "city":"Houston",
									 "street":"1210 W Clay St",
									 "postalCode":"",
									 "state":{
										"country":{
										   "defaultSelected":true,
										   "subdivisionCategoryName":"state",
										   "alpha2Code":"US",
										   "isoCode":"US",
										   "name":"United States of America (the)",
										   "id":223
										},
										"defaultSelected":false,
										"code":"TX",
										"name":"Texas",
										"id":61,
										"categoryName":"state"
									 }
								  },
								  "dateCreated":1563380090677,
								  "metric":true,
								  "name":"Building 1",
								  "location":{
				
								  },
								  "id":44,
								  "revitLink":"",
								  "costCenters":[
				
								  ],
								  "dateUpdated":1591819645633
							   },
							   "dateUpdated":1591989677357
							}
						 },
						 "dateUpdated":1563379891283,
						 "custom11":"",
						 "custom10":"",
						 "custom13":"",
						 "custom12":"",
						 "custom15":"",
						 "custom14":"",
						 "custom17":"",
						 "custom16":"",
						 "custom19":"",
						 "custom18":"",
						 "middleName":""
					  },
					  "dateUpdated":1593748316627,
					  "approved":false,
					  "dateCreated":1593748206540,
					  "id":209,
					  "status":{
						 "code":"sub",
						 "dateCreated":1185984126540,
						 "name":"In Progress",
						 "id":10,
						 "locked":true
					  }
				   },
				   
				   ...
        ]
        
## List of all Archived Move Requests [GET]

+ Response 200

	[Archived Move Collection][]
	

## Archived Move Request Items [/move/requests/items/archived///{id}]
A single move request item object.

+ Parameters
	+ id (string) ... ID of the Archived Move Request Item
	
+ Model (application/json)
	JSON representation of the Archived Move Item Resource
	
	+ Body 
		
		{
           "itemType":"USER",
           "toRoom":{
              "area":400.0,
              "longDescription":"",
              "dateCreated":1563381159400,
              "reservable":false,
              "name":"test room",
              "description":"",
              "id":1,
              "type":{
                 "hexColor":"ff3366",
                 "contentFlag":3,
                 "cost":0.0,
                 "color":{
        
                 },
                 "name":"MAIL RM",
                 "occupiable":true,
                 "id":105,
                 "parkingSpace":false,
                 "dateUpdated":1583291717220,
                 "typeCode":""
              },
              "floor":{
                 "area":5000.0,
                 "dateCreated":1563381159233,
                 "drawingAvailable":false,
                 "name":"Floor 1",
                 "id":1,
                 "building":{
                    "address":{
                       "country":{
                          "defaultSelected":true,
                          "subdivisionCategoryName":"state",
                          "alpha2Code":"US",
                          "isoCode":"US",
                          "name":"United States of America (the)",
                          "id":223
                       },
                       "city":"Houston",
                       "street":"1210 W Clay St",
                       "postalCode":"",
                       "state":{
                          "country":{
                             "defaultSelected":true,
                             "subdivisionCategoryName":"state",
                             "alpha2Code":"US",
                             "isoCode":"US",
                             "name":"United States of America (the)",
                             "id":223
                          },
                          "defaultSelected":false,
                          "code":"TX",
                          "name":"Texas",
                          "id":61,
                          "categoryName":"state"
                       }
                    },
                    "dateCreated":1563380090677,
                    "metric":true,
                    "name":"Building 1",
                    "location":{
        
                    },
                    "id":44,
                    "revitLink":"",
                    "costCenters":[
        
                    ],
                    "dateUpdated":1591819645633
                 },
                 "dateUpdated":1584634081437
              },
              "capacity":10,
              "dateUpdated":1584634081683
           },
           "name":"Juan Delgado2",
           "fromRoom":{
              "area":0.0,
              "longDescription":"",
              "reservable":true,
              "description":"testing 1234",
              "type":{
                 "hexColor":"03fff7",
                 "contentFlag":1,
                 "cost":0.0,
                 "color":{
        
                 },
                 "name":"OFFICE",
                 "occupiable":false,
                 "id":100,
                 "parkingSpace":false,
                 "dateUpdated":1585874142457,
                 "typeCode":""
              },
              "capacity":5,
              "dateUpdated":1595325880387,
              "dateCreated":1580232955383,
              "googleData":{
                 "googleCalResourceId":"MQUeSi6xcKSkkCvlbn65_aOFBjs",
                 "googleCalAddress":"testcalendar.net_1887u0ufemsraieomea5r8p2bdf3m@resource.calendar.google.com"
              },
              "name":"NotNewRoomr",
              "remoteInfo":"",
              "id":13,
              "floor":{
                 "area":3808.0,
                 "dateCreated":1563467606570,
                 "drawingAvailable":false,
                 "name":"Conference Room",
                 "id":2,
                 "building":{
                    "address":{
                       "country":{
                          "defaultSelected":true,
                          "subdivisionCategoryName":"state",
                          "alpha2Code":"US",
                          "isoCode":"US",
                          "name":"United States of America (the)",
                          "id":223
                       },
                       "city":"Houston",
                       "street":"1210 W Clay St",
                       "postalCode":"",
                       "state":{
                          "country":{
                             "defaultSelected":true,
                             "subdivisionCategoryName":"state",
                             "alpha2Code":"US",
                             "isoCode":"US",
                             "name":"United States of America (the)",
                             "id":223
                          },
                          "defaultSelected":false,
                          "code":"TX",
                          "name":"Texas",
                          "id":61,
                          "categoryName":"state"
                       }
                    },
                    "dateCreated":1563380090677,
                    "metric":true,
                    "name":"Building 1",
                    "location":{
        
                    },
                    "id":44,
                    "revitLink":"",
                    "costCenters":[
        
                    ],
                    "dateUpdated":1591819645633
                 },
                 "dateUpdated":1591989677357
              }
           },
           "id":90783,
           "type":{
              "dateCreated":1067272496850,
              "name":"Employee Move",
              "id":2,
              "fields":[
                 {
                    "code":"firstName",
                    "name":"First Name",
                    "id":17
                 },
                 {
                    "code":"lastName",
                    "name":"Last Name",
                    "id":18
                 },
                 {
                    "code":"phone",
                    "name":"Phone",
                    "id":19
                 },
                 {
                    "code":"extension",
                    "name":"Extension",
                    "id":20
                 },
                 {
                    "code":"costCenter",
                    "name":"Cost Center",
                    "id":21
                 },
                 {
                    "code":"employeeId",
                    "name":"Employee ID",
                    "id":22
                 },
                 {
                    "code":"email",
                    "name":"Email",
                    "id":23
                 },
                 {
                    "code":"userName",
                    "name":"Username",
                    "id":34
                 }
              ],
              "dateUpdated":1593107218917,
              "typeCode":"move"
           },
           "user":{
              "floorWarden":false,
              "costCenter1":"Category1",
              "lastName":"Delgado2",
              "color":"#F9ECEA",
              "costCenter":{
                 "hexColor":"6987f5",
                 "code":"DEP1",
                 "dateCreated":1564801237447,
                 "depth":{
                    "code":"dp",
                    "dateCreated":1181403915183,
                    "level":1,
                    "name":"Department",
                    "id":2,
                    "category":{
                       "categoryType":[
                          {
                             "name":"user",
                             "id":1
                          },
                          {
                             "name":"room",
                             "id":2
                          }
                       ],
                       "code":"cost-center",
                       "dateCreated":1448999609433,
                       "color":{
        
                       },
                       "name":"Cost Center",
                       "id":1
                    }
                 },
                 "color":{
        
                 },
                 "name":"Department 1",
                 "id":5,
                 "category":{
                    "categoryType":[
                       {
                          "name":"user",
                          "id":1
                       },
                       {
                          "name":"room",
                          "id":2
                       }
                    ],
                    "code":"cost-center",
                    "dateCreated":1448999609433,
                    "color":{
        
                    },
                    "name":"Cost Center",
                    "id":1
                 },
                 "costCenterParent":{
                    "hexColor":"403ddb",
                    "code":"CAT1",
                    "dateCreated":1564800251707,
                    "depth":{
                       "code":"co",
                       "dateCreated":1181403908747,
                       "level":0,
                       "name":"Company",
                       "id":1,
                       "category":{
                          "categoryType":[
                             {
                                "name":"user",
                                "id":1
                             },
                             {
                                "name":"room",
                                "id":2
                             }
                          ],
                          "code":"cost-center",
                          "dateCreated":1448999609433,
                          "color":{
        
                          },
                          "name":"Cost Center",
                          "id":1
                       }
                    },
                    "color":{
        
                    },
                    "name":"Category1",
                    "id":1,
                    "category":{
                       "categoryType":[
                          {
                             "name":"user",
                             "id":1
                          },
                          {
                             "name":"room",
                             "id":2
                          }
                       ],
                       "code":"cost-center",
                       "dateCreated":1448999609433,
                       "color":{
        
                       },
                       "name":"Cost Center",
                       "id":1
                    },
                    "dateUpdated":1564782304360
                 }
              },
              "userName":"jrdelgado",
              "specialNeeds":false,
              "room":{
                 "area":0.0,
                 "longDescription":"",
                 "reservable":true,
                 "description":"testing 1234",
                 "type":{
                    "hexColor":"03fff7",
                    "contentFlag":1,
                    "cost":0.0,
                    "color":{
        
                    },
                    "name":"OFFICE",
                    "occupiable":false,
                    "id":100,
                    "parkingSpace":false,
                    "dateUpdated":1585874142457,
                    "typeCode":""
                 },
                 "capacity":5,
                 "dateUpdated":1595325880387,
                 "dateCreated":1580232955383,
                 "googleData":{
                    "googleCalResourceId":"MQUeSi6xcKSkkCvlbn65_aOFBjs",
                    "googleCalAddress":"testcalendar.net_1887u0ufemsraieomea5r8p2bdf3m@resource.calendar.google.com"
                 },
                 "name":"NotNewRoomr",
                 "remoteInfo":"",
                 "id":13,
                 "floor":{
                    "area":3808.0,
                    "dateCreated":1563467606570,
                    "drawingAvailable":false,
                    "name":"Conference Room",
                    "id":2,
                    "building":{
                       "address":{
                          "country":{
                             "defaultSelected":true,
                             "subdivisionCategoryName":"state",
                             "alpha2Code":"US",
                             "isoCode":"US",
                             "name":"United States of America (the)",
                             "id":223
                          },
                          "city":"Houston",
                          "street":"1210 W Clay St",
                          "postalCode":"",
                          "state":{
                             "country":{
                                "defaultSelected":true,
                                "subdivisionCategoryName":"state",
                                "alpha2Code":"US",
                                "isoCode":"US",
                                "name":"United States of America (the)",
                                "id":223
                             },
                             "defaultSelected":false,
                             "code":"TX",
                             "name":"Texas",
                             "id":61,
                             "categoryName":"state"
                          }
                       },
                       "dateCreated":1563380090677,
                       "metric":true,
                       "name":"Building 1",
                       "location":{
        
                       },
                       "id":44,
                       "revitLink":"",
                       "costCenters":[
        
                       ],
                       "dateUpdated":1591819645633
                    },
                    "dateUpdated":1591989677357
                 }
              },
              "dateUpdated":1592584651853,
              "firstName":"Juan",
              "dateCreated":1570723843567,
              "name":"Juan Delgado2",
              "id":55,
              "mailStop":{
                 "name":"Stop 1",
                 "id":139
              },
              "userType":{
                 "name":"New Type 2",
                 "id":3
              },
              "costCenter2":"Department 1",
              "email":"jdelgado@iofficecorp.com"
           }
        }
        

## Retrieve a single Archived Move Request Item [GET]
+ Response 200
	
	[Archived Move Request Items][]
	
## Archived Move Request Item Collection [/move/requests/items/archived///{?requestId}]
+ Parameters
	+ requestId(optional, number, `209`) ... Retrieves all archived move request items associated with the archived move request specified by the parameter.
	
+ Model (application/json)
	JSON representation of the Archived Move Request Item resource.
	
	+ Body
		
		[
				   {
					  "itemType":"USER",
					  "toRoom":{
						 "area":400.0,
						 "longDescription":"",
						 "dateCreated":1563381159400,
						 "reservable":false,
						 "name":"test room",
						 "description":"",
						 "id":1,
						 "type":{
							"hexColor":"ff3366",
							"contentFlag":3,
							"cost":0.0,
							"color":{
				
							},
							"name":"MAIL RM",
							"occupiable":true,
							"id":105,
							"parkingSpace":false,
							"dateUpdated":1583291717220,
							"typeCode":""
						 },
						 "floor":{
							"area":5000.0,
							"dateCreated":1563381159233,
							"drawingAvailable":false,
							"name":"Floor 1",
							"id":1,
							"building":{
							   "address":{
								  "country":{
									 "defaultSelected":true,
									 "subdivisionCategoryName":"state",
									 "alpha2Code":"US",
									 "isoCode":"US",
									 "name":"United States of America (the)",
									 "id":223
								  },
								  "city":"Houston",
								  "street":"1210 W Clay St",
								  "postalCode":"",
								  "state":{
									 "country":{
										"defaultSelected":true,
										"subdivisionCategoryName":"state",
										"alpha2Code":"US",
										"isoCode":"US",
										"name":"United States of America (the)",
										"id":223
									 },
									 "defaultSelected":false,
									 "code":"TX",
									 "name":"Texas",
									 "id":61,
									 "categoryName":"state"
								  }
							   },
							   "dateCreated":1563380090677,
							   "metric":true,
							   "name":"Building 1",
							   "location":{
				
							   },
							   "id":44,
							   "revitLink":"",
							   "costCenters":[
				
							   ],
							   "dateUpdated":1591819645633
							},
							"dateUpdated":1584634081437
						 },
						 "capacity":10,
						 "dateUpdated":1584634081683
					  },
					  "name":"Juan Delgado2",
					  "fromRoom":{
						 "area":0.0,
						 "longDescription":"",
						 "reservable":true,
						 "description":"testing 1234",
						 "type":{
							"hexColor":"03fff7",
							"contentFlag":1,
							"cost":0.0,
							"color":{
				
							},
							"name":"OFFICE",
							"occupiable":false,
							"id":100,
							"parkingSpace":false,
							"dateUpdated":1585874142457,
							"typeCode":""
						 },
						 "capacity":5,
						 "dateUpdated":1595325880387,
						 "dateCreated":1580232955383,
						 "googleData":{
							"googleCalResourceId":"MQUeSi6xcKSkkCvlbn65_aOFBjs",
							"googleCalAddress":"testcalendar.net_1887u0ufemsraieomea5r8p2bdf3m@resource.calendar.google.com"
						 },
						 "name":"NotNewRoomr",
						 "remoteInfo":"",
						 "id":13,
						 "floor":{
							"area":3808.0,
							"dateCreated":1563467606570,
							"drawingAvailable":false,
							"name":"Conference Room",
							"id":2,
							"building":{
							   "address":{
								  "country":{
									 "defaultSelected":true,
									 "subdivisionCategoryName":"state",
									 "alpha2Code":"US",
									 "isoCode":"US",
									 "name":"United States of America (the)",
									 "id":223
								  },
								  "city":"Houston",
								  "street":"1210 W Clay St",
								  "postalCode":"",
								  "state":{
									 "country":{
										"defaultSelected":true,
										"subdivisionCategoryName":"state",
										"alpha2Code":"US",
										"isoCode":"US",
										"name":"United States of America (the)",
										"id":223
									 },
									 "defaultSelected":false,
									 "code":"TX",
									 "name":"Texas",
									 "id":61,
									 "categoryName":"state"
								  }
							   },
							   "dateCreated":1563380090677,
							   "metric":true,
							   "name":"Building 1",
							   "location":{
				
							   },
							   "id":44,
							   "revitLink":"",
							   "costCenters":[
				
							   ],
							   "dateUpdated":1591819645633
							},
							"dateUpdated":1591989677357
						 }
					  },
					  "id":90783,
					  "type":{
						 "dateCreated":1067272496850,
						 "name":"Employee Move",
						 "id":2,
						 "fields":[
							{
							   "code":"firstName",
							   "name":"First Name",
							   "id":17
							},
							{
							   "code":"lastName",
							   "name":"Last Name",
							   "id":18
							},
							{
							   "code":"phone",
							   "name":"Phone",
							   "id":19
							},
							{
							   "code":"extension",
							   "name":"Extension",
							   "id":20
							},
							{
							   "code":"costCenter",
							   "name":"Cost Center",
							   "id":21
							},
							{
							   "code":"employeeId",
							   "name":"Employee ID",
							   "id":22
							},
							{
							   "code":"email",
							   "name":"Email",
							   "id":23
							},
							{
							   "code":"userName",
							   "name":"Username",
							   "id":34
							}
						 ],
						 "dateUpdated":1593107218917,
						 "typeCode":"move"
					  },
					  "user":{
						 "floorWarden":false,
						 "costCenter1":"Category1",
						 "lastName":"Delgado2",
						 "color":"#F9ECEA",
						 "costCenter":{
							"hexColor":"6987f5",
							"code":"DEP1",
							"dateCreated":1564801237447,
							"depth":{
							   "code":"dp",
							   "dateCreated":1181403915183,
							   "level":1,
							   "name":"Department",
							   "id":2,
							   "category":{
								  "categoryType":[
									 {
										"name":"user",
										"id":1
									 },
									 {
										"name":"room",
										"id":2
									 }
								  ],
								  "code":"cost-center",
								  "dateCreated":1448999609433,
								  "color":{
				
								  },
								  "name":"Cost Center",
								  "id":1
							   }
							},
							"color":{
				
							},
							"name":"Department 1",
							"id":5,
							"category":{
							   "categoryType":[
								  {
									 "name":"user",
									 "id":1
								  },
								  {
									 "name":"room",
									 "id":2
								  }
							   ],
							   "code":"cost-center",
							   "dateCreated":1448999609433,
							   "color":{
				
							   },
							   "name":"Cost Center",
							   "id":1
							},
							"costCenterParent":{
							   "hexColor":"403ddb",
							   "code":"CAT1",
							   "dateCreated":1564800251707,
							   "depth":{
								  "code":"co",
								  "dateCreated":1181403908747,
								  "level":0,
								  "name":"Company",
								  "id":1,
								  "category":{
									 "categoryType":[
										{
										   "name":"user",
										   "id":1
										},
										{
										   "name":"room",
										   "id":2
										}
									 ],
									 "code":"cost-center",
									 "dateCreated":1448999609433,
									 "color":{
				
									 },
									 "name":"Cost Center",
									 "id":1
								  }
							   },
							   "color":{
				
							   },
							   "name":"Category1",
							   "id":1,
							   "category":{
								  "categoryType":[
									 {
										"name":"user",
										"id":1
									 },
									 {
										"name":"room",
										"id":2
									 }
								  ],
								  "code":"cost-center",
								  "dateCreated":1448999609433,
								  "color":{
				
								  },
								  "name":"Cost Center",
								  "id":1
							   },
							   "dateUpdated":1564782304360
							}
						 },
						 "userName":"jrdelgado",
						 "specialNeeds":false,
						 "room":{
							"area":0.0,
							"longDescription":"",
							"reservable":true,
							"description":"testing 1234",
							"type":{
							   "hexColor":"03fff7",
							   "contentFlag":1,
							   "cost":0.0,
							   "color":{
				
							   },
							   "name":"OFFICE",
							   "occupiable":false,
							   "id":100,
							   "parkingSpace":false,
							   "dateUpdated":1585874142457,
							   "typeCode":""
							},
							"capacity":5,
							"dateUpdated":1595325880387,
							"dateCreated":1580232955383,
							"googleData":{
							   "googleCalResourceId":"MQUeSi6xcKSkkCvlbn65_aOFBjs",
							   "googleCalAddress":"testcalendar.net_1887u0ufemsraieomea5r8p2bdf3m@resource.calendar.google.com"
							},
							"name":"NotNewRoomr",
							"remoteInfo":"",
							"id":13,
							"floor":{
							   "area":3808.0,
							   "dateCreated":1563467606570,
							   "drawingAvailable":false,
							   "name":"Conference Room",
							   "id":2,
							   "building":{
								  "address":{
									 "country":{
										"defaultSelected":true,
										"subdivisionCategoryName":"state",
										"alpha2Code":"US",
										"isoCode":"US",
										"name":"United States of America (the)",
										"id":223
									 },
									 "city":"Houston",
									 "street":"1210 W Clay St",
									 "postalCode":"",
									 "state":{
										"country":{
										   "defaultSelected":true,
										   "subdivisionCategoryName":"state",
										   "alpha2Code":"US",
										   "isoCode":"US",
										   "name":"United States of America (the)",
										   "id":223
										},
										"defaultSelected":false,
										"code":"TX",
										"name":"Texas",
										"id":61,
										"categoryName":"state"
									 }
								  },
								  "dateCreated":1563380090677,
								  "metric":true,
								  "name":"Building 1",
								  "location":{
				
								  },
								  "id":44,
								  "revitLink":"",
								  "costCenters":[
				
								  ],
								  "dateUpdated":1591819645633
							   },
							   "dateUpdated":1591989677357
							}
						 },
						 "dateUpdated":1592584651853,
						 "firstName":"Juan",
						 "dateCreated":1570723843567,
						 "name":"Juan Delgado2",
						 "id":55,
						 "mailStop":{
							"name":"Stop 1",
							"id":139
						 },
						 "userType":{
							"name":"New Type 2",
							"id":3
						 },
						 "costCenter2":"Department 1",
						 "email":"jdelgado@iofficecorp.com"
					  }
				   },
				   
				   ...
        ]
        
## List of all Archived Move Request Items [GET]
+ Response 200
	
	[Archived Move Request Item Collection][] 

## Get Move Status Ids [/move/statuses]

Get move status ids

## Retrieve Move Status Ids [GET]

+ Response 200 (application/json)

            [
             {
                code: "pen",
                dateCreated: 1195932197043,
                name: "Pending",
                id: 15
             },
             {
                code: "apr",
                dateCreated: 1195932197030,
                name: "Approved by Manager",
                id: 14
             },
             {
                code: "sub",
                dateCreated: 1185984126540,
                name: "In Progress",
                id: 10
             },
             {
                code: "0",
                dateCreated: 1202693678817,
                name: "Rejected",
                id: 16
             }
           ]
                     
## Get Move Request Type Ids [/move/requestTypes]

Get move request type ids

## Retrieve Move Request Type Ids [GET]

+ Response 200 (application/json)

            [
              {
                "dateCreated": 1067272496850,
                "name": "Employee Move",
                "id": 2,
                "fields": [
                  {
                    "code": "firstName",
                    "name": "First Name",
                    "id": 17
                  },
                  {
                    "code": "lastName",
                    "name": "Last Name",
                    "id": 18
                  },
                  {
                    "code": "phone",
                    "name": "Phone",
                    "id": 19
                  },
                  {
                    "code": "extension",
                    "name": "Extension",
                    "id": 20
                  },
                  {
                    "code": "costCenter",
                    "name": "Cost Center",
                    "id": 21
                  },
                  {
                    "code": "employeeId",
                    "name": "Employee ID",
                    "id": 22
                  },
                  {
                    "code": "email",
                    "name": "Email",
                    "id": 23
                  }
                ],
                "typeCode": "move"
              },
              {
                "dateCreated": 1064943098163,
                "name": "New Person",
                "id": 1,
                "fields": [
                  {
                    "code": "firstName",
                    "name": "First Name",
                    "id": 10
                  },
                  {
                    "code": "lastName",
                    "name": "Last Name",
                    "id": 11
                  },
                  {
                    "code": "phone",
                    "name": "Phone",
                    "id": 12
                  },
                  {
                    "code": "extension",
                    "name": "Extension",
                    "id": 13
                  },
                  {
                    "code": "costCenter",
                    "name": "Cost Center",
                    "id": 14
                  },
                  {
                    "code": "employeeId",
                    "name": "Employee ID",
                    "id": 15
                  },
                  {
                    "code": "email",
                    "name": "Email",
                    "id": 16
                  }
                ],
                "typeCode": "new"
              },
              {
                "dateCreated": 1067272669320,
                "name": "Exiting Employee",
                "id": 6,
                "fields": [
                  {
                    "code": "firstName",
                    "name": "First Name",
                    "id": 24
                  },
                  {
                    "code": "lastName",
                    "name": "Last Name",
                    "id": 25
                  },
                  {
                    "code": "phone",
                    "name": "Phone",
                    "id": 26
                  },
                  {
                    "code": "extension",
                    "name": "Extension",
                    "id": 27
                  },
                  {
                    "code": "costCenter",
                    "name": "Cost Center",
                    "id": 28
                  },
                  {
                    "code": "employeeId",
                    "name": "Employee ID",
                    "id": 29
                  },
                  {
                    "code": "email",
                    "name": "Email",
                    "id": 30
                  }
                ],
                "typeCode": "terminate"
              },
              {
                "dateCreated": 1067272647150,
                "name": "Move Office Equipment",
                "id": 5,
                "fields": [],
                "typeCode": "move"
              }
            ]
            
## Get Move Tasks [/move/tasks]

Get move tasks

## Retrieve Move Tasks [GET]

+ Response 200 (application/json)

		[  
		   {  
			  "dateCreated":1224355565670,
			  "name":"Network Services",
			  "id":1,
			  "fields":[  
				 {  
					"code":"pcType",
					"name":"PC Type",
					"id":4
				 },
				 {  
					"code":"notes",
					"name":"Notes",
					"id":5
				 },
				 {  
					"code":"printer",
					"name":"Printer?",
					"id":12
				 },
				 {  
					"code":"localQueue",
					"name":"Local Queue",
					"id":26
				 }
			  ]
		   },
		   ...   {  
			  "dateCreated":1224355565670,
			  "name":"Furniture",
			  "id":10,
			  "fields":[  
				 {  
					"code":"deskChair",
					"name":"Desk Chair?",
					"id":42
				 },
				 {  
					"code":"sideChair",
					"name":"Side Chair?",
					"id":43
				 },
				 {  
					"code":"whiteBoard",
					"name":"White Board?",
					"id":44
				 },
				 {  
					"code":"other",
					"name":"Other?",
					"id":45
				 },
				 {  
					"code":"notes",
					"name":"Notes",
					"id":46
				 }
			  ]
		   }
		]


## Stacking Diagram [/move/plans]
Stacking Diagram related resources of *iOffice API*

### Retrieve All Move Plans[GET /move/plans]

This API retrieves the details of all Move Plans from Stacking Diagram Page

+ Parameters

+ Response 200                

      [
               {
                        "depth": {
                            "code": "co",
                            "dateCreated": 1181403908747,
                            "level": 0,
                            "name": "Company",
                            "id": 1,
                            "category": {
                                "code": "Please do not modify/remove!",
                                "dateCreated": 1448999612493,
                                "color": {},
                                "name": "Default Category",
                                "id": 1,
                                "dateUpdated": 1465489481990
                            }
                        },
                        "center": {
                            "name": "Move Center",
                            "id": 77
                        },
                        "changes": [
                            {
                                "categoryItem": {
                                    "hexColor": "ffffcc",
                                    "code": "Please do not modify/remove!",
                                    "dateCreated": 1464968087173,
                                    "depth": {
                                        "code": "co",
                                        "dateCreated": 1181403908747,
                                        "level": 0,
                                        "name": "Company",
                                        "id": 1,
                                        "category": {
                                            "code": "Please do not modify/remove!",
                                            "dateCreated": 1448999612493,
                                            "color": {},
                                            "name": "Default Category",
                                            "id": 1,
                                            "dateUpdated": 1465489481990
                                         }
                                    },
                                    "color": {},
                                    "name": "North America",
                                    "id": 199,
                                    "category": {
                                        "code": "Please do not modify/remove!",
                                        "dateCreated": 1448999612493,
                                        "color": {},
                                        "name": "Default Category",
                                        "id": 1,
                                        "dateUpdated": 1465489481990
                                    },
                                    "dateUpdated": 1464988286367
                                },
                                "toFloor": {
                                    "area": 19662.6148,
                                    "meRatio": 1.75,
                                    "dateCreated": 1522704303613,
                                    "drawingAvailable": true,
                                    "interiorGross": 0.0,
                                    "name": "2",
                                    "leaseArea": 0.0,
                                    "id": 50,
                                    "building": {
                                        "meRatio": 2.5,
                                        "code": "VIEW",
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
                                            "street": "901 Bagby St",
                                            "postalCode": "77002",
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
                                        "dateCreated": 1473436298227,
                                        "metric": false,
                                        "name": "View Only",
                                        "location": {},
                                        "revitLink": "",
                                        "id": 65,
                                        "weRatio": 1.75,
                                        "dateUpdated": 1674812048407,
                                        "costCenters": []
                                    },
                                    "dateUpdated": 1600271522433
                                },
                                "fromFloor": {
                                    "area": 15338.417,
                                    "meRatio": 1.65,
                                    "dateCreated": 1473436298897,
                                    "drawingAvailable": true,
                                    "interiorGross": 0.0,
                                    "name": "1",
                                    "leaseArea": 0.0,
                                    "id": 41,
                                    "weRatio": 0.95,
                                    "building": {
                                        "meRatio": 2.5,
                                        "code": "VIEW",
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
                                            "street": "901 Bagby St",
                                            "postalCode": "77002",
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
                                        "dateCreated": 1473436298227,
                                        "metric": false,
                                        "name": "View Only",
                                        "location": {},
                                        "revitLink": "",
                                        "id": 65,
                                        "weRatio": 1.75,
                                        "dateUpdated": 1674812048407,
                                        "costCenters": []
                                    },
                                    "dateUpdated": 1600271479847
                                },
                                "id": 5
                            }
                        ],
                        "name": "Master Plan - DO NOT DELETE",
                        "id": 1,
                        "dateUpdated": 1669296962620,
                        "forecasts": [
                            {
                                "categoryItem": {
                                    "hexColor": "ffffcc",
                                    "code": "Please do not modify/remove!",
                                    "dateCreated": 1464968087173,
                                    "depth": {
                                        "code": "co",
                                        "dateCreated": 1181403908747,
                                        "level": 0,
                                        "name": "Company",
                                        "id": 1,
                                        "category": {
                                            "code": "Please do not modify/remove!",
                                            "dateCreated": 1448999612493,
                                            "color": {},
                                            "name": "Default Category",
                                            "id": 1,
                                            "dateUpdated": 1465489481990
                                        }
                                    },
                                    "color": {},
                                    "name": "North America",
                                    "id": 199,
                                    "category": {
                                        "code": "Please do not modify/remove!",
                                        "dateCreated": 1448999612493,
                                        "color": {},
                                        "name": "Default Category",
                                        "id": 1,
                                        "dateUpdated": 1465489481990
                                    },
                                    "dateUpdated": 1464988286367
                                },
                                "dateCreated": 1669296962617,
                                "percentageBased": false,
                                "categoryMemberCount": 50,
                                "id": 388,
                                "building": {
                                    "meRatio": 2.5,
                                    "code": "VIEW",
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
                                        "street": "901 Bagby St",
                                        "postalCode": "77002",
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
                                    "dateCreated": 1473436298227,
                                    "metric": false,
                                    "name": "View Only",
                                    "location": {},
                                    "revitLink": "",
                                    "id": 65,
                                    "weRatio": 1.75,
                                    "dateUpdated": 1674812048407,
                                    "costCenters": []
                                },
                                "growthValue": 5
                            }
                        ]
              } 
              ...
      ]

### Retrieve single Move Plan [GET /move/plans/{planId}]

This API retrieves the details of single Move Plan from Stacking Diagram Page

+ Parameters
    + planId (number, `70`) ... Plan ID

+ Response 200

               {
                        "depth": {
                            "code": "co",
                            "dateCreated": 1181403908747,
                            "level": 0,
                            "name": "Company",
                            "id": 1,
                            "category": {
                                "code": "Please do not modify/remove!",
                                "dateCreated": 1448999612493,
                                "color": {},
                                "name": "Default Category",
                                "id": 1,
                                "dateUpdated": 1465489481990
                            }
                        },
                        "center": {
                            "name": "Move Center",
                            "id": 77
                        },
                        "changes": [
                            {
                                "categoryItem": {
                                    "hexColor": "ffffcc",
                                    "code": "Please do not modify/remove!",
                                    "dateCreated": 1464968087173,
                                    "depth": {
                                        "code": "co",
                                        "dateCreated": 1181403908747,
                                        "level": 0,
                                        "name": "Company",
                                        "id": 1,
                                        "category": {
                                            "code": "Please do not modify/remove!",
                                            "dateCreated": 1448999612493,
                                            "color": {},
                                            "name": "Default Category",
                                            "id": 1,
                                            "dateUpdated": 1465489481990
                                         }
                                    },
                                    "color": {},
                                    "name": "North America",
                                    "id": 199,
                                    "category": {
                                        "code": "Please do not modify/remove!",
                                        "dateCreated": 1448999612493,
                                        "color": {},
                                        "name": "Default Category",
                                        "id": 1,
                                        "dateUpdated": 1465489481990
                                    },
                                    "dateUpdated": 1464988286367
                                },
                                "toFloor": {
                                    "area": 19662.6148,
                                    "meRatio": 1.75,
                                    "dateCreated": 1522704303613,
                                    "drawingAvailable": true,
                                    "interiorGross": 0.0,
                                    "name": "2",
                                    "leaseArea": 0.0,
                                    "id": 50,
                                    "building": {
                                        "meRatio": 2.5,
                                        "code": "VIEW",
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
                                            "street": "901 Bagby St",
                                            "postalCode": "77002",
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
                                        "dateCreated": 1473436298227,
                                        "metric": false,
                                        "name": "View Only",
                                        "location": {},
                                        "revitLink": "",
                                        "id": 65,
                                        "weRatio": 1.75,
                                        "dateUpdated": 1674812048407,
                                        "costCenters": []
                                    },
                                    "dateUpdated": 1600271522433
                                },
                                "fromFloor": {
                                    "area": 15338.417,
                                    "meRatio": 1.65,
                                    "dateCreated": 1473436298897,
                                    "drawingAvailable": true,
                                    "interiorGross": 0.0,
                                    "name": "1",
                                    "leaseArea": 0.0,
                                    "id": 41,
                                    "weRatio": 0.95,
                                    "building": {
                                        "meRatio": 2.5,
                                        "code": "VIEW",
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
                                            "street": "901 Bagby St",
                                            "postalCode": "77002",
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
                                        "dateCreated": 1473436298227,
                                        "metric": false,
                                        "name": "View Only",
                                        "location": {},
                                        "revitLink": "",
                                        "id": 65,
                                        "weRatio": 1.75,
                                        "dateUpdated": 1674812048407,
                                        "costCenters": []
                                    },
                                    "dateUpdated": 1600271479847
                                },
                                "id": 5
                            }
                        ],
                        "name": "Master Plan - DO NOT DELETE",
                        "id": 1,
                        "dateUpdated": 1669296962620,
                        "forecasts": [
                            {
                                "categoryItem": {
                                    "hexColor": "ffffcc",
                                    "code": "Please do not modify/remove!",
                                    "dateCreated": 1464968087173,
                                    "depth": {
                                        "code": "co",
                                        "dateCreated": 1181403908747,
                                        "level": 0,
                                        "name": "Company",
                                        "id": 1,
                                        "category": {
                                            "code": "Please do not modify/remove!",
                                            "dateCreated": 1448999612493,
                                            "color": {},
                                            "name": "Default Category",
                                            "id": 1,
                                            "dateUpdated": 1465489481990
                                        }
                                    },
                                    "color": {},
                                    "name": "North America",
                                    "id": 199,
                                    "category": {
                                        "code": "Please do not modify/remove!",
                                        "dateCreated": 1448999612493,
                                        "color": {},
                                        "name": "Default Category",
                                        "id": 1,
                                        "dateUpdated": 1465489481990
                                    },
                                    "dateUpdated": 1464988286367
                                },
                                "dateCreated": 1669296962617,
                                "percentageBased": false,
                                "categoryMemberCount": 50,
                                "id": 388,
                                "building": {
                                    "meRatio": 2.5,
                                    "code": "VIEW",
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
                                        "street": "901 Bagby St",
                                        "postalCode": "77002",
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
                                    "dateCreated": 1473436298227,
                                    "metric": false,
                                    "name": "View Only",
                                    "location": {},
                                    "revitLink": "",
                                    "id": 65,
                                    "weRatio": 1.75,
                                    "dateUpdated": 1674812048407,
                                    "costCenters": []
                                },
                                "growthValue": 5
                            }
                        ]
              }

### Create a Move Plan [POST /move/plans]
The following attributes are required to create a Move Plan

+ Request (application/json)

          {
            "name": "Rainforest SiteAdmin1234's Plan",
            "center": {
                "id": 77
            },
            "depth": {
                "id": 1
            },
            "changes": []
          }

+ Response 201
    + Body

          {
              "dateCreated": 1677060275338,
              "depth": {
                  "code": "co",
                  "dateCreated": 1181403908747,
                  "level": 0,
                  "name": "Company",
                  "id": 1,
                  "category": {
                      "code": "Please do not modify/remove!",
                      "dateCreated": 1448999612493,
                      "color": {},
                      "name": "Default Category",
                      "id": 1,
                      "dateUpdated": 1465489481990
                  }
              },
              "center": {
                  "name": "Move Center",
                  "id": 77
              },
              "changes": [],
              "name": "Rainforest SiteAdmin1234's Plan",
              "id": 288,
              "forecasts": []
          }

### Edit a Move Plan [PUT /move/plans/{id}]
The following attributes are required to edit a Move Plan

+ Parameters

    + id (string, `287`) ... ID of the Move Plan

      + Request (application/json)

                {
                    "depth": {
                        "id": 1
                    },
                    "center": {
                        "id": 77
                    },
                    "changes": [],
                    "name": "Rainforest SiteAdmin12345's Plan",
                    "dateUpdated": 1677060099650,
                    "forecasts": [
                        {
                            "categoryItem": {
                                "hexColor": "ffffcc",
                                "depth": {
                                    "code": "co",
                                    "level": 0,
                                    "name": "Company",
                                    "id": 1
                                },
                                "code": "Please do not modify/remove!",
                                "name": "North America",
                                "id": 199,
                                "parents": []
                            },
                            "categoryMemberCount": 111,
                            "percentageBased": false,
                            "id": 791,
                            "building": {
                                "code": "DO NOT REMOVE",
                                "name": "Move",
                                "id": 43
                            },
                            "growthValue": 6
                        }
                    ]
                }
             
          

+ Response 201
    + Body

            {
                "dateCreated": 1677223651954,
                "depth": {
                    "code": "co",
                    "dateCreated": 1181403908747,
                    "level": 0,
                    "name": "Company",
                    "id": 1,
                    "category": {
                        "code": "Please do not modify/remove!",
                        "dateCreated": 1448999612493,
                        "color": {},
                        "name": "Default Category",
                        "id": 1,
                        "dateUpdated": 1465489481990
                    }
                },
                "center": {
                    "name": "Move Center",
                    "id": 77
                },
                "changes": [],
                "name": "Rainforest SiteAdmin12345's Plan",
                "id": 291,
                "dateUpdated": 1677060099650,
                "forecasts": [
                    {
                        "categoryItem": {
                            "hexColor": "ffffcc",
                            "code": "Please do not modify/remove!",
                            "dateCreated": 1464968087173,
                            "depth": {
                                "code": "co",
                                "dateCreated": 1181403908747,
                                "level": 0,
                                "name": "Company",
                                "id": 1,
                                "category": {
                                    "code": "Please do not modify/remove!",
                                    "dateCreated": 1448999612493,
                                    "color": {},
                                    "name": "Default Category",
                                    "id": 1,
                                    "dateUpdated": 1465489481990
                                }
                            },
                            "color": {},
                            "name": "North America",
                            "id": 199,
                            "category": {
                                "code": "Please do not modify/remove!",
                                "dateCreated": 1448999612493,
                                "color": {},
                                "name": "Default Category",
                                "id": 1,
                                "dateUpdated": 1465489481990
                            },
                            "dateUpdated": 1464988286367
                        },
                        "dateCreated": 1677060099647,
                        "percentageBased": false,
                        "categoryMemberCount": 111,
                        "id": 791,
                        "building": {
                            "code": "DO NOT REMOVE",
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
                                "street": "901 Bagby St",
                                "postalCode": "77002",
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
                            "name": "Move",
                            "leaseArea": 6000.0,
                            "location": {},
                            "revitLink": "https://a360.co/2IHVNN4",
                            "id": 43,
                            "dateUpdated": 1677197021700,
                            "costCenters": []
                        },
                        "growthValue": 6
                    }
                ]
            }

### Remove a Move Plan [DELETE /move/plans/{id}]
+ Parameters

    + id (string, `287`) ... ID of the Move Plan

+ Response 200

        {
          "response": "Successfully removed"
        }

## Move Approvals [/approvals]
Move Approvals related resources of *iOffice API*

### Retrieve Move Statuses[GET /approvals]

This API retrieves the details of all Move Statuses from Move Approvals Page

+ Response 200

          [
              {
                  "approvalTemplate": {
                      "notification": {
                          "dateCreated": 1663143588283,
                          "id": 27,
                          "dateUpdated": 1663584320782
                      },
                      "dateCreated": 1663143588280,
                      "color": "#CCCCCC",
                      "approvalType": "move",
                      "center": {
                          "name": "Move Center",
                          "id": 77
                      },
                      "name": "Automation 123",
                      "trigger": {
                          "dateCreated": 1663143588280,
                          "id": 53,
                          "matchingType": "ALL",
                          "dateUpdated": 1663584320782
                      },
                      "id": 53,
                      "dateUpdated": 1663584320781
                  },
                  "currentStep": {
                      "dateCreated": 1663157539846,
                      "rule": "ALL",
                      "id": 2
                  },
                  "notification": {
                      "dateCreated": 1663157539860,
                      "id": 1,
                      "notificationUsers": []
                  },
                  "dateCreated": 1663157539853,
                  "approvalType": "move",
                  "center": {
                      "name": "Move Center",
                      "id": 77
                  },
                  "id": 2,
                  "steps": [
                      {
                          "dateCreated": 1663157539846,
                          "rule": "ALL",
                          "id": 2
                      }
                  ]
              }
              ...
          ]

### Retrieve Move Templates[GET /approvals/templates]

This API retrieves the details of all Move Templates from Move Approvals Page

+ Response 200

      [
        {
            "dateCreated": 1605767288423,
            "color": "#f1b2b2",
            "approvalType": "move",
            "center": {
                "name": "Move Center",
                "id": 77
            },
            "name": "Size > 10",
            "trigger": {
                "dateCreated": 1605767288410,
                "id": 1,
                "matchingType": "ALL"
            },
            "id": 1,
            "dateUpdated": 1677106870244
        },
        {
            "dateCreated": 1605767382263,
            "color": "#f1c4a7",
            "approvalType": "move",
            "center": {
                "name": "Move Center",
                "id": 77
            },
            "name": "Location = Move",
            "trigger": {
                "dateCreated": 1605767382260,
                "id": 2,
                "matchingType": "ALL"
            },
            "id": 2,
            "dateUpdated": 1677106870284
        }
        ...
      ]

### Create a Move Template [POST /approvals/templates]
The following attributes are required to create a Move Template

+ Request (application/json)

          {
            "color": "#72634c",
            "name": "demo",
            "steps": [
                {
                    "groups": [
                        {
                            "approverGroup": {
                                "groupType": "ANYADM",
                                "center": {
                                    "name": "Move Center",
                                    "id": 77
                                }
                            }
                        }
                    ],
                    "rule": "ANY",
                    "groupType": "ANYADM"
                }
            ],
            "trigger": {
                "conditions": [
                    {
                        "property": "cost",
                        "qualifier": "IS_GREATER_THAN",
                        "value": "1"
                    }
                ]
            },
            "notification": {
            "id": null
            },
            "center": {
                "id": 77
            },
            "sortOrder": 12,
            "approvalType": "move"
          }

  + Response 201
      + Body

            {
                "notification": {
                    "dateCreated": 1677136556453,
                    "id": 356
                },
                "dateCreated": 1677136556431,
                "color": "#72634c",
                "approvalType": "move",
                "center": {
                    "name": "Move Center",
                    "id": 77
                },
                "name": "demo",
                "trigger": {
                    "dateCreated": 1677136556452,
                    "id": 382,
                    "matchingType": "ALL"
                },
                "id": 382
            }


### Edit a Move Template [PUT /approvals/templates]
The following attributes are required to edit a Move Template

+ Request (application/json)

                 {
                    "id": 381,
                    "name": "demo1"
                 }

+ Response 200
    + Body

          {
                "notification": {
                    "dateCreated": 1677136321256,
                    "id": 355
                },
                "dateCreated": 1677136321250,
                "color": "#72634c",
                "approvalType": "move",
                "center": {
                    "name": "Move Center",
                    "id": 77
                },
                "name": "demo1",
                "trigger": {
                    "dateCreated": 1677136321240,
                    "id": 381,
                    "matchingType": "ALL"
                },
                "id": 381,
                "dateUpdated": 1677138128472
          }

### Remove a Move Template [DELETE /approvals/templates/{id}]
+ Parameters

    + id (string, `287`) ... ID of the Move Template

+ Response 200

        {
          "response": "Successfully removed"
        }
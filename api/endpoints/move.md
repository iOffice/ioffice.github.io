# Group Move
Move-related resources of *iOffice API*

## Move [/move/requests///{id}]
A single move reservation object.

+ Parameters
    + id (string) ... ID of the Move Request


+ Model (application/json)
    JSON representation of the Move Resource

    + Body

           {
             "date": 1504112404863,
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
               "firstName": "Jason",
               "dateCreated": 1464727067663,
               "color": "#89ffa1",
               "name": "Jason Admin",
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
               "userName": "jasonadmin",
               "specialNeeds": false,
               "email": "jpoland@iofficecorp.com",
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
                 "name": "Jason Admin",
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
                   "userName": "jasonadmin",
                   "specialNeeds": false,
                   "dateUpdated": 1488566587390,
                   "firstName": "Jason",
                   "dateCreated": 1464727067663,
                   "phone": "",
                   "name": "Jason Admin",
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
                   "email": "jasongpoland@gmail.com"
                 },
                 "tasksValueMap": {}
               }
             ],
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


## Edit a Move Request [PUT /move/requests/]

To update a Move Request send JSON with updated values for one or more of the attributes.
+ The following attribute is required to update a Move Request: `id`.

+ Request (application/json)


           {
             "date": 1504112404863,
             "approved": true,
             "comments": [
               {
                 "content": "your comment here!"
               }
             ],
             "approvedBy": {
               "id": 9
             },
             "id": 18,
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
                   "userName": "jasonadmin",
                   "specialNeeds": false,
                   "firstName": "Jason",
                   "phone": "",
                   "name": "Jason Admin",
                   "email": "jasongpoland@gmail.com"
                 },
                 "tasksValueMap": {}
               }
             ],
             "status": {
               "id": 10
             }
           }


+ Response 200

          {
             "date": 1504112404863,
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
               "firstName": "Jason",
               "dateCreated": 1464727067663,
               "color": "#89ffa1",
               "name": "Jason Admin",
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
               "userName": "jasonadmin",
               "specialNeeds": false,
               "email": "jpoland@iofficecorp.com",
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
                 "name": "Jason Admin",
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
                   "userName": "jasonadmin",
                   "specialNeeds": false,
                   "dateUpdated": 1488566587390,
                   "firstName": "Jason",
                   "dateCreated": 1464727067663,
                   "phone": "",
                   "name": "Jason Admin",
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
                   "email": "jasongpoland@gmail.com"
                 },
                 "tasksValueMap": {}
               }
             ],
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
                "response": "Successfully removed"
           }


## Move Collection [/move/requests///{{?statusId,approved}]

+ Model (application/json)
    JSON representation of the Move Collection resource.

    + Body

            [
                         {
                           "date": 1504112404863,
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
                             "firstName": "Jason",
                             "dateCreated": 1464727067663,
                             "color": "#89ffa1",
                             "name": "Jason Admin",
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
                             "userName": "jasonadmin",
                             "specialNeeds": false,
                             "email": "jpoland@iofficecorp.com",
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
                               "name": "Jason Admin",
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
                                 "userName": "jasonadmin",
                                 "specialNeeds": false,
                                 "dateUpdated": 1488566587390,
                                 "firstName": "Jason",
                                 "dateCreated": 1464727067663,
                                 "phone": "",
                                 "name": "Jason Admin",
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
                                 "email": "jasongpoland@gmail.com"
                               },
                               "tasksValueMap": {}
                             }
                           ],
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
+ The following attributes are required to create a Move Request: status `id` and type `id`.

+ Request (application/json)

           {
             "date": 1504112404863,
             "approved": true,
             "comments": [
               {
                 "content": "your comment here!"
               }
             ],
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
                   "userName": "jasonadmin",
                   "specialNeeds": false,
                   "firstName": "Jason",
                   "phone": "",
                   "name": "Jason Admin",
                   "email": "jasongpoland@gmail.com"
                 },
                 "tasksValueMap": {}
               }
             ],
             "status": {
               "id": 10
             }
           }


+ Response 201

           {
             "date": 1504112404863,
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
               "firstName": "Jason",
               "dateCreated": 1464727067663,
               "color": "#89ffa1",
               "name": "Jason Admin",
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
               "userName": "jasonadmin",
               "specialNeeds": false,
               "email": "jpoland@iofficecorp.com",
               "dateUpdated": 1488566587390
             },
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
                 "name": "Jason Admin",
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
                   "userName": "jasonadmin",
                   "specialNeeds": false,
                   "dateUpdated": 1488566587390,
                   "firstName": "Jason",
                   "dateCreated": 1464727067663,
                   "phone": "",
                   "name": "Jason Admin",
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
                   "email": "jasongpoland@gmail.com"
                 },
                 "tasksValueMap": {}
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
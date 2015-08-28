# Group Cost Center
Cost Center related resources of *iOffice API*

## Cost Center Collection [/costcenters{?category,parent,root,startAt,limit}]
Collection of all Cost Centers.

+ Parameters
    + category = (optional, integer, , `1`) ... If present, query will filter by category
    + parent = (optional, integer, , `2`) ... If present, query will filter by parent
    + root = `false` (optional, boolean, , `true`) ... If present, query will only return Cost Centers without a parent

+ Model (application/json)
    JSON represenation of the Cost Center Collection Resource

    + Body
        
            [
                {
                    "id": 21,
                    "name": "1 Blah s",
                    "code": "bldg1",
                    "depth": {
                      "code": "flr",
                      "dateCreated": 1435854598093,
                      "level": 3,
                      "name": "Floor",
                      "id": 48,
                      "dateUpdated": 1438958701470
                    },
                    "category": {
                        "code": "co",
                        "color": {},
                        "name": "Company",
                        "id": 27,
                        "dateUpdated": 1435679759130
                    },
                    costCenterParent: {},
                    "dateCreated": 1434561059383,
                    "dateUpdated": 1435679209637 
                }
            ]
### List of all Cost Centers [GET]
+ Response 200
    [Cost Center Collection][]

## Cost Center [/costcenters/{id}]
A single Cost Center object.

+ Model (application/json)
    JSON representation of the Cost Center Resource

    + Body
        
            {
                    "id": 21,
                    "name": "1 Blah s",
                    "code": "bldg1",
                    "depth": {
                      "code": "flr",
                      "dateCreated": 1435854598093,
                      "level": 3,
                      "name": "Floor",
                      "id": 48,
                      "dateUpdated": 1438958701470
                    },
                    "category": {
                        "code": "co",
                        "color": {},
                        "name": "Company",
                        "id": 27,
                        "dateUpdated": 1435679759130
                    },
                    costCenterParent: {},
                    "dateCreated": 1434561059383,
                    "dateUpdated": 1435679209637 
                }

### Retrieve a Single Cost Center [GET]
+ Parameters
    + id (string) ... ID of the Cost Center
+ Response 200 
    [Cost Center][]

### Create a Cost Center [POST /costcenters]
The following attributes are required to create a Cost Center: 

+ Request (application/json)
    
        {
            "name":"new cc",
            "code":"new-cc-code", 
            "category": {
                "id": 31
            }
        }

+ Response 201
    
        {
            "id": 21,
            "name": "1 Blah s",
            "code": "bldg1",
            "depth": {
                "code": "flr",
                "dateCreated": 1435854598093,
                "level": 3,
                "name": "Floor",
                "id": 48,
                "dateUpdated": 1438958701470
             },
            "category": {
                "code": "co",
                "color": {},
                "name": "Company",
                "id": 27,
                "dateUpdated": 1435679759130
            },
            costCenterParent: {},
            "dateCreated": 1434561059383,
            "dateUpdated": 1435679209637 
        }
### Edit a Cost Center [PUT /costcenters/{id}]
To update a Cost Center send JSON with updated value for one or more of the attributes.
+ Parameters
    + id (string) ... ID of the Cost Center
+ Request (application/json)

        {
            "id": 23,
            "name": "newName",
            "code": "bldg3"
        }

+ Response 200
    + Body
                
            {
                "id": 23,
                "name": "newName",
                "code": "bldg3",
                "depth": {
                    "code": "flr",
                    "dateCreated": 1435854598093,
                    "level": 3,
                    "name": "Floor",
                    "id": 48,
                    "dateUpdated": 1438958701470
                 },
                "category": {
                    "code": "co",
                    "color": {},
                    "name": "Company",
                    "id": 27,
                    "dateUpdated": 1435679759130
                },
                costCenterParent: {},
                "dateCreated": 1434561059383,
                "dateUpdated": 1435679209637 
            }

### Remove a Cost Center [DELETE]

+ Response 200

## Cost Center Helpers [/costcenters] 

### Get a Cost Center's children [GET /costcenters/{id}/children]
+ Parameters
    + id (string) ... ID of the Cost Center

+ Response 200

        [
          {
            "code": "f1",
            "dateCreated": 1434561227550,
            "name": "First Floor",
            "id": 137,
            "category": {
                "code": "co",
                "color": {},
                "name": "Company",
                "id": 27,
                "dateUpdated": 1435679759130
            },
            "costCenterParent": {
              "code": "bldg1",
              "dateCreated": 1434561059383,
              "name": "1 Blah s",
              "id": 133,
              "dateUpdated": 1435679209637
            },
            "dateUpdated": 1435681499297
          },
          {
            "code": "f2",
            "dateCreated": 1435783794327,
            "name": "Second Floor",
            "id": 171,
            "costCenterParent": {
              "code": "bldg1",
              "dateCreated": 1434561059383,
              "name": "1 Blah s",
              "id": 133,
              "dateUpdated": 1435679209637
            }
          }
        ]

### Get the users assigned to a specific Cost Center [GET /costcenters/{id}/users]
+ Parameters
    + id (string) ... ID of the Cost Center

+ Response 200
        
        [ 
          {
            "floorWarden": false,
            "costCenter1": "First Floor",
            "lastName": "Silverman",
            "color": "#a5c7f7",
            "costCenter": {},
            "userName": "ssilverman",
            "specialNeeds": false,
            "room": {},
            "dateUpdated": 1435585164033,
            "firstName": "Sarah",
            "dateCreated": 1435585128170,
                "name": "Sarah Silverman",
                "id": 11,
                "userType": {
                  "dateCreated": 1430925761040,
                  "name": "Employee",
                  "id": 1,
                  "fields": [],
                  "dateUpdated": 1437164292987
                },
                "costCenter2": "Edit Team 1",
                "email": "test@test.com"
              },
              {
                "costCenter1": "First Floor",
                "lastName": "Operator",
                "extension": "",
                "color": "#8b80f2",
                "jobTitle": "Manager",
                "specialNeeds": false,
                "dateCreated": 1428424375617,
                "knownAs": "",
                "company": "",
                "id": 9,
                "department": "",
                "fax": "",
                "costCenter2": "Mkt Team 1",
                "email": "test@test.com",
                "floorWarden": false,
                "comments": "",
                "costCenter": {},
                "mobile": "",
                "employeeId": "",
                "userName": "moperator",
                "room": {},
                "dateUpdated": 1435870455727,
                "firstName": "Mark",
                "phone": "",
                "name": "Mark Operator",
                "userType": {
                  "dateCreated": 1430925761040,
                  "name": "Employee",
                  "id": 1,
                  "fields": [],
                  "dateUpdated": 1437164292987
                }
              },
              {
                "costCenter1": "First Floor",
                "lastName": "Admin",
                "extension": "",
                "color": "#dd81f4",
                "jobTitle": "Administrator",
                "specialNeeds": false,
                "dateCreated": 1428423879367,
                "knownAs": "",
                "company": "",
                "id": 7,
                "department": "",
                "fax": "",
                "costCenter2": "Edit Team 1",
                "email": "test@test.com",
                "floorWarden": false,
                "comments": "",
                "costCenter": {},
                "mobile": "",
                "employeeId": "",
                "userName": "madmin",
                "dateUpdated": 1440688251423,
                "firstName": "Mark",
                "phone": "",
                "name": "Mark Admin",
                "userType": {
                  "dateCreated": 1430925761040,
                  "name": "Employee",
                  "id": 1,
                  "fields": [],
                  "dateUpdated": 1437164292987
                }
              }
            ]

### Get the users assigned to any Cost Center [GET /costcenters/users]
+ Response 200

       
        [ 
          {
            "floorWarden": false,
            "costCenter1": "First Floor",
            "lastName": "Silverman",
            "color": "#a5c7f7",
            "costCenter": {},
            "userName": "ssilverman",
            "specialNeeds": false,
            "room": {},
            "dateUpdated": 1435585164033,
            "firstName": "Sarah",
            "dateCreated": 1435585128170,
                "name": "Sarah Silverman",
                "id": 11,
                "userType": {
                  "dateCreated": 1430925761040,
                  "name": "Employee",
                  "id": 1,
                  "fields": [],
                  "dateUpdated": 1437164292987
                },
                "costCenter2": "Edit Team 1",
                "email": "test@test.com"
              },
              {
                "costCenter1": "First Floor",
                "lastName": "Operator",
                "extension": "",
                "color": "#8b80f2",
                "jobTitle": "Manager",
                "specialNeeds": false,
                "dateCreated": 1428424375617,
                "knownAs": "",
                "company": "",
                "id": 9,
                "department": "",
                "fax": "",
                "costCenter2": "Mkt Team 1",
                "email": "test@test.com",
                "floorWarden": false,
                "comments": "",
                "costCenter": {},
                "mobile": "",
                "employeeId": "",
                "userName": "moperator",
                "room": {},
                "dateUpdated": 1435870455727,
                "firstName": "Mark",
                "phone": "",
                "name": "Mark Operator",
                "userType": {
                  "dateCreated": 1430925761040,
                  "name": "Employee",
                  "id": 1,
                  "fields": [],
                  "dateUpdated": 1437164292987
                }
              },
              {
                "costCenter1": "First Floor",
                "lastName": "Admin",
                "extension": "",
                "color": "#dd81f4",
                "jobTitle": "Administrator",
                "specialNeeds": false,
                "dateCreated": 1428423879367,
                "knownAs": "",
                "company": "",
                "id": 7,
                "department": "",
                "fax": "",
                "costCenter2": "Edit Team 1",
                "email": "test@test.com",
                "floorWarden": false,
                "comments": "",
                "costCenter": {},
                "mobile": "",
                "employeeId": "",
                "userName": "madmin",
                "dateUpdated": 1440688251423,
                "firstName": "Mark",
                "phone": "",
                "name": "Mark Admin",
                "userType": {
                  "dateCreated": 1430925761040,
                  "name": "Employee",
                  "id": 1,
                  "fields": [],
                  "dateUpdated": 1437164292987
                }
              }
            ]
 

### Get the rooms assigned to a specific Cost Center [GET /costcenters/{id}/rooms]
+ Parameters
    + id (string) ... ID of the Cost Center

+ Response 200

        [
          {
            "reservable": true,
            "name": "03-355",
            "id": 51,
            "floor": {
              "area": 0,
              "name": "Floor1",
              "id": 1,
              "building": {
                "address": {
                  "country": { },
                  "city": "Houston",
                  "street": "",
                  "postalCode": "",
                  "state": {
                    "country": {},
                    "defaultSelected": false,
                    "code": "TX",
                    "name": "Texas",
                    "id": 61,
                    "categoryName": "state"
                  }
                },
                "code": "BLDG1",
                "metric": false,
                "name": "Building1",
                "id": 43
              }
            }
          },
          {
            "reservable": true,
            "name": "03-354",
            "id": 52,
            "floor": {
              "area": 0,
              "name": "Floor1",
              "id": 1,
              "building": {
                "address": {
                  "country": {},
                  "city": "Houston",
                  "street": "",
                  "postalCode": "",
                  "state": {
                    "country": {},
                    "defaultSelected": false,
                    "code": "TX",
                    "name": "Texas",
                    "id": 61,
                    "categoryName": "state"
                  }
                },
                "code": "BLDG1",
                "metric": false,
                "name": "Building1",
                "id": 43
              }
            }
          }
        ]

### Get the rooms assigned to any Cost Center [GET /rooms]
+ Response 200

        [
          {
            "reservable": true,
            "name": "03-355",
            "id": 51,
            "floor": {
              "area": 0,
              "name": "Floor1",
              "id": 1,
              "building": {
                "address": {
                  "country": { },
                  "city": "Houston",
                  "street": "",
                  "postalCode": "",
                  "state": {
                    "country": {},
                    "defaultSelected": false,
                    "code": "TX",
                    "name": "Texas",
                    "id": 61,
                    "categoryName": "state"
                  }
                },
                "code": "BLDG1",
                "metric": false,
                "name": "Building1",
                "id": 43
              }
            }
          },
          {
            "reservable": true,
            "name": "03-354",
            "id": 52,
            "floor": {
              "area": 0,
              "name": "Floor1",
              "id": 1,
              "building": {
                "address": {
                  "country": {},
                  "city": "Houston",
                  "street": "",
                  "postalCode": "",
                  "state": {
                    "country": {},
                    "defaultSelected": false,
                    "code": "TX",
                    "name": "Texas",
                    "id": 61,
                    "categoryName": "state"
                  }
                },
                "code": "BLDG1",
                "metric": false,
                "name": "Building1",
                "id": 43
              }
            }
          }
        ]

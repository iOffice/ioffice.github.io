# Group Mail
Mail-related resources of *iOffice API*

## Mail [/mail/items///{id}]
A single mail item object.


+ Parameters
    + id (string) ... ID of the Mail Item

+ Model (application/json)
    JSON representation of the Mail Item Resource

    + Body

            {
              "currentQueue": "OUT",
              "toUser": {
                "lastName": "Hill",
                "id": 420,
                "email": "hankhill@iofficecorp.com",
                "userName": "hankhill",
                "firstName": "Hank",
                "name": "Hank Hill",
                "userType": {
                  ...
                }
              },
              "itemType": "INBOUND",
              "route": {
                "forShipping": false,
                "dateCreated": 1389629005210,
                "name": "Propane Mail Stop",
                "id": 99,
                "dateUpdated": 1496351321157
              },
              "originalTrackingNumber": "1234567890",
              "courier": {
                "code": "OTHER",
                "dateCreated": 1064937226683,
                "name": "Other",
                "id": 5,
                "dateUpdated": 1066939059227
              },
              "deliveryType": "Other",
              "statuses": [
                {
                  "center": {
                    "name": "Propane Receiving",
                    "id": 68
                  },
                  "id": 2426,
                  "enteredBy": {
                    "lastName": "Hill",
                    "firstName": "Bobby",
                    "phone": "123-456-7899",
                    "name": "Bobby Hill",
                    "userType": {
                      ...
                    }                    
                    "extension": "123",
                    "company": "Strickland Propane",
                    "id": 1,
                    "email": "bobbyhill@iofficecorp.com",
                    "employeeId": "99",
                    "userName": "bobbyhill",
                    "mailStop": {
                      "name": "Bobby's Room Mail Stop",
                      "id": 139
                    },                    
                    "room": {
                      "type": {
                        ...
                      },
                      "name": "803",
                      "id": 160,
                      "mailStop": {
                        "name": "Bobby's Room Mail Stop",
                        "id": 139
                      },
                      "floor": {
                        "name": "08",
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
                            "city": "Arlen",
                            "street": "1598 Strickland Way",
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
                          "code": "PRPN",
                          "name": "Lone Star Tower",
                          "location": {},
                          "id": 43,
                        },
                      }
                    },
                  }
                },
                {
                  "center": {
                    "name": "Mail Center",
                    "id": 68
                  },
                  "id": 2721,
                  "enteredBy": {
                    "lastName": "Service",
                    "extension": "123",
                    "knownAs": "",
                    "company": "IOFFICE",
                    "id": 1,
                    "email": "jroussel@iofficecorp.com",
                    "floorWarden": false,
                    "mobile": "",
                    "employeeId": "",
                    "userName": "ioffice",
                    "room": {
                      "type": {
                        ...
                      },
                      "name": "803",
                      "id": 160,
                      "mailStop": {
                        "name": "Stop 1",
                        "id": 139
                      },
                      "floor": {
                        "name": "08",
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
                          "code": "PRPN",
                          "name": "Lone Star Tower",
                          "location": {},
                          "id": 43,
                        },
                      }
                    },
                    "firstName": "Customer",
                    "phone": "123-456-7899",
                    "name": "Customer Service",
                    "mailStop": {
                      "name": "Stop 1",
                      "id": 139
                    },
                    "userType": {
                      ...
                    }
                  }
                }
              ],
              "id": 1773,
              "packageType": {
                "code": "env",
                "dateCreated": 1345679479550,
                "sortOrder": 3,
                "name": "Envelope",
                "id": 1,
                "dateUpdated": 1465239263837
              },
              "trackingNumber": "1234567890",
              "deliverTo": {
                "lastName": "Hill",
				 "firstName": "Peggy",
                "id": 123,
                "email": "peggyhill@iofficecorp.com",
                "userName": "peggyhill",
                "name": "Peggy Hill",
                "userType": {
                  ...
                }
              }
            }

### Retrieve a Single Mail Item [GET]
+ Response 200

    [Mail][]
    
### Edit a Mail Item [PUT]
To update a Mail Item send JSON with the id and updated value for one or more of the attributes.
    
+ Request (application/json)

        {
        "id": 1773,
        "toUser": {
          "lastName": "Hill",
          "firstName": "Peggy",
          "id": 123,
          "email": "peggyhill@iofficecorp.com",
          "userName": "peggyhill",
          "name": "Peggy Hill",
          "userType": {
          ...
          }
        },
		  "itemType": "INBOUND",
		  "route": {
			"forShipping": false,
			"dateCreated": 1389629005210,
			"name": "Propane Mail Stop",
			"id": 99,
			"dateUpdated": 1496351321157
		  },           
        }

+ Response 200
    
    [Mail][]

### Remove a Mail Item [DELETE]
+ Parameters
    + id (string) ... ID of the Mail Item
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }    
        
## Mail Items Collection [/mail/items]
Collection of all Mail Items.

+ Model (application/json)
    JSON representation of the Mail Items Collection resource.

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

### List of all Mail Items [GET]

+ Response 200
    
    [Mail Items Collection][]        
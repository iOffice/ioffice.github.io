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
                "id": 1773,
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
To update a Mail Item send JSON with the Mail Item's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Mail Item
  
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
                 
### Deliver a Mail Item [PUT /mail/items///{id}///deliver]
To deliver a single Mail Item send JSON with the required attributes.

+ Parameters
    + id (string) ... ID of the Mail Item
  
+ Request (application/json)

            {
              "itemType": "INTEROFFICE",
              "fromUser": {
                "id": 13
              },
              "toUser": {
                "id": 126
              },
              "id": 1906,
              "trackingNumber": "351987984"
            }

+ Response 200   
    [Mail][]
    
### Deliver many Mail Items [PUT /mail/items/deliver]
To deliver many Mail Items send JSON with the required attributes.

+ Request (application/json)

			[
				{
				  "itemType": "INTEROFFICE",
				  "fromUser": {
					"id": 13
				  },
				  "toUser": {
					"id": 126
				  },
				  "id": 1906,
				  "trackingNumber": "351987984"
				},
				...
			]

+ Response 200   
    [Mail][]    
    
## Checkout a Mail Item [PUT /mail/items///{id}///checkout]
To checkout a single Mail Item send JSON with the required attributes.

+ Parameters
    + id (string) ... ID of the Mail Item
  
+ Request (application/json)

            {
              "itemType": "INTEROFFICE",
              "fromUser": {
                "id": 13
              },
              "toUser": {
                "id": 126
              },
              "id": 1906,
              "trackingNumber": "351987984"
            }

+ Response 200
    [Mail][]
    
### Pend a Mail Item [PUT /mail/items///{id}///pending]
To pend a Mail Item send JSON with the required attributes.

+ Parameters
    + id (string) ... ID of the Mail Item
  
+ Request (application/json)

            {
              "itemType": "INTEROFFICE",
              "fromUser": {
                "id": 13
              },
              "toUser": {
                "id": 126
              },
              "id": 1906,
              "trackingNumber": "351987984"
            }

+ Response 200
    [Mail][]   
    
### Transfer a Mail Item [PUT /mail/items///{id}///transfer]
To transfer a Mail Item send JSON with the required attributes.

+ Parameters
    + id (string) ... ID of the Mail Item
  
+ Request (application/json)

            {
              "itemType": "INTEROFFICE",
              "fromUser": {
                "id": 13
              },
              "toUser": {
                "id": 126
              },
              "id": 1906,
              "trackingNumber": "351987984"
            }

+ Response 200
    [Mail][]    
    
### Add a Comment to a Mail Item [PUT /mail/items///{id}///addComment]
To add a Comment to a Mail Item send JSON with the required attributes.

+ Parameters
	+ id (string) ... ID of the Mail Item
  
+ Request (application/json)

            {
              "comment: "This is a comment!",
            }

+ Response 200
    [Mail][]                        
        
## Mail Items Collection [/mail/items///{?search,modifiedOrCreatedAfter}]
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
            ]

### List of all Mail Items [GET]

+ Parameters
    + search (optional, number, `351987984`) ... Number to search for mail item by id, trackingNumber, or originalTrackingNumber
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Mail Items Collection][]  
    
## Check In one or many Mail Items [POST /mail/items/checkin]
To Check In one or many Mail Items send JSON with the required attributes.

+ Request (application/json)

			[
				{
				  "itemType": "OUTBOUND",
				  "packageType": {
					"id": 1
				  },
				  "center": {
					 "id": 62
					},
				  "fromUser": {
					"id": 13
				  },
				  "toUser": {
					"id": 126
				  },
				  "trackingNumber": "351987984"
				},
				...
			]

+ Response 200  
    [Mail][]         
    
## Mail Item IDs [/mail/items/ids{?modifiedOrCreatedAfter}]
Retrieve all Mail Item IDs.

+ Model (application/json)
    JSON representation of the Mail Item ID resource.

    + Body

            [
                1234,
                5678,
                9012,
                3456,
                7890
            ]

### Retrieve Mail Item IDs [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Mail Item IDs][]
    
    
## Delivered Mail Items [/mail/items/delivered{?modifiedOrCreatedAfter}]
Collection of all Delivered Mail Items.

+ Model (application/json)
    JSON representation of the Delivered Mail Items Collection resource.

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

### Retrieve Delivered Mail Items [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Delivered Mail Items][]    
    
## Package Types [/mail/packageTypes{?modifiedOrCreatedAfter}]
Collection of all Mail Package Types.

+ Model (application/json)
    JSON representation of the Mail Package Types resource.

    + Body

            [
              {
                "code": "env",
                "dateCreated": 1345679479550,
                "sortOrder": 3,
                "name": "Envelope",
                "id": 1,
                "dateUpdated": 1465239263837
              },
              {
                "code": "box",
                "dateCreated": 1345679479567,
                "sortOrder": 1,
                "name": "Box",
                "id": 2,
                "dateUpdated": 1465239263837
              },
              {
                "code": "bag",
                "dateCreated": 1345679479570,
                "sortOrder": 2,
                "name": "Bag",
                "id": 3,
                "dateUpdated": 1465239263843
              }
            ]

### Retrieve Package Types [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Package Types][]   
    
## Mail Stops [/mail/mailstops{?modifiedOrCreatedAfter}]
Collection of all Mail Stops.

+ Model (application/json)
    JSON representation of the Mail Stops resource.

    + Body

            [
              {
                "name": "Goku Stop",
                "id": 123
              },
              {
                "name": "Vegeta Stop",
                "id": 456
              },
              {
                "name": "Piccolo Stop",
                "id": 789
              },
              {
                "name": "Master Roshi Stop",
                "id": 012
              },
              {
                "name": "Dragon Ball Stop",
                "id": 345
              }
            ]

### Retrieve Mail Stops [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Mail Stops][]      
    
## Mail Status Types [/mail/types{?modifiedOrCreatedAfter}]
Collection of all Mail Status Types.

+ Model (application/json)
    JSON representation of the Mail Status Types resource.

    + Body

            [
              {
                "code": "out",
                "name": "Delivered",
                "id": 1
              },
              {
                "code": "checkin",
                "name": "Checked In",
                "id": 2
              },
              {
                "code": "checkout",
                "name": "Checked out",
                "id": 3
              }
            ]

### Retrieve Mail Status Types [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Mail Routes][]     
    
## Mail Routes [/mail/routes{?modifiedOrCreatedAfter}]
Collection of all Mail Routes.

+ Model (application/json)
    JSON representation of the Mail Routes resource.

    + Body

            [
              {
                "forShipping": false,
                "dateCreated": 1106077148680,
                "name": "DBZ Mail Center",
                "id": 9000,
                "dateUpdated": 1465497845000
              },
              {
                "forShipping": true,
                "dateCreated": 1136928941950,
                "name": "Sailor Moon Mail Center",
                "id": 5,
                "dateUpdated": 1465497863110
              },
              {
                "forShipping": false,
                "dateCreated": 1374783404423,
                "name": "Ranma 1/2 Mail Center",
                "id": 999,
                "dateUpdated": 1465497836000
              }
            ]

### Retrieve Mail Routes [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Mail Routes][] 
    
## Mail Locations [/mail/locations{?modifiedOrCreatedAfter}]
Collection of all Mail Locations.

+ Model (application/json)
    JSON representation of the Mail Locations resource.

    + Body

            [
              {
                "dateCreated": 1449102051820,
                "sortOrder": 1,
                "name": "Rack 1",
                "id": 1,
                "dateUpdated": 1501188860653
              },
              {
                "dateCreated": 1449102051820,
                "sortOrder": 2,
                "name": "Rack 2",
                "id": 2,
                "dateUpdated": 1501188860657
              },
              {
                "dateCreated": 1483036976673,
                "sortOrder": 3,
                "name": "Rack 3",
                "id": 3,
                "dateUpdated": 1501188860660
              }
            ]           

### Retrieve Mail Locations [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Mail Locations][]     

## Mail Alerts [/mail/alerts{?modifiedOrCreatedAfter}]
Collection of all Mail Alerts.

+ Model (application/json)
    JSON representation of the Mail Alerts resource.

    + Body

            [
              {
                "multipleAlerts": true,
                "notes": "This is a Note!",
                "id": 1,
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
						  "id": 43
						},
					  },
					},
				 },
			   },   	
            ]
              
### Retrieve Mail Alerts [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Mail Alerts][]    
    
## Mail Leaderboards for Deliveries [/stats/leaderboards/deliveries{?modifiedOrCreatedAfter}]
Collection of Leaderboards for Mail Deliveries.

+ Model (application/json)
    JSON representation of the Mail Leaderboards for Deliveries resource.

    + Body

            [
				{
					"count": 99,
					"user": {
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
						  },
						},
					},		  
				 },
				 ...			              
            ]           

### Retrieve Leaderboards for Mail Deliveries  [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Mail Leaderboards for Deliveries][]      
    
## Mail Leaderboards for Check-Ins [/stats/leaderboards/check-ins{?modifiedOrCreatedAfter}]
Collection of Leaderboards for Check-Ins.

+ Model (application/json)
    JSON representation of the Mail Leaderboards for Check-Ins resource.

    + Body

            [
				{
					"count": 67,
					"user": {
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
						  },
						},
					},		  
				 },
				 ...			              
            ]           

### Retrieve Leaderboards for Mail Check-Ins  [GET]

+ Parameters
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Mail Leaderboards for Check-Ins][]                               

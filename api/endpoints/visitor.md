# Group Visitor
Visitor-related resources of *iOffice API*

## Visitor [/visitors///{id}]
A single visitor object.

+ Parameters
    + id (string) ... Visitor ID


+ Model (application/json)
  JSON representation of the Visitor Resource

    + Body

            {
                "status": "ok",
                "response": {
                    "visitorId": {
                        "id": 2021
                    },
                    "visitorInfo": {
                        "visitorAlertId": 0,
                        "firstName": "Tom",
                        "lastName": "Richards",
                        "company": "Tesla",
                        "email": "abc@xyz.com",
                        "notes": "For interview",
                        "dateCreated": "2022-03-31T07:55:37.66",
                        "createdBy": 3519,
                        "dateUpdated": "2022-09-20T04:13:43",
                        "lastUpdatedBy": 3517,
                        "visitorType": "Interview",
                        "active": true
                    },
                    "visitorIdentification": {},
                    "visitorAddress": {
                         "address": "Texas",
                         "state": "Texas",
                         "postalCode": "400001",
                         "phone": "1234567"
                    },
                    "visitorCustomFields": {}
                }
            }

### Retrieve a Single Visitor [GET]
+ Response 200

  [Visitor][]


## Check-in registered visitor [/visitors///registrations///{id}///checkin]

### Check-in Registered Visitor [POST]

+ Parameters
    + id (string) ... Registration ID

+ Response 200
    + Body

            {
                "status": "ok",
                "response": {
                    "id": {
                        "id": 3438
                    },
                "visitorId": {
                    "id": 2021
                },
                "userId": 3517,
                "centerId": 128,
                "arrivalDateTime": "1464727067663",
                "statusId": 2,
                "notes": "scheduled interview",
                "badgePrinted": "Yes",
                "isTouchless": false,
                "dateCreated": "1464727067663",
                "createdBy": 3517,
                "alertFlag": 0,
                "signatureId": {
                    "id": "3050ea3e-aa95-c796-7078-3bd4dc6fd53d"
                }
            }


## Batch checkin [/visitors///registrations///batch///checkin]

### Batch Check-in Visitors [POST]

+ Request (application/json)

        {
            "visitors": [
                {
                    "registrationId": 3374
                },
                {
                    "registrationId": 3361
                }
            ]
       }

+ Response 200


## Pre-register a visitor [/visitors///registrations///preregister]

### Pre-register a Visitor [POST]

+ Request (application/json)

        {
              "arrivalDate": 1663667820000,
              "userId": 3903,
              "visitorTypeName": "",
              "visitor": {
                  "visitorInfo": {
                      "visitorAlertId": 0,
                      "firstName": "FirstName",
                      "lastName": "LastName",
                      "company": "Tesla",
                      "email": "abc@xyz.com",
                      "notes": "preRegister",
                      "dateCreated": "1663667820000",
                      "createdBy": 3516,
                      "visitorType": "Furniture",
                      "active": true
                  },
                  "visitorAddress": {
                      "address": "Newyork",
                      "state": "Newyork",
                      "postalCode": "500123",
                      "phone": "5443729573"
                  },
                  "visitorIdentification": {},
                  "visitorCustomFields": {},
                  "visitorId": {
                      "id": 1982
                  }
              },
              "submittedByUser": {
                  "id": 3903
              },
              "deviceName": "Desktop",
              "centerId": 128
        }

+ Response 200

    + Body

            {
                "status": "ok",
                "response": {
                    "id": {
                        "id": 3438
                    },
                "visitorId": {
                    "id": 2021
                },
                "userId": 3517,
                "centerId": 128,
                "arrivalDateTime": "1464727067663",
                "statusId": 2,
                "notes": "scheduled interview",
                "badgePrinted": "Yes",
                "isTouchless": false,
                "dateCreated": "1464727067663",
                "createdBy": 3517,
                "deviceName": "Desktop"
            }

### Visitor Types [/visitors/types/stringIcon/]

## Retrieve Collection of Visitor Types [GET]

+ Response 200

	{
	  "status": "ok",
	  "response": [
		{
		  "id": {
			"id": 40
		  },
		  "name": "Employee",
		  "active": true,
		  "iconUid": "color:microsoft-powerpoint-2019--v2"
		},
		{
		  "id": {
			"id": 41
		  },
		  "name": "Visitor",
		  "active": true,
		  "iconUid": "ios7:visa"
		},
		{
		  "id": {
			"id": 58
		  },
		  "name": "Contractor",
		  "active": true,
		  "iconUid": "office:maintenance"
		},
		{
		  "id": {
			"id": 70
		  },
		  "name": "Guest new1",
		  "active": true,
		  "iconUid": "fluent:star"
		},
		{
		  "id": {
			"id": 5246
		  },
		  "name": "UI Test",
		  "active": true,
		  "iconUid": "m_outlined:gear--v2"
		}
	  ]
	}

## Add Visitor Type [POST]

+ Request (application/json)

	{
	  "name": "NewGuest",
	  "active": true,
	  "iconUid": "23265"
	}
	
+ Response 200

	{
	  "status": "ok",
	  "response": {
		"id": 5248
	  }
	}
	
## Update/Remove Visitor Type [PUT]

+ active (optional, boolean, `false`) ... Set it to false to remove a Visitor Type

+ Request (application/json)

	{
	  "id": {
		"id": 5248
	  },
	  "name": "NewGuestEdited",
	  "active": true,
	  "iconUid": "23265"
	}
	
+ Response 200

	{
	  "status": "ok",
	  "response": 1
	}
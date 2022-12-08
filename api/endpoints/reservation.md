# Group Reservation
Reservation-related resources of *iOffice API*

## Reservation [/reservations///{id}]
A single reservation object.


+ Parameters
    + id (string) ... ID of the Reservation

+ Model (application/json)
    JSON representation of the Reservation Resource

    + Body

            {
                "id": ID,
                "center": {...},
                "numberOfPeople": INT,
                "allDay": "BOOLEAN",
                "checkedIn": "BOOLEAN",
                "checkedOut": "BOOLEAN",
                "notes": "STRING"
                "madeInIoffice": "BOOLEAN",
                "name": "STRING",
                "user": {...},
                "dateUpdated": EPOCH_TIME,
                "room": {...}
            }

### Retrieve a Single Reservation [GET]
+ Response 200

    [Reservation][]

### Edit a Reservation [PUT]
To update a Reservation send JSON with the Reservation's `ID` and updated value for one or more of the attributes.

+ Parameters
    + id (string) ... ID of the Reservation
    
+ Request (application/json)

        {
        	"id": 23,
            "user": {
                "id": 56
            }
        }

+ Response 200
    
    [Reservation][]

### Remove a Reservation [DELETE]
+ Parameters
    + id (string) ... ID of the Reservation
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

## Reservation Collection [/reservations///{?includeCancelled,includePastReservations,includeNonCancelled,showOnlyMyReservations,startDate,endDate,buildingId,roomId,modifiedOrCreatedAfter}]
Collection of all Reservations.

+ Model (application/json)
    JSON representation of the Reservation Collection resource.

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

### List of all Reservations [GET]

+ Parameters
    + includeCancelled = `false` (optional, boolean, , `true`) ... If true, query will include cancelled reservations
    + includeNonCancelled = `true` (optional, boolean, , `false`) ... If true, query will include non-cancelled reservations
    + includePastReservations = `false` (optional, boolean, `true`) ... If true, query will include past reservations
    + showOnlyMyReservations = `true` (optional, boolean, `false`) ... If true, query will only include logged in user's reservations
    + startDate (optional, number, `1404410211910`) ... Epoch time (milliseconds) of reservation start date
    + endDate (optional, number, `1404421051661`) ... Epoch time (milliseconds) of reservation end date
    + buildingId (optional, number, `44`) ... Id of the building to query from
    + limit (optional, number, `500`) ... Reservations List limit to query from
    + roomId (optional, number, `16`) ... Id of the room to query from
    + modifiedOrCreatedAfter (optional, number, `1549319834`) ... Epoch time (milliseconds) to poll recently modified items in the collection.

+ Response 200
    
    [Reservation Collection][]


### Create a Reservation [POST]
The following attributes are required to create a Reservation: `startDate`, `endDate`, `user`, `room`, `center`, and `allDay`.

+ Request (application/json)

            {
                "startDate": EPOCH_TIME,
                "endDate": EPOCH_TIME
                "numberOfPeople": INT,
                "allDay": "BOOLEAN",
                "name": "STRING",
                "center": {...},
                "user": {...},
                "guests": [..],
                "room": {...},
                "notes": "STRING"
            }

+ Response 201

    [Reservation][]

## Cancel [/reservations///{id}/cancel]
Cancel Reservation

+ Parameters

    + id (string) ... ID of the Reservation

### Cancel Reservation [PUT]
+ Response 200

          {
              "id": ID,
              "cancellationReason": "STRING"
              "cancelled": "BOOLEAN"
              "startDate": EPOCH_TIME,
              "endDate": EPOCH_TIME
              "numberOfPeople": INT,
              "checkedIn": "BOOLEAN",
              "checkedOut": "BOOLEAN",
              "name": "STRING",
              "dateCreated": EPOCH_TIME,
              "dateUpdated": EPOCH_TIME,
              "user": {...},
              "center": {...},
              "room": {...},
              "notes": "STRING"
          }


## Check In [/reservations///{id}/checkIn]
Reservation Check In

+ Parameters

    + id (string) ... ID of the Reservation

### Reservation Check In [PUT]
+ Response 200
    [Reservation][]


## Check Out [/reservations///{id}/checkOut]
Reservation Check Out

*Not available through the desktop app*

+ Parameters

    + id (string) ... ID of the Reservation

### Reservation Check Out [PUT]
+ Response 200
    [Reservation][]

## Promo Content [/center///{?module,selector}]
Promo Content Collection

+ Model (application/json)
    JSON representation of the Promo Content resource.

    + Body

            [
                {
                    "promoContent": [],
                    "name": "Test",
                    "id": 177
                },
                {
                    "promoContent": [],
                    "name": "SiteAdmin4388",
                    "id": 178
                },
                {
                    "promoContent": [],
                    "name": "SiteAdmin4388",
                    "id": 179
                }
                ...
            ]

### Retrieve Promo Content [GET]
The following attributes are required to get Promo Content details: `module`, `selector`.

+ Parameters
    + module (string, `reservation`) ... Module name
    + selector (string, `id%2Cname%2CpromoContent`) ... Selector ID

+ Response 200

    [Promo Content][]

### Retrieve Center Name [PUT /centers/promo]

+ Request (application/json)

        {
           "centerId":82,
           "promoContent": 
           [
              "<p><a href=\"https://www.iofficecorp.com/\" rel=\"noopener noreferrer\" target=\"_blank\"><img src=\"https://www.iofficecorp.com/hubfs/2017/Marketplace/ioffice-wheel-2.png?t=1519997685552\"></a></p>",
              "<p><a href=\"https://www.yahoo.com\" rel=\"noopener noreferrer\" target=\"_blank\"><img src=\"https://i.ibb.co/94HpJFj/Screenshot-1.jpg\"></a></p>",
              "<p><img src=\"https://i.ibb.co/7ktkjr6/Screen-Shot-2021-04-21-at-10-57-10-AM.png\"></p>",
              "<p><a href=\"https://hq.iofficeconnect.com/home.i#/admin/users\" rel=\"noopener noreferrer\" target=\"_blank\">HQ SIte</a></p>",
              "<p><img src=\"https://s3.eu-central-1.amazonaws.com/rainforest-random-images/004.jpeg\"></p>"
          ]
        }

+ Response 200

      {
          "name": "Reservation Center",
          "id": 82
      }

### Notification [GET /notifications/{?limit}]
The following attribute is required to get a Notification: `limit`.

+ Parameters
    + limit (optional, number, `500`) ... Reservations List limit to query from

+ Response 200
    []

### Services [GET /system/config/services]

+ Response 200

      {
          "servicesLocation": "https://services-dev.api.iofficeconnect.com",
          "websocketsLocation": "wss://ws-dev.api.iofficeconnect.com",
          "tilesLocation": "https://drawing-tile-default.qa.iofficeconnect.dev/drawings"
      }

### User Details [/users/me]
Details of User in Promo Content

#### User Specific Info [GET /users/me]

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

#### User Email Info [GET /users/me/{?selector}]

*'selector' expects email value in parameter as mentioned in example.*

The following attribute is required to get user's email info: `selector`.

+ Parameters
    + selector (string, `email%2CfirstName%2CuserName`) ... Selector ID

+ Response 200

      {
         "firstName": "Ashitosh",
         "name": "Admin Wagh",
         "id": 3951,
         "userName": "ashitosh.wagh",
         "email": "ashitosh.wagh@eptura.com"
      }

#### User Permissions Info [GET /users/me/{?selector}]

*'selector' expects permissions value in parameter as mentioned in example.*

The following attribute is required to get user's permissions info: `selector`.

+ Parameters
    + selector (string, `permissions(center(module)%2Crole)%2CsiteAdmin`) ... Selector ID

+ Response 200
    
      {
      "siteAdmin": true,
      "permissions": [
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "copy",
      "name": "Arizona Copy Center",
      "id": 123
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "asset",
      "name": "Asset Center",
      "id": 69
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "asset",
      "name": "AssetTest_Aishwarya",
      "id": 172
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "Austin Löfsjögård Service Request - NON DST",
      "id": 70
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "mail",
      "name": "Austin Mail Center",
      "id": 113
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "move",
      "name": "Austin Move Center",
      "id": 78
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "Austin Reservation Center",
      "id": 141
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "space",
      "name": "Austin Space Center",
      "id": 79
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "visitor",
      "name": "Austin Visitor Center",
      "id": 128
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "Boston Maintenance Center",
      "id": 130
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "mail",
      "name": "California Mail Center",
      "id": 107
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "mail",
      "name": "California Pending Queue",
      "id": 114
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "California Reservation Center",
      "id": 143
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "California Service Center",
      "id": 103
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "visitor",
      "name": "California Visitor Center",
      "id": 146
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "Colorado Maintenance Center",
      "id": 104
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "Colorado Reservation Center",
      "id": 144
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "copy",
      "name": "Copy Center",
      "id": 67
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "mail",
      "name": "Dallas Mail Center",
      "id": 117
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "Dallas Service Request",
      "id": 98
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "fileroom",
      "name": "File Room",
      "id": 80
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "Google Reservation Center",
      "id": 138
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "Graph Reservation Center",
      "id": 148
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "Hawaii Building - Reservation Center",
      "id": 150
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "space",
      "name": "Hawaii Building - Space Center",
      "id": 154
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "copy",
      "name": "Hawaii Building Copy Center",
      "id": 163
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "inventory",
      "name": "Hawaii Building Inventory Center",
      "id": 176
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "mail",
      "name": "Hawaii Building Mail Center",
      "id": 175
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "move",
      "name": "Hawaii Building Move Center",
      "id": 174
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "Hawaii Building Service Request",
      "id": 153
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "visitor",
      "name": "Hawaii Building Visitor Center",
      "id": 173
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "fileroom",
      "name": "Houston File Center",
      "id": 92
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "inventory",
      "name": "Houston Inventory Center",
      "id": 124
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "mail",
      "name": "Houston Mail Center",
      "id": 83
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "move",
      "name": "Houston Move Center",
      "id": 75
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "mail",
      "name": "Houston Pending Queue",
      "id": 71
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "Houston Reservation Center - 24 hour",
      "id": 145
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "Houston Service Request",
      "id": 77
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "space",
      "name": "Houston Space Center",
      "id": 74
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "visitor",
      "name": "Houston Visitor Center",
      "id": 89
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "India Maintenance Center",
      "id": 105
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "visitor",
      "name": "India Visitor Center",
      "id": 139
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "inventory",
      "name": "Inventory Center",
      "id": 73
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "asset",
      "name": "james testing",
      "id": 160
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "copy",
      "name": "james testing copy",
      "id": 161
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "copy",
      "name": "james testing neighborhoods",
      "id": 162
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "copy",
      "name": "London Copy Center",
      "id": 112
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "London Löfsjögård Service Request",
      "id": 76
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "mail",
      "name": "London Mail Center",
      "id": 125
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "move",
      "name": "London Move Center",
      "id": 90
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "London Reservation - Wed Only",
      "id": 149
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "London Reservation Center",
      "id": 95
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "space",
      "name": "London Space Center",
      "id": 81
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "visitor",
      "name": "London Visitor Center",
      "id": 115
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "copy",
      "name": "Maine Copy Center",
      "id": 122
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "mail",
      "name": "Maine Pending Mail Center",
      "id": 102
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "Maine Reservation Center",
      "id": 106
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "Maine Service Request",
      "id": 108
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "visitor",
      "name": "Maine Visitors Center",
      "id": 72
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "asset",
      "name": "New Asset Center",
      "id": 85
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "mail",
      "name": "New York Mail Center",
      "id": 129
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "New York Service Request Center",
      "id": 121
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "space",
      "name": "Pat's Test",
      "id": 142
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "Prajkta's Reservation Center",
      "id": 151
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "space",
      "name": "Prajkta's Space Center",
      "id": 152
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "Reservation Center",
      "id": 82
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "space",
      "name": "Restricted Space Center",
      "id": 140
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "mail",
      "name": "San Antonio Mail Center",
      "id": 118
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "San Antonio Service Request Center",
      "id": 101
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "Service Request",
      "id": 155
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "SiteAdmin4388",
      "id": 170
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "SiteAdmin4388",
      "id": 178
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "SiteAdmin4388",
      "id": 179
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "SiteAdmin8574",
      "id": 171
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "copy",
      "name": "test",
      "id": 134
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "reservation",
      "name": "Test",
      "id": 177
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "asset",
      "name": "Test - Asset Center",
      "id": 132
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "Test Maint Center",
      "id": 131
      }
      },
      {
      "role": "ADMINISTRATOR",
      "center": {
      "module": "maintenance",
      "name": "Test Maintenance Center",
      "id": 116
      }
      }
      ],
      "name": "Admin Wagh",
      "id": 3951
      }

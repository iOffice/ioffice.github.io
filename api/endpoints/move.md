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
                "comments": [
                    {
                        "id": 45,
                        "content": "Your comment here!"
                    }
                ],
                "dateCreated": 1469657150797,
                "id": 4,
                "status": {
                    "code": "sub",
                    "dateCreated": 1185984126540,
                    "name": "In Progress",
                    "id": 10
                }
           }

### Retrieve a Single Move Request [GET]
+ Response 200

    [Move][]


## Edit a Move Request [PUT /move/requests/]

To update a Move Request send JSON with updated values for one or more of the attributes.
+ The following attribute is required to update a Move Request: `id`.

+ Request (application/json)


           {
               "comments": [
                    {
                        "content": "new comment here!"
                    }
               ],
               "id": 4,
               "approved": true,
               "status": {
                    "id": 14
                }
}

+ Response 200

           {
                "comments": [
                    {
                        "id": 81,
                        "content": "new comment here!"
                    }
                ],
                "dateCreated": 1469657150797,
                "id": 4,
                "dateUpdated": 1488473461303,
                "status": {
                    "code": "apr",
                    "dateCreated": 1195932197030,
                    "name": "Approved by Manager",
                    "id": 14
                }
           }



### Remove a Move Request [DELETE]
+ Parameters
    + id (string) ... ID of the User
+ Response 200

           {
                "response": "Successfully removed"
           }


## Move Collection [/move/requests]

List of all Move Requests

+ Model (application/json)
    JSON representation of the Move Collection resource.

    + Body

            [
              {
                "comments": [
                    {
                      "id": 47,
                      "content": "Word."
                    }
                ],
                "dateCreated": 1469657281923,
                "id": 6,
                "status": {
                  "code": "sub",
                  "dateCreated": 1185984126540,
                  "name": "In Progress",
                  "id": 10
                }
              },
              {
                "comments": [
                  {
                    "id": 48,
                    "content": "Word 2 ur mother."
                  }
                ],
                "dateCreated": 1469657337973,
                "id": 7,
                "status": {
                  "code": "sub",
                  "dateCreated": 1185984126540,
                  "name": "Pending",
                  "id": 15
                }
              },
              {
                "comments": [
                  {
                    "id": 51,
                    "content": "Word 'em up!"
                  }
                ],
                "dateCreated": 1469657800263,
                "id": 8,
                "status": {
                  "code": "sub",
                  "dateCreated": 1185984126540,
                  "name": "Approved by Manager",
                  "id": 14
                }
              },
            ]


### List of all Move Requests [GET]

+ Response 200

    [Move Collection][]


### Create a Move Request [POST /move/requests]
The following attribute is required to update a Move Request: status `id`.

+ Request (application/json)

             {
                "comments": [
             {
                "content": "this is a new move request"
             }
                ],
                "status": {
                "id": 13
                }
            }

+ Response 201


### Get Approval of a Move Request [GET /move/requests//{{id}//?selector=approved]

Get boolean value if Move Request {id} is approved

+ Response 200 (application/json)

            {
                "approved": "true",
                "id": 6,
        }

### Get Approval of All Move Requests [GET /move/requests/?selector=approved]

Get boolean values of all Move Request approvals

+ Response 200 (application/json)

            [
              {
                "approved": true,
                "id": 1
              },
              {
                "approved": true,
                "id": 2
              },
              {
                "approved": false,
                "id": 3
              },
              {
                "approved": true,
                "id": 4
              },
              {
                "approved": false,
                "id": 6
              }
            ]


## Get Move Status Ids [/move/statuses]

Get move status ids

### Retrieve Move Status Ids [GET]

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


## Get Move Request by Status Id [/move/requests/?statusId={{id}]

Get move request by status id

### Retrieve Move Request by Status Id [GET]

+ Response 200 (application/json)

            [
             {
                 "comments": [
                   {
                     "id": 83,
                     "content": "newer comment here!"
                   }
                 ],
                 "dateCreated": 1488475111830,
                 "id": 26,
                 "status": {
                   "code": "apr",
                   "dateCreated": 1195932197030,
                   "name": "Approved by Manager",
                   "id": 14
                 }
               },
               {
                 "comments": [
                   {
                     "id": 84,
                     "content": "newwer comment here!"
                   }
                 ],
                 "dateCreated": 1488475131627,
                 "id": 27,
                 "status": {
                   "code": "apr",
                   "dateCreated": 1195932197030,
                   "name": "Approved by Manager",
                   "id": 14
                 }
               }
             ]

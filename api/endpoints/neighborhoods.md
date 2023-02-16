# Group Neighborhoods
Neighborhoods-related resources of *iOffice API*

## Neighborhoods [/neighborhoods{?centerId}]
Collection of all Neighborhoods

### Retrieve All Neighborhoods [GET /neighborhoods{?centerId}]
This API returns list of all neighborhoods in particular module

The following attributes are required to get list of neighborhoods: `centerId`.

+ Parameters
    + centerId (int, `79`) ... Center Id

+ Response 200

           [
               {
                   "owner": {
                       "floorWarden": false,
                       "lastName": "Azad",
                       "color": "#76C7DA",
                       "userName": "sazad",
                       "passwordResetAttemptsRemaining": 3,
                       "specialNeeds": false,
                       "dateUpdated": 1646943255737,
                       "firstName": "Sabera",
                       "custom10": "33",
                       "custom02": "Dog",
                       "dateCreated": 1611003598567,
                       "custom04": "3",
                       "custom03": "1611269672207",
                       "custom06": "1610985600000",
                       "custom05": "- 3 is Jan 21 and 4 is 6 pm.\n- 6 is 10 am and 7 is Jan 11.\n- 8 should show Jan 11 and 12 pm\n",
                       "custom08": "1610388000000",
                       "name": "Sabera Azad",
                       "custom07": "1610405721816",
                       "custom09": "Deparment",
                       "id": 3439,
                       "userType": {
                           "dateCreated": 1428954498147,
                           "name": "Employee",
                           "id": 1,
                           "dateUpdated": 1630594939190
                       },
                       "email": "sabera.azad@spaceiq.com"
                       },
                       "borderColor": "#CCCCCC",
                       "code": "Sabera's neighborhood",
                       "color": "#CCCCCC",
                       "fillOpacity": 0.5,
                       "center": {
                           "name": "Austin Space Center",
                           "id": 79
                       },
                       "borderWeight": 2,
                       "description": "Check for insight report",
                       "dateUpdated": 1631130028094,
                       "borderOpacity": 0.5,
                       "dateCreated": 1629231924173,
                       "name": "Neighborhood #1",
                       "id": 1
                   }
               }
           ]

### Create a Neighborhoods [PUT]
The following attributes are required to create a Neighborhoods

+ Request (application/json)

           {
               "name": "New Neighborhood_QA",
               "center": {
               "id": 79
                },
               "color": "#CCCCCC",
               "borderWeight": 2,
               "borderColor": "#CCCCCC",
               "borderOpacity": 0.5,
               "fillOpacity": 0.5,
               "effectiveStartDate": 1676451692488,
               "code": "QA_Test"
           }

+ Response 201
   + Body

           {
               "borderColor": "#CCCCCC",
               "borderOpacity": 0.5,
               "code": "QA_Test",
               "dateCreated": 1676451854974,
               "color": "#CCCCCC",
               "fillOpacity": 0.5,
               "center": {
                   "name": "Austin Space Center",    
                   "id": 79
               },
               "name": "New Neighborhood_QA",
               "borderWeight": 2,
               "id": 248
           }

### Edit a Neighborhoods [POST]

+ Parameters

+ Request (application/json)

          {
              "code": "NWNBHD_550118577",
              "color": "#CCCCCC",
              "name": "Neighborhood1159400",
              "id": 210
          }

+ Response 200
   + Body

          { 
               "borderColor": "#CCCCCC",
               "borderOpacity": 0.5,
               "code": "NWNBHD_550118577",
               "dateCreated": 1657594121936,
               "color": "#CCCCCC",
               "fillOpacity": 0.5,
               "center": {
                   "name": "Austin Space Center",
                   "id": 79
              },
              "name": "Neighborhood1159400",
              "borderWeight": 2,
              "id": 210,
              "dateUpdated": 1676463879764
          }

### Remove a Neighborhoods [DELETE /neighborhoods/{id}]
+ Parameters
   + id (int) ... ID of the Neighborhoods
  
+ Response 200

        {
            {
                "response": "Successfully removed"
            }
        }

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

## Sections [/neighborhoods/sections]
Collection of all Neighborhood Sections

### Retrieve All Sections [GET /neighborhoods/sections]
This API returns list of all sections from all neighbourhoods

+ Response 200

        [
            {
               "borderColor": "#30e916",
               "borderOpacity": 0.5,
               "dateCreated": 1630004885420,
               "color": "#30e916",
               "fillOpacity": 0.5,
               "name": "Section in Other Building",
               "coordinates": "[{\"lng\":9.772848956794661,\"lat\":-4.961538182748129},{\"lng\":10.062404180897722,\"lat\":-4.967278683995653},{\"lng\":10.351959405000784,\"lat\":-4.973019185243178},{\"lng\":10.641514629103845,\"lat\":-4.978759686490703},{\"lng\":10.931069853206907,\"lat\":-4.984500187738227},{\"lng\":11.220625077309968,\"lat\":-4.990240688985752},{\"lng\":11.51018030141303,\"lat\":-4.995981190233277},{\"lng\":11.799735525516091,\"lat\":-5.001721691480801},{\"lng\":12.089290749619153,\"lat\":-5.007462192728326},{\"lng\":12.089290749619153,\"lat\":-5.315326794173572},{\"lng\":12.089290749619153,\"lat\":-5.623191395618818},{\"lng\":12.089290749619153,\"lat\":-5.931055997064064},{\"lng\":12.089290749619153,\"lat\":-6.23892059850931},{\"lng\":12.089290749619153,\"lat\":-6.546785199954556},{\"lng\":12.089290749619153,\"lat\":-6.854649801399802},{\"lng\":12.089290749619153,\"lat\":-7.162514402845048},{\"lng\":12.089290749619153,\"lat\":-7.470379004290294},{\"lng\":11.80981953829572,\"lat\":-7.484660587032749},{\"lng\":11.530348326972288,\"lat\":-7.498942169775205},{\"lng\":11.250877115648855,\"lat\":-7.513223752517661},{\"lng\":10.971405904325422,\"lat\":-7.527505335260116},{\"lng\":10.69193469300199,\"lat\":-7.541786918002572},{\"lng\":10.412463481678557,\"lat\":-7.5560685007450274},{\"lng\":10.132992270355125,\"lat\":-7.570350083487483},{\"lng\":9.853521059031692,\"lat\":-7.584631666229939},{\"lng\":9.843437046252063,\"lat\":-7.256744980794712},{\"lng\":9.833353033472434,\"lat\":-6.928858295359486},{\"lng\":9.823269020692805,\"lat\":-6.60097160992426},{\"lng\":9.813185007913177,\"lat\":-6.273084924489034},{\"lng\":9.803100995133548,\"lat\":-5.945198239053807},{\"lng\":9.793016982353919,\"lat\":-5.617311553618581},{\"lng\":9.78293296957429,\"lat\":-5.289424868183355},{\"lng\":9.772848956794661,\"lat\":-4.961538182748129}]",
               "borderWeight": 2,
               "id": 2,
               "floor": {
                   "area": 16978.2167,
                   "dateCreated": 1629985917187,
                   "drawingAvailable": true,
                   "interiorGross": 0.0,
                   "name": "Other Floor",
                   "leaseArea": 0.0,
                   "id": 64,
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
                           "city": "Providence",
                           "street": "40 N Main St",
                           "postalCode": "02903",
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
                                "code": "RI",
                                "name": "Rhode Island",
                                "id": 57,
                                "categoryName": "state"
                           }
                       },
                       "dateCreated": 1629985886053,
                       "metric": false,
                       "name": "Other Neighborhoods",
                       "location": {},
                       "revitLink": "",
                       "id": 80,
                       "dateUpdated": 1687504772607,
                       "costCenters": []
                   },
                   "dateUpdated": 1629986705960
               },
               "dateUpdated": 1629987061413
            },
            .
            .
            .
        ]

### Create Section [PUT /neighborhoods/sections]
This API creates section for particular existing neighbourhood

*The 'Room ID', 'Floor ID', 'Neighbourhood ID', 'Coordinates' and 'Name' is compulsory*

+ Request (application/json)

      {
         "borderColor": null,
         "borderOpacity": null,
         "rooms": [
            {
               "id": 2489
            }
         ],
         "color": null,
         "fillOpacity": null,
         "name": "Section1169276",
         "coordinates": "[{\"lng\":2.479061096191407,\"lat\":-3.8195261967366703},{\"lng\":2.6853938140869147,\"lat\":-3.8195261967366703},{\"lng\":2.891726531982423,\"lat\":-3.8195261967366703},{\"lng\":3.098059249877931,\"lat\":-3.8195261967366703},{\"lng\":3.3043919677734386,\"lat\":-3.8195261967366703},{\"lng\":3.3043919677734386,\"lat\":-3.6495981562312148},{\"lng\":3.3043919677734386,\"lat\":-3.4796701157257597},{\"lng\":3.3043919677734386,\"lat\":-3.3097420752203046},{\"lng\":3.3043919677734386,\"lat\":-3.139814034714849},{\"lng\":3.098059249877931,\"lat\":-3.139814034714849},{\"lng\":2.891726531982423,\"lat\":-3.139814034714849},{\"lng\":2.6853938140869147,\"lat\":-3.139814034714849},{\"lng\":2.479061096191407,\"lat\":-3.139814034714849},{\"lng\":2.479061096191407,\"lat\":-3.3097420752203046},{\"lng\":2.479061096191407,\"lat\":-3.4796701157257597},{\"lng\":2.479061096191407,\"lat\":-3.6495981562312148},{\"lng\":2.479061096191407,\"lat\":-3.8195261967366703}]",
         "borderWeight": null,
         "neighborhood": {
            "id": 6299
         },
         "floor": {
            "id": 61
         }
      }


+ Response 201

  {
  "rooms": [
  {
  "area": 60.94,
  "nameWithDescription": "2053",
  "reservable": false,
  "name": "2053",
  "description": "",
  "id": 50688,
  "floor": {
  "name": "Neighborhood Floor 1",
  "id": 1286,
  "building": {
  "code": "DO NOT REMOVE",
  "name": "Neighborhoods",
  "id": 267
  }
  },
  "type": {
  "color": {
  "red": 117,
  "green": 197,
  "blue": 217
  },
  "name": "CONF",
  "id": 3,
  "spaceTypeGroup": {
  "name": "We Spaces",
  "id": 3
  }
  },
  "users": []
  }
  ],
  "allUsers": [],
  "coordinates": "[{\"lng\":10.091108825683596,\"lat\":-3.739615546108873},{\"lng\":10.2076872253418,\"lat\":-3.739615546108873},{\"lng\":10.324265625000002,\"lat\":-3.739615546108873},{\"lng\":10.440844024658205,\"lat\":-3.739615546108873},{\"lng\":10.557422424316407,\"lat\":-3.739615546108873},{\"lng\":10.557422424316407,\"lat\":-3.588979552610195},{\"lng\":10.557422424316407,\"lat\":-3.438343559111517},{\"lng\":10.557422424316407,\"lat\":-3.2877075656128385},{\"lng\":10.557422424316407,\"lat\":-3.13707157211416},{\"lng\":10.440844024658205,\"lat\":-3.13707157211416},{\"lng\":10.324265625000002,\"lat\":-3.13707157211416},{\"lng\":10.2076872253418,\"lat\":-3.13707157211416},{\"lng\":10.091108825683596,\"lat\":-3.13707157211416},{\"lng\":10.091108825683596,\"lat\":-3.2877075656128385},{\"lng\":10.091108825683596,\"lat\":-3.438343559111517},{\"lng\":10.091108825683596,\"lat\":-3.588979552610195},{\"lng\":10.091108825683596,\"lat\":-3.739615546108873}]",
  "name": "Test Section 1",
  "neighborhood": {
  "borderColor": "#CCCCCC",
  "borderOpacity": 0.5,
  "code": "NWNBHD_835903",
  "color": "#CCCCCC",
  "fillOpacity": 0.5,
  "name": "Neighborhood7023126",
  "borderWeight": 2,
  "id": 36
  },
  "id": 231,
  "floor": {
  "name": "Neighborhood Floor 1",
  "id": 1286,
  "building": {
  "code": "DO NOT REMOVE",
  "metric": false,
  "centers": [
  {
  "module": "move",
  "name": "Austin Move Center",
  "id": 78
  },
  {
  "module": "maintenance",
  "name": "Houston Service Request",
  "id": 77
  },
  {
  "module": "move",
  "name": "London Move Center",
  "id": 90
  },
  {
  "module": "move",
  "name": "Houston Move Center",
  "id": 75
  },
  {
  "module": "maintenance",
  "name": "Service Request",
  "id": 155
  },
  {
  "module": "space",
  "name": "Austin Space Center",
  "id": 79
  }
  ],
  "name": "Neighborhoods",
  "id": 267
  }
  }
  }


### Update Section [POST /neighborhoods/sections]
This API creates section for particular existing neighbourhood

*The 'Room ID', 'Floor ID', 'Neighbourhood ID', 'Section ID', 'Coordinates' and 'Name' is compulsory*

+ Request (application/json)

      {
         "rooms": [
            {
               "id": 50652
            }
         ],
         "allUsers": [],
         "coordinates": "[{\"lng\":6.230826232910156,\"lat\":-2.2629213405391497},{\"lng\":6.397958633422851,\"lat\":-2.2629213405391497},{\"lng\":6.5650910339355475,\"lat\":-2.2629213405391497},{\"lng\":6.732223434448244,\"lat\":-2.2629213405391497},{\"lng\":6.899355834960939,\"lat\":-2.2629213405391497},{\"lng\":6.899355834960939,\"lat\":-2.0597826771027448},{\"lng\":6.899355834960939,\"lat\":-1.8566440136663394},{\"lng\":6.899355834960939,\"lat\":-1.653505350229934},{\"lng\":6.899355834960939,\"lat\":-1.4503666867935288},{\"lng\":6.732223434448244,\"lat\":-1.4503666867935288},{\"lng\":6.5650910339355475,\"lat\":-1.4503666867935288},{\"lng\":6.397958633422851,\"lat\":-1.4503666867935288},{\"lng\":6.230826232910156,\"lat\":-1.4503666867935288},{\"lng\":6.230826232910156,\"lat\":-1.653505350229934},{\"lng\":6.230826232910156,\"lat\":-1.8566440136663394},{\"lng\":6.230826232910156,\"lat\":-2.0597826771027448},{\"lng\":6.230826232910156,\"lat\":-2.2629213405391497}]",
         "name": "Section Name 1",
         "neighborhood": {
            "id": 36
         },
         "id": 232,
         "floor": {
            "id": 1286
         }
      }


+ Response 200

  {
  "rooms": [
  {
  "area": 60.94,
  "nameWithDescription": "2053",
  "reservable": false,
  "name": "2053",
  "description": "",
  "id": 50688,
  "floor": {
  "name": "Neighborhood Floor 1",
  "id": 1286,
  "building": {
  "code": "DO NOT REMOVE",
  "name": "Neighborhoods",
  "id": 267
  }
  },
  "type": {
  "color": {
  "red": 117,
  "green": 197,
  "blue": 217
  },
  "name": "CONF",
  "id": 3,
  "spaceTypeGroup": {
  "name": "We Spaces",
  "id": 3
  }
  },
  "users": []
  }
  ],
  "allUsers": [],
  "coordinates": "[{\"lng\":10.091108825683596,\"lat\":-3.739615546108873},{\"lng\":10.2076872253418,\"lat\":-3.739615546108873},{\"lng\":10.324265625000002,\"lat\":-3.739615546108873},{\"lng\":10.440844024658205,\"lat\":-3.739615546108873},{\"lng\":10.557422424316407,\"lat\":-3.739615546108873},{\"lng\":10.557422424316407,\"lat\":-3.588979552610195},{\"lng\":10.557422424316407,\"lat\":-3.438343559111517},{\"lng\":10.557422424316407,\"lat\":-3.2877075656128385},{\"lng\":10.557422424316407,\"lat\":-3.13707157211416},{\"lng\":10.440844024658205,\"lat\":-3.13707157211416},{\"lng\":10.324265625000002,\"lat\":-3.13707157211416},{\"lng\":10.2076872253418,\"lat\":-3.13707157211416},{\"lng\":10.091108825683596,\"lat\":-3.13707157211416},{\"lng\":10.091108825683596,\"lat\":-3.2877075656128385},{\"lng\":10.091108825683596,\"lat\":-3.438343559111517},{\"lng\":10.091108825683596,\"lat\":-3.588979552610195},{\"lng\":10.091108825683596,\"lat\":-3.739615546108873}]",
  "name": "Updated Section",
  "neighborhood": {
  "borderColor": "#CCCCCC",
  "borderOpacity": 0.5,
  "code": "NWNBHD_835903",
  "color": "#CCCCCC",
  "fillOpacity": 0.5,
  "name": "Neighborhood7023126",
  "borderWeight": 2,
  "id": 36
  },
  "id": 231,
  "floor": {
  "name": "Neighborhood Floor 1",
  "id": 1286,
  "building": {
  "code": "DO NOT REMOVE",
  "metric": false,
  "centers": [
  {
  "module": "move",
  "name": "Austin Move Center",
  "id": 78
  },
  {
  "module": "maintenance",
  "name": "Houston Service Request",
  "id": 77
  },
  {
  "module": "move",
  "name": "London Move Center",
  "id": 90
  },
  {
  "module": "move",
  "name": "Houston Move Center",
  "id": 75
  },
  {
  "module": "maintenance",
  "name": "Service Request",
  "id": 155
  },
  {
  "module": "space",
  "name": "Austin Space Center",
  "id": 79
  }
  ],
  "name": "Neighborhoods",
  "id": 267
  }
  }
  }


### Delete Section [DELETE /neighborhoods/Sections/{sectionId}]
This API deletes the Section from particular neighbourhood

The following attributes are required to get list of neighborhoods: `sectionId`.

+ Parameters
  + sectionId (int, `231`) ... Section Id

+ Response 200

           {"response":"Successfully removed"}
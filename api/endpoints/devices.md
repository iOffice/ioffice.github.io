# Group Devices

## Devices [/devices]
Devices related resources of *iOffice API*

+ Model (application/json)
    JSON representation of the Category	Resource

### Retrieve Collection of Devices [GET]
+ Parameters
	+ deviceType (optinal, string, `VISITOR_PANEL`) ... Type of Devices to Fetch
	+ selector (`deviceStatus(datePaired%2CdateUnpaired%2CdateUpdated%2CdeviceId%2CdeviceType
	%2ClastDiscoverableDate%2ClastPairedByUserId%2ClastUnpairedByUserId%2ClastUpdatedByUserId)%2CdeviceType
	%2Csettings(backgroundImage%2CbypassPicture%2CcenterId%2CdisableFields%2CdisplayFloorViewer%2ChideGraphic
	%2Ctouchless%2CtransparentCard)`)
	
+ Response 200

	[
	  {
		"deviceType": "VISITOR_PANEL",
		"settings": {
		  "displayFloorViewer": true,
		  "centerId": 89,
		  "touchless": true,
		  "backgroundImage": "",
		  "bypassPicture": false,
		  "transparentCard": false,
		  "disableFields": [],
		  "hideGraphic": true
		},
		"name": "Jessica's ipad",
		"id": 190,
		"deviceStatus": {
		  "deviceType": "VISITOR_PANEL",
		  "lastDiscoverableDate": 1633018243076,
		  "lastPairedByUserId": 1,
		  "lastUnpairedByUserId": 1,
		  "lastUpdatedByUserId": 1,
		  "dateUnpaired": 1633017816146,
		  "deviceId": 190,
		  "datePaired": 1633018252073,
		  "dateUpdated": 1633018252073
		}
	  },
	  {
		"deviceType": "VISITOR_PANEL",
		"settings": {
		  "displayFloorViewer": true,
		  "centerId": 128,
		  "touchless": false,
		  "backgroundImage": "",
		  "bypassPicture": false,
		  "transparentCard": false,
		  "disableFields": [],
		  "hideGraphic": false
		},
		"name": "iPad Sergeo's",
		"id": 196,
		"deviceStatus": {
		  "deviceType": "VISITOR_PANEL",
		  "lastDiscoverableDate": 1668605078366,
		  "lastPairedByUserId": 3476,
		  "lastUnpairedByUserId": 3476,
		  "lastUpdatedByUserId": 3951,
		  "dateUnpaired": 1652777231223,
		  "deviceId": 196,
		  "datePaired": 1652777074646,
		  "dateUpdated": 1668605078366
		}
	  }
	]
		
### Retrieve Single Device [GET /devices/{id}]
+ Parameters
    + id (int, `234`) ... ID of the Device
    + selector (`deviceStatus(datePaired%2CdatePolled%2CdateUnpaired%2CdateUpdated%2CdeviceId%2CdeviceType
	%2ClastDiscoverableDate%2ClastPairedByUserId%2ClastUnpairedByUserId%2ClastUpdatedByUserId)%2CdeviceType
	%2CfloorMarker(floor(building))%2Csettings(campus%2ClegendMinimized%2CmapOrientation(bearing%2Ccenter(lat%2Clng)%2Cpitch%2Czoom)
	%2Cmodes%2CshowSensorData%2CsiteLogo)`)

+ Response 200
			{
			  "deviceType": "WAYFINDING",
			  "settings": {
				"showSensorData": true,
				"modes": [

				],
				"campus": [

				],
				"legendMinimized": false,
				"siteLogo": true,
				"mapOrientation": {
				  "bearing": 0.0,
				  "center": {
					"lng": 6.3446044921875,
					"lat": -3.850552816561631
				  },
				  "zoom": 6.268508237549647,
				  "pitch": 0.0
				}
			  },
			  "floorMarker": {
				"id": 650,
				"floor": {
				  "name": "Ahmedfloor",
				  "id": 1293,
				  "building": {
					"code": "111",
					"name": "Ahmed Tower",
					"id": 182
				  }
				}
			  },
			  "name": "WAYFINDING Device",
			  "id": 234,
			  "deviceStatus": {
				"deviceType": "WAYFINDING",
				"lastDiscoverableDate": 1660639596326,
				"lastPairedByUserId": 3476,
				"lastUnpairedByUserId": 3476,
				"lastUpdatedByUserId": 3476,
				"dateUnpaired": 1660639595556,
				"deviceId": 234,
				"datePaired": 1660639579480,
				"dateUpdated": 1660639596326
			  }
			}
			
### Create Device [POST /devices/create]
+ Parameters
	+ selector (`deviceStatus(datePaired%2CdateUnpaired%2CdateUpdated%2CdeviceId%2ClastDiscoverableDate%2ClastPairedByUserId%2ClastUnpairedByUserId%2ClastUpdatedByUserId)%2CdeviceType%2Cenabled%2CfloorMarker(description%2Cposition(x%2Cy)%2Ctype(description%2ChexColor%2CiconUid%2CmarkerTypeGroup(visibleByDefault)))%2Csettings`)

+ Request (application/json)
			{
			  "device": {
				"deviceType": "WAYFINDING",
				"enabled": true,
				"name": "WAYFINDING Device",
				"settings": {
				  "settingsType": "WAYFINDING"
				}
			  },
			  "floor": {
				"id": 3814
			  },
			  "position": {
				"x": 1903.8198380566669,
				"y": 688.6639676114645
			  }
			}
			
+ Response 201
			{
			  "deviceType": "WAYFINDING",
			  "settings": {

			  },
			  "floorMarker": {
				"position": {
				  "x": 1903.82,
				  "y": 688.66
				},
				"id": 653,
				"type": {
				  "hexColor": "BEA5FA",
				  "name": "WAYFINDING",
				  "description": "",
				  "iconUid": "ios7:home",
				  "markerTypeGroup": {
					"code": "$@IOFFICE_DEVICES@$",
					"visibleByDefault": true,
					"name": "iOFFICE Kiosk Devices",
					"id": 18
				  },
				  "id": 19
				}
			  },
			  "name": "WAYFINDING Device",
			  "id": 239,
			  "enabled": true
			}
			
### Update Single Device [PUT /devices/{id}]
+ Parameters
    + id (int, `80`) ... ID of the Device
	
+ Request (application/json)
	{
	  "name": "center device",
	  "settings": {
		"showSensorData": true,
		"modes": [

		],
		"campus": [

		],
		"legendMinimized": false,
		"siteLogo": true,
		"mapOrientation": {
		  "bearing": -90,
		  "center": {
			"lng": 8.480550201386677,
			"lat": -3.8055252372980846
		  },
		  "pitch": 60,
		  "zoom": 5.473784419746073
		},
		"settingsType": "WAYFINDING"
	  }
	}

+ Response 200
			{
			  "settings": {
				"modes": [

				],
				"settingsType": "WAYFINDING",
				"campus": [

				],
				"mapOrientation": {
				  "bearing": -90.0,
				  "center": {
					"lng": 8.480550201386677,
					"lat": -3.8055252372980846
				  },
				  "zoom": 5.473784419746073,
				  "pitch": 60.0
				}
			  },
			  "dateCreated": 1561133232940,
			  "name": "center device",
			  "id": 80,
			  "dateUpdated": 1670868716275
			}

### Delete Device [DELETE /devices/{id}]
+ Parameters
    + id (int, `123`) ... ID of the Device

+ Response 200
			{"response":"Successfully removed"}


### Retrieve List Of Devices in Floor [GET]

+ Parameters
    + deviceType (optinal, `WAYFINDING`) ... If included, query will return list of devices of given device type
	+ floorId (optional, int, `1293`) ... If included, query will return list of devices in floor
	+ selector (optional, `deviceStatus(datePaired%2CdatePolled%2CdateUnpaired%2CdateUpdated%2CdeviceId%2CdeviceType%2ClastDiscoverableDate%2ClastPairedByUserId%2ClastUnpairedByUserId%2ClastUpdatedByUserId)%2CdeviceType%2CfloorMarker(floor(building))%2Csettings(campus%2ClegendMinimized%2CmapOrientation(bearing%2Ccenter(lat%2Clng)%2Cpitch%2Czoom)%2Cmodes%2CshowSensorData%2CsiteLogo`)
    		
+ Response 200
			[
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [
					85,
					106,
					43,
					80
				  ],
				  "legendMinimized": true,
				  "siteLogo": false,
				  "mapOrientation": {
					"bearing": 16.115099910008443,
					"center": {
					  "lng": 3.2505541257661434,
					  "lat": -8.526282186004707
					},
					"zoom": 7.255246014229159,
					"pitch": 38.99999999999997
				  }
				},
				"floorMarker": {
				  "id": 129,
				  "floor": {
					"name": "05",
					"id": 37,
					"building": {
					  "code": "HT1",
					  "name": "Houston Tower 1",
					  "id": 82
					}
				  }
				},
				"name": "Ray's Device",
				"id": 56,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1561388652316,
				  "lastPairedByUserId": 1,
				  "lastUnpairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1561388540990,
				  "deviceId": 56,
				  "datePaired": 1561388698026,
				  "dateUpdated": 1561388698026
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": false,
				  "mapOrientation": {
					"bearing": -178.48873907526757,
					"center": {
					  "lng": 15.237046421842933,
					  "lat": -4.94427305388102
					},
					"zoom": 5.039302194252716,
					"pitch": 36.000000000000014
				  }
				},
				"floorMarker": {
				  "id": 130,
				  "floor": {
					"name": "05",
					"id": 37,
					"building": {
					  "code": "HT1",
					  "name": "Houston Tower 1",
					  "id": 82
					}
				  }
				},
				"name": "Test 2",
				"id": 57,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1572889885396,
				  "lastPairedByUserId": 1,
				  "lastUnpairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1562159912543,
				  "deviceId": 57,
				  "datePaired": 1561470229940,
				  "dateUpdated": 1572889885396
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [
					80
				  ],
				  "legendMinimized": true,
				  "siteLogo": false,
				  "mapOrientation": {
					"bearing": 1.4457481112623327,
					"center": {
					  "lng": 4.984510756294071,
					  "lat": -8.084774906843208
					},
					"zoom": 5.8320941381670695,
					"pitch": 4.500000000000011
				  }
				},
				"floorMarker": {
				  "id": 132,
				  "floor": {
					"name": "05",
					"id": 37,
					"building": {
					  "code": "HT1",
					  "name": "Houston Tower 1",
					  "id": 82
					}
				  }
				},
				"name": "Test 3",
				"id": 59,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1572885630030,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 59,
				  "dateUpdated": 1572885630030
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": true,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": -56.30937683644004,
					"center": {
					  "lng": 5.603009449229944,
					  "lat": -6.439437033737391
					},
					"zoom": 7.155204973562053,
					"pitch": 42.0
				  }
				},
				"floorMarker": {
				  "id": 133,
				  "floor": {
					"name": "05",
					"id": 37,
					"building": {
					  "code": "HT1",
					  "name": "Houston Tower 1",
					  "id": 82
					}
				  }
				},
				"name": "Test 4",
				"id": 60,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1572885501560,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 60,
				  "dateUpdated": 1572885501560
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": true,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 20.799999999999727,
					"center": {
					  "lng": 9.947040455664364,
					  "lat": -5.00768729736734
					},
					"zoom": 5.08747883585588,
					"pitch": 51.5
				  }
				},
				"floorMarker": {
				  "id": 137,
				  "floor": {
					"name": "05",
					"id": 37,
					"building": {
					  "code": "HT1",
					  "name": "Houston Tower 1",
					  "id": 82
					}
				  }
				},
				"name": "Test 5",
				"id": 64,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1582232988173,
				  "lastPairedByUserId": 1,
				  "lastUnpairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1561073381106,
				  "deviceId": 64,
				  "datePaired": 1561047483876,
				  "dateUpdated": 1582232988173
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": true,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"center": {
					  "lng": 13.420748082710361,
					  "lat": -6.8383613477449074
					},
					"zoom": 5.100358766418762,
					"pitch": 43.500000000000014
				  }
				},
				"floorMarker": {
				  "id": 138,
				  "floor": {
					"name": "05",
					"id": 37,
					"building": {
					  "code": "HT1",
					  "name": "Houston Tower 1",
					  "id": 82
					}
				  }
				},
				"name": "Test 6",
				"id": 65,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1595873431960,
				  "lastUpdatedByUserId": 1491,
				  "deviceId": 65,
				  "dateUpdated": 1595873431960
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 166,
				  "floor": {
					"name": "01",
					"id": 1088,
					"building": {
					  "code": "111",
					  "name": "iOFFICE HQ",
					  "id": 128
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 72,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1583363712076,
				  "lastPairedByUserId": 1,
				  "lastUnpairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1561074712520,
				  "deviceId": 72,
				  "datePaired": 1561073196670,
				  "dateUpdated": 1583363712076
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 167,
				  "floor": {
					"name": "20",
					"id": 12,
					"building": {
					  "code": "AUS",
					  "name": "Austin",
					  "id": 80
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 73,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1618859694570,
				  "lastPairedByUserId": 1,
				  "lastUnpairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1561493875476,
				  "deviceId": 73,
				  "datePaired": 1561493864293,
				  "dateUpdated": 1618859694570
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 171,
				  "floor": {
					"name": "02",
					"id": 1066,
					"building": {
					  "code": "ALK",
					  "name": "Alaska",
					  "id": 106
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 77,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1561130090626,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 77,
				  "dateUpdated": 1561130090626
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": -90.0,
					"center": {
					  "lng": 8.480550201386677,
					  "lat": -3.8055252372980846
					},
					"zoom": 5.473784419746073,
					"pitch": 60.0
				  }
				},
				"floorMarker": {
				  "id": 174,
				  "floor": {
					"name": "01",
					"id": 1065,
					"building": {
					  "code": "ALK",
					  "name": "Alaska",
					  "id": 106
					}
				  }
				},
				"name": "center device",
				"id": 80,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1603494032976,
				  "lastPairedByUserId": 1,
				  "lastUnpairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1603494031370,
				  "deviceId": 80,
				  "datePaired": 1603494038940,
				  "dateUpdated": 1603494038940
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"center": {
					  "lng": 5.674365768849839,
					  "lat": -3.976168073150049
					},
					"zoom": 5.473784419746073,
					"pitch": 60.0
				  }
				},
				"floorMarker": {
				  "id": 175,
				  "floor": {
					"name": "01",
					"id": 1065,
					"building": {
					  "code": "ALK",
					  "name": "Alaska",
					  "id": 106
					}
				  }
				},
				"name": "far right device",
				"id": 81,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1572466841260,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 81,
				  "dateUpdated": 1572466841260
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"center": {
					  "lng": 8.480550201389747,
					  "lat": -3.8055252372659822
					},
					"zoom": 5.473784419746073,
					"pitch": 60.0
				  }
				},
				"floorMarker": {
				  "id": 176,
				  "floor": {
					"name": "01",
					"id": 1065,
					"building": {
					  "code": "ALK",
					  "name": "Alaska",
					  "id": 106
					}
				  }
				},
				"name": "far left device",
				"id": 82,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1572467356076,
				  "lastPairedByUserId": 1,
				  "lastUnpairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1561134789206,
				  "deviceId": 82,
				  "datePaired": 1561133348400,
				  "dateUpdated": 1572467356076
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 178,
				  "floor": {
					"name": "D10",
					"id": 1038,
					"building": {
					  "code": "CAL",
					  "name": "California",
					  "id": 91
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 84,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1575396375146,
				  "lastPairedByUserId": 1,
				  "lastUnpairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1561156582180,
				  "deviceId": 84,
				  "datePaired": 1575396382540,
				  "dateUpdated": 1575396382540
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 179,
				  "floor": {
					"name": "02",
					"id": 1066,
					"building": {
					  "code": "ALK",
					  "name": "Alaska",
					  "id": 106
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 85,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1561156616326,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 85,
				  "dateUpdated": 1561156616326
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 180,
				  "floor": {
					"name": "02",
					"id": 1066,
					"building": {
					  "code": "ALK",
					  "name": "Alaska",
					  "id": 106
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 86,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1561156720283,
				  "lastPairedByUserId": 1,
				  "lastUnpairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1561156719516,
				  "deviceId": 86,
				  "datePaired": 1561156653706,
				  "dateUpdated": 1561156720283
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": -90.0,
					"center": {
					  "lng": 7.992240200991091,
					  "lat": -3.6520659821089083
					},
					"zoom": 5.948613209125885,
					"pitch": 60.0
				  }
				},
				"floorMarker": {
				  "id": 181,
				  "floor": {
					"name": "03",
					"id": 1093,
					"building": {
					  "code": "ALK",
					  "name": "Alaska",
					  "id": 106
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 87,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1561156729760,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 87,
				  "datePaired": 1561156739716,
				  "dateUpdated": 1561156739716
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 196,
				  "floor": {
					"name": "07",
					"id": 34,
					"building": {
					  "code": "LON",
					  "name": "London",
					  "id": 86
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 97,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1561480494583,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 97,
				  "datePaired": 1561480494913,
				  "dateUpdated": 1561480494913
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 208,
				  "floor": {
					"name": "Wyoming",
					"id": 1054,
					"building": {
					  "name": "Houston Tower 3",
					  "id": 85
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 107,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1593116572413,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 107,
				  "dateUpdated": 1593116572413
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": true,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": -125.1999999999994,
					"center": {
					  "lng": 75.91540458196755,
					  "lat": -22.229372176849182
					},
					"zoom": 4.1,
					"pitch": 60.0
				  }
				},
				"floorMarker": {
				  "id": 209,
				  "floor": {
					"name": "Wyoming",
					"id": 1054,
					"building": {
					  "name": "Houston Tower 3",
					  "id": 85
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 108,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1561494415653,
				  "lastPairedByUserId": 1,
				  "lastUnpairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1561494414966,
				  "deviceId": 108,
				  "datePaired": 1561494409193,
				  "dateUpdated": 1561494415653
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": true,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"center": {
					  "lng": 6.859931945823973,
					  "lat": -3.53620881848326
					},
					"zoom": 5.660565106624534,
					"pitch": 60.0
				  }
				},
				"floorMarker": {
				  "id": 210,
				  "floor": {
					"name": "01",
					"id": 1059,
					"building": {
					  "name": "Houston Tower 5 - Houston, Texas",
					  "id": 102
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 109,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1561490713383,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 109,
				  "datePaired": 1561490731656,
				  "dateUpdated": 1561490731656
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": true,
				  "siteLogo": false,
				  "mapOrientation": {
					"bearing": 0.0,
					"center": {
					  "lng": 6.85993194582079,
					  "lat": -3.5362088184801195
					},
					"zoom": 5.660565106624534,
					"pitch": 60.0
				  }
				},
				"floorMarker": {
				  "id": 211,
				  "floor": {
					"name": "01",
					"id": 1059,
					"building": {
					  "name": "Houston Tower 5 - Houston, Texas",
					  "id": 102
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 110,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1561518701546,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 110,
				  "dateUpdated": 1561518701546
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 1.433357575324749,
					"center": {
					  "lng": 10.957569036090149,
					  "lat": -4.2781575515084285
					},
					"zoom": 5.1349811426631025,
					"pitch": 51.99999999999999
				  }
				},
				"floorMarker": {
				  "id": 215,
				  "floor": {
					"name": "05",
					"id": 37,
					"building": {
					  "code": "HT1",
					  "name": "Houston Tower 1",
					  "id": 82
					}
				  }
				},
				"name": "Test 7",
				"id": 114,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1595872320320,
				  "lastUpdatedByUserId": 1491,
				  "deviceId": 114,
				  "dateUpdated": 1595872320320
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 221,
				  "floor": {
					"name": "02",
					"id": 1066,
					"building": {
					  "code": "ALK",
					  "name": "Alaska",
					  "id": 106
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 120,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1561493093406,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 120,
				  "dateUpdated": 1561493093406
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"center": {
					  "lng": 6.8794593008346965,
					  "lat": -4.167092468984848
					},
					"zoom": 6.263476372718859,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 222,
				  "floor": {
					"name": "20",
					"id": 12,
					"building": {
					  "code": "AUS",
					  "name": "Austin",
					  "id": 80
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 121,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1565202447613,
				  "lastPairedByUserId": 1339,
				  "lastUnpairedByUserId": 1339,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1561495245330,
				  "deviceId": 121,
				  "datePaired": 1561495218116,
				  "dateUpdated": 1565202447613
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 224,
				  "floor": {
					"name": "01",
					"id": 1065,
					"building": {
					  "code": "ALK",
					  "name": "Alaska",
					  "id": 106
					}
				  }
				},
				"name": "TESTING DEVICE 2",
				"id": 123,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1583363512130,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 123,
				  "dateUpdated": 1583363512130
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 300,
				  "floor": {
					"name": "20",
					"id": 12,
					"building": {
					  "code": "AUS",
					  "name": "Austin",
					  "id": 80
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 135,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "datePolled": 1618900558253,
				  "lastDiscoverableDate": 1618860363316,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 135,
				  "datePaired": 1618860495833,
				  "dateUpdated": 1618860495833
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": -90.0,
					"center": {
					  "lng": 11.557252823950535,
					  "lat": -5.645670344128291
					},
					"zoom": 6.183826242679035,
					"pitch": 60.0
				  }
				},
				"floorMarker": {
				  "id": 307,
				  "floor": {
					"name": "06",
					"id": 3,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 142,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1574111102386,
				  "lastPairedByUserId": 1,
				  "lastUnpairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "dateUnpaired": 1574111100586,
				  "deviceId": 142,
				  "datePaired": 1574111109896,
				  "dateUpdated": 1574111109896
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"center": {
					  "lng": 7.274631348421281,
					  "lat": -5.5614368995998404
					},
					"zoom": 5.634130891079857,
					"pitch": 60.0
				  }
				},
				"floorMarker": {
				  "id": 308,
				  "floor": {
					"name": "06",
					"id": 3,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 143,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1565028988670,
				  "lastPairedByUserId": 1339,
				  "lastUpdatedByUserId": 1339,
				  "deviceId": 143,
				  "datePaired": 1565028998880,
				  "dateUpdated": 1565028998880
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 309,
				  "floor": {
					"name": "10",
					"id": 15,
					"building": {
					  "code": "HT1",
					  "name": "Houston Tower 1",
					  "id": 82
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 144,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1564591611703,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 144,
				  "dateUpdated": 1564591611703
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 310,
				  "floor": {
					"name": "10",
					"id": 15,
					"building": {
					  "code": "HT1",
					  "name": "Houston Tower 1",
					  "id": 82
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 145,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1564591428940,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 145,
				  "dateUpdated": 1564591428940
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 311,
				  "floor": {
					"name": "06",
					"id": 3,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 146,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1574111731420,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 146,
				  "datePaired": 1574111739696,
				  "dateUpdated": 1574111739696
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 312,
				  "floor": {
					"name": "06",
					"id": 3,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 147,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1573775363846,
				  "lastUpdatedByUserId": 1339,
				  "deviceId": 147,
				  "dateUpdated": 1573775363846
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 313,
				  "floor": {
					"name": "06",
					"id": 3,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 148,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1565029420746,
				  "lastUpdatedByUserId": 1339,
				  "deviceId": 148,
				  "dateUpdated": 1565029420746
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 314,
				  "floor": {
					"name": "06",
					"id": 3,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 149,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1565027527643,
				  "lastUpdatedByUserId": 1339,
				  "deviceId": 149,
				  "dateUpdated": 1565027527643
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 315,
				  "floor": {
					"name": "06",
					"id": 3,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 150,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1564674136470,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 150,
				  "dateUpdated": 1564674136470
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 316,
				  "floor": {
					"name": "06",
					"id": 3,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 151,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1565029421986,
				  "lastUpdatedByUserId": 1339,
				  "deviceId": 151,
				  "dateUpdated": 1565029421986
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 321,
				  "floor": {
					"name": "07",
					"id": 1,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 154,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1625066532090,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 154,
				  "dateUpdated": 1625066532090
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [
					82,
					171
				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"center": {
					  "lng": 8.173828125,
					  "lat": -3.4366581585590836
					},
					"zoom": 6.027846559139003,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 322,
				  "floor": {
					"name": "07",
					"id": 1,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 155,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1625093490516,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 155,
				  "dateUpdated": 1625093490516
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 429,
				  "floor": {
					"name": "01",
					"id": 1065,
					"building": {
					  "code": "ALK",
					  "name": "Alaska",
					  "id": 106
					}
				  }
				},
				"name": "BOTTOM",
				"id": 165,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1572467316423,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 165,
				  "dateUpdated": 1572467316423
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 433,
				  "floor": {
					"name": "06",
					"id": 3,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 169,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1574112387323,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 169,
				  "datePaired": 1574112394826,
				  "dateUpdated": 1574112394826
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 434,
				  "floor": {
					"name": "06",
					"id": 3,
					"building": {
					  "code": "",
					  "name": "Houston Tower 2",
					  "id": 43
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 170,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1574113243016,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 170,
				  "datePaired": 1574113252036,
				  "dateUpdated": 1574113252036
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 437,
				  "floor": {
					"name": "01",
					"id": 1122,
					"building": {
					  "name": "Autocad Test - Pita",
					  "id": 134
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 173,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1575417309193,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 173,
				  "datePaired": 1575417352536,
				  "dateUpdated": 1575417352536
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 459,
				  "floor": {
					"name": "05",
					"id": 37,
					"building": {
					  "code": "HT1",
					  "name": "Houston Tower 1",
					  "id": 82
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 175,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1582232892203,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 175,
				  "datePaired": 1582232898303,
				  "dateUpdated": 1582232898303
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 503,
				  "floor": {
					"name": "01",
					"id": 1110,
					"building": {
					  "code": "AUS",
					  "name": "Austin",
					  "id": 80
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 176,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1587749932170,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 176,
				  "datePaired": 1587749963213,
				  "dateUpdated": 1587749963213
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": true,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"center": {
					  "lng": 10.05523681640625,
					  "lat": -5.1866881497044375
					},
					"zoom": 5.798602562239104,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 509,
				  "floor": {
					"name": "05",
					"id": 37,
					"building": {
					  "code": "HT1",
					  "name": "Houston Tower 1",
					  "id": 82
					}
				  }
				},
				"name": "Danielle's Test",
				"id": 177,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1588177464716,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 177,
				  "datePaired": 1588177488236,
				  "dateUpdated": 1588177488236
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 523,
				  "floor": {
					"name": "07",
					"id": 1099,
					"building": {
					  "code": "code",
					  "name": "Arizona - name",
					  "id": 108
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 178,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1597089251906,
				  "lastUpdatedByUserId": 1339,
				  "deviceId": 178,
				  "dateUpdated": 1597089251906
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 526,
				  "floor": {
					"name": "01",
					"id": 1065,
					"building": {
					  "code": "ALK",
					  "name": "Alaska",
					  "id": 106
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 179,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1600272795356,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 179,
				  "dateUpdated": 1600272795356
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 601,
				  "floor": {
					"name": "20",
					"id": 12,
					"building": {
					  "code": "AUS",
					  "name": "Austin",
					  "id": 80
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 183,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "datePolled": 1618867406246,
				  "lastDiscoverableDate": 1618859833073,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 183,
				  "datePaired": 1618859838353,
				  "dateUpdated": 1618859838353
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 602,
				  "floor": {
					"name": "20",
					"id": 12,
					"building": {
					  "code": "AUS",
					  "name": "Austin",
					  "id": 80
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 184,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1618860600976,
				  "lastPairedByUserId": 1,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 184,
				  "datePaired": 1618860605866,
				  "dateUpdated": 1618860605866
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"settings": {
				  "showSensorData": false,
				  "modes": [

				  ],
				  "campus": [

				  ],
				  "legendMinimized": false,
				  "siteLogo": true,
				  "mapOrientation": {
					"bearing": 0.0,
					"pitch": 0.0
				  }
				},
				"floorMarker": {
				  "id": 603,
				  "floor": {
					"name": "20",
					"id": 12,
					"building": {
					  "code": "AUS",
					  "name": "Austin",
					  "id": 80
					}
				  }
				},
				"name": "WAYFINDING Device",
				"id": 185,
				"deviceStatus": {
				  "deviceType": "WAYFINDING",
				  "lastDiscoverableDate": 1618861865103,
				  "lastUpdatedByUserId": 1,
				  "deviceId": 185,
				  "dateUpdated": 1618861865103
				}
			  }
			]

### List of Device Types [GET /devices/types]

+ Response 200
			[
			  {
				"deviceType": "SPACE_PANEL",
				"user": {
				  "floorWarden": false,
				  "firstName": "SPACE_PANEL",
				  "lastName": "DeviceUser",
				  "dateCreated": 1559948578660,
				  "color": "#A5F0C2",
				  "name": "SPACE_PANEL DeviceUser",
				  "id": 1509,
				  "userType": {
					"dateCreated": 1428954498147,
					"name": "Employee",
					"id": 1,
					"dateUpdated": 1669893659410
				  },
				  "userName": "$@spacepaneldeviceuser@$",
				  "passwordResetAttemptsRemaining": 3,
				  "specialNeeds": false,
				  "dateUpdated": 1559948578807
				},
				"markerType": {
				  "hexColor": "3FB7A9",
				  "dateCreated": 1559937354100,
				  "name": "SPACE_PANEL",
				  "description": "",
				  "iconUid": "11087",
				  "markerTypeGroup": {
					"code": "$@IOFFICE_DEVICES@$",
					"dateCreated": 1559926966740,
					"name": "iOFFICE Kiosk Devices",
					"id": 18
				  },
				  "id": 20
				}
			  },
			  {
				"deviceType": "WAYFINDING",
				"user": {
				  "floorWarden": false,
				  "firstName": "WAYFINDING",
				  "lastName": "DeviceUser",
				  "dateCreated": 1559948631790,
				  "color": "#91FCFD",
				  "name": "WAYFINDING DeviceUser",
				  "id": 1510,
				  "userType": {
					"dateCreated": 1428954498147,
					"name": "Employee",
					"id": 1,
					"dateUpdated": 1669893659410
				  },
				  "userName": "$@wayfindingdeviceuser@$",
				  "passwordResetAttemptsRemaining": 3,
				  "specialNeeds": false,
				  "dateUpdated": 1559948631940
				},
				"markerType": {
				  "hexColor": "BEA5FA",
				  "dateCreated": 1559926966786,
				  "name": "WAYFINDING",
				  "description": "",
				  "iconUid": "54614",
				  "markerTypeGroup": {
					"code": "$@IOFFICE_DEVICES@$",
					"dateCreated": 1559926966740,
					"name": "iOFFICE Kiosk Devices",
					"id": 18
				  },
				  "id": 19,
				  "dateUpdated": 1582233086343
				}
			  },
			  {
				"deviceType": "VISITOR_PANEL",
				"user": {
				  "floorWarden": false,
				  "firstName": "VISITOR_PANEL",
				  "lastName": "DeviceUser",
				  "dateCreated": 1603493951377,
				  "color": "#D47456",
				  "name": "VISITOR_PANEL DeviceUser",
				  "id": 3359,
				  "userType": {
					"dateCreated": 1428954498147,
					"name": "Employee",
					"id": 1,
					"dateUpdated": 1669893659410
				  },
				  "userName": "$@visitorpaneldeviceuser@$",
				  "passwordResetAttemptsRemaining": 3,
				  "specialNeeds": false,
				  "dateUpdated": 1603493951583
				},
				"markerType": {
				  "hexColor": "1AA3A5",
				  "dateCreated": 1603493951200,
				  "name": "VISITOR_PANEL",
				  "description": "",
				  "iconUid": "23770",
				  "markerTypeGroup": {
					"code": "$@IOFFICE_DEVICES@$",
					"dateCreated": 1559926966740,
					"name": "iOFFICE Kiosk Devices",
					"id": 18
				  },
				  "id": 126
				}
			  }
			]

### Unpair Device [POST /devices/unpair/{id}]
+ Parameters
    + id (int, `80`) ... ID of the Device 
	
+ Response 200
			{
			  "dateUnpaired": 1670870511776,
			  "unpaired": "device:WAYFINDING:80"
			}

### Device Pending [GET /devices/pending]
+ Parameters
	deviceType (`WAYFINDING`)
	
+ Response 200
			{
			  "expiresIn": 60,
			  "startDate": 1670867655990
			}
			
### Broadcast Device [POST /devices/broadcast/{id}]
+ Request (application/json)
	{}
	
+ Response 200
			{
			  "expiresIn": 60,
			  "startDate": 1670867655990
			}
			
## Sensors [/sensors]

### Retrieve Sensors [GET]
	
+ Response 200
			[
			  {
				"uid": "@031915ff-fbac-446b-ae3d-911d8c7e5ba0",
				"name": "54 phone room (suite 3)",
				"type": {
				  "id": "GE_OCCUPANCY",
				  "name": "General Electric Occupancy Sensor"
				}
			  },
			  {
				"uid": "@0f018303-33d6-4de6-b392-b8520e24948f",
				"name": "62 wkst",
				"type": {
				  "id": "GE_OCCUPANCY",
				  "name": "General Electric Occupancy Sensor"
				}
			  },
			  {
				"uid": "1007706",
				"name": "44 Manuel",
				"type": {
				  "id": "UTI_LIVE_MOTION",
				  "name": "UtilLive Motion Sensor"
				}
			  },
			  {
				"uid": "1007707",
				"name": "46 Cameron",
				"type": {
				  "id": "UTI_LIVE_MOTION",
				  "name": "UtilLive Motion Sensor"
				}
			  },
			  {
				"uid": "1007708",
				"name": "48 Mykal",
				"type": {
				  "id": "UTI_LIVE_MOTION",
				  "name": "UtilLive Motion Sensor"
				}
			  },
			  {
				"uid": "1007710",
				"name": "47 Victor",
				"type": {
				  "id": "UTI_LIVE_MOTION",
				  "name": "UtilLive Motion Sensor"
				}
			  },
			  {
				"uid": "1007712",
				"name": "49 Natalia",
				"type": {
				  "id": "UTI_LIVE_MOTION",
				  "name": "UtilLive Motion Sensor"
				}
			  },
			  {
				"uid": "1007725",
				"name": "50 wkst (Patrick)",
				"type": {
				  "id": "UTI_LIVE_MOTION",
				  "name": "UtilLive Motion Sensor"
				}
			  },
			  {
				"uid": "1007726",
				"name": "51 Jason",
				"type": {
				  "id": "UTI_LIVE_MOTION",
				  "name": "UtilLive Motion Sensor"
				}
			  },
			  {
				"uid": "1007728",
				"name": "52 kitchen",
				"type": {
				  "id": "UTI_LIVE_MOTION",
				  "name": "UtilLive Motion Sensor"
				}
			  },
			  {
				"uid": "1007730",
				"name": "56 lounge by the quiet room",
				"type": {
				  "id": "UTI_LIVE_MOTION",
				  "name": "UtilLive Motion Sensor"
				}
			  },
			  {
				"uid": "1007731",
				"name": "58 lounge by the window st 3",
				"type": {
				  "id": "UTI_LIVE_MOTION",
				  "name": "UtilLive Motion Sensor"
				}
			  },
			  {
				"uid": "123",
				"name": "test",
				"type": {
				  "id": "GE_OCCUPANCY",
				  "name": "General Electric Occupancy Sensor"
				}
			  },
			  {
				"uid": "12311111",
				"name": "",
				"type": {
				  "id": "GE_OCCUPANCY",
				  "name": "General Electric Occupancy Sensor"
				},
				"currentValue": 0,
				"readType": "utilization",
				"lastSensorChangeDate": "2020-01-13T20:38:03Z"
			  },
			  {
				"uid": "123123",
				"name": "",
				"type": {
				  "id": "GE_OCCUPANCY",
				  "name": "General Electric Occupancy Sensor"
				},
				"currentValue": 0,
				"readType": "utilization",
				"lastSensorChangeDate": "2020-02-27T16:20:55Z"
			  },
			  {
				"uid": "12345",
				"name": "testing",
				"type": {
				  "id": "HELIUM_GREEN",
				  "name": "Helium Green Sensor"
				}
			  },
			  {
				"uid": "897987",
				"name": "",
				"type": {
				  "id": "GE_OCCUPANCY",
				  "name": "General Electric Occupancy Sensor"
				},
				"currentValue": 0,
				"readType": "utilization",
				"lastSensorChangeDate": "2020-02-26T21:43:40Z"
			  },
			  {
				"uid": "kenton",
				"name": "test",
				"type": {
				  "id": "GE_OCCUPANCY",
				  "name": "General Electric Occupancy Sensor"
				}
			  },
			  {
				"uid": "pizza",
				"name": "",
				"type": {
				  "id": "GE_OCCUPANCY",
				  "name": "General Electric Occupancy Sensor"
				},
				"currentValue": 0,
				"readType": "utilization",
				"lastSensorChangeDate": "2020-02-26T21:43:28Z"
			  }
			]

### Retrieve Sensor Types [GET /sensors/types]
	
+ Response 200
			{
			  "status": "ok",
			  "response": [
				{
				  "id": "HELIUMGREEN",
				  "name": "Helium Green",
				  "sensorTypes": [
					{
					  "id": "HELIUM_GREEN",
					  "name": "Helium Green Sensor"
					}
				  ]
				},
				{
				  "id": "IACONNECTS",
				  "name": "iaConnects",
				  "sensorTypes": [
					{
					  "id": "IA_UTILIZATION",
					  "name": "IAConnects Utilization Sensor"
					}
				  ]
				},
				{
				  "id": "COWORKR",
				  "name": "CoWorkr",
				  "sensorTypes": [
					{
					  "id": "COWORKR_OCCUPANCY",
					  "name": "CoWorkr Occupancy Sensor"
					},
					{
					  "id": "COWORKR_PEOPLE_COUNT",
					  "name": "CoWorkr People Count Sensor"
					}
				  ]
				},
				{
				  "id": "VERGESENSE",
				  "name": "Vergesense",
				  "sensorTypes": [
					{
					  "id": "VERGESENSE",
					  "name": "VergeSense People Count Sensor"
					}
				  ]
				},
				{
				  "id": "CURRENT",
				  "name": "Current",
				  "sensorTypes": [
					{
					  "id": "GE_OCCUPANCY",
					  "name": "General Electric Occupancy Sensor"
					},
					{
					  "id": "GE_PEOPLE_COUNT",
					  "name": "General Electric People Count Sensor"
					}
				  ]
				},
				{
				  "id": "IBEACON",
				  "name": "iBeacon",
				  "sensorTypes": [
					{
					  "id": "IBEACON",
					  "name": "iBeacon"
					}
				  ]
				},
				{
				  "id": "UTILIVE",
				  "name": "UtiLive",
				  "sensorTypes": [
					{
					  "id": "UTI_LIVE_MOTION",
					  "name": "UtilLive Motion Sensor"
					}
				  ]
				},
				{
				  "id": "WORKPLACEFABRIC",
				  "name": "Workplace Fabric",
				  "sensorTypes": [
					{
					  "id": "WORKPLACE_FABRIC",
					  "name": "Workplace Fabric Sensor"
					}
				  ]
				},
				{
				  "id": "RADIANT",
				  "name": "Radiant",
				  "sensorTypes": [
					{
					  "id": "RADIANT_OCCUPANCY",
					  "name": "Radiant Occupancy Sensor"
					}
				  ]
				},
				{
				  "id": "EMBRAVA",
				  "name": "Embrava",
				  "sensorTypes": [
					{
					  "id": "EMBRAVA_DESK_SIGN",
					  "name": "Embrava Desk Sign"
					}
				  ]
				}
			  ]
			}
### Retrieve Sensor Rooms [GET /sensors/rooms]
+ Parameters
    + activeNow (boolean, `true`)

+ Response 200
			{
			  "status": "ok",
			  "response": [
				{
				  "roomId": 80426,
				  "links": [
					{
					  "sensorUid": "12345",
					  "sensorType": {
						"id": "HELIUM_GREEN",
						"name": "Helium Green Sensor"
					  },
					  "notes": "testing",
					  "linkStart": "2022-12-12T07:19:17Z"
					}
				  ]
				},
				{
				  "roomId": 77468,
				  "links": [
					{
					  "sensorUid": "897987",
					  "sensorType": {
						"id": "GE_OCCUPANCY",
						"name": "General Electric Occupancy Sensor"
					  },
					  "notes": "",
					  "linkStart": "2020-02-26T21:43:28Z"
					}
				  ]
				},
				{
				  "roomId": 79782,
				  "links": [
					{
					  "sensorUid": "12311111",
					  "sensorType": {
						"id": "GE_OCCUPANCY",
						"name": "General Electric Occupancy Sensor"
					  },
					  "notes": "",
					  "linkStart": "2020-01-13T20:38:03Z"
					}
				  ]
				},
				{
				  "roomId": 77475,
				  "links": [
					{
					  "sensorUid": "123123",
					  "sensorType": {
						"id": "GE_OCCUPANCY",
						"name": "General Electric Occupancy Sensor"
					  },
					  "notes": "",
					  "linkStart": "2020-02-27T16:20:55Z"
					}
				  ]
				}
			  ]
			}
			
### Add/Move/Deallocate Sensor [POST /sensors/rooms]

Request response for Add/Move Sensor:

+ Request (application/json)
			{
			  "roomId": 80144,
			  "links": [
				{
				  "sensorUid": "0909",
				  "notes": "Test",
				  "vendor": {
					"id": "IBEACON",
					"name": "iBeacon",
					"sensorTypes": [
					  {
						"id": "IBEACON",
						"name": "iBeacon"
					  }
					]
				  },
				  "sensorType": {
					"id": "IBEACON",
					"name": "iBeacon"
				  }
				}
			  ]
			}
						
+ Response 200
			{
			  "status": "ok",
			  "response": {
				"roomId": 80144,
				"links": [
				  {
					"sensorUid": "0909",
					"sensorType": {
					  "id": "IBEACON",
					  "name": "iBeacon"
					},
					"notes": "Test",
					"linkStart": "2023-01-10T15:58:59Z"
				  }
				]
			  }
			}
			
Request response for Deallocate Sensor:
+ Request (application/json)
			{
			  "roomId": 80144,
			  "links": [

			  ]
			}
			
+ Response 200			
			{
			  "status": "ok",
			  "response": {
				"roomId": 80144,
				"links": [

				]
			  }
			}
		
### Update Sensor [PUT /sensors]
+ Request (application/json)
			{
			  "uid": "0909",
			  "name": "TestEdit",
			  "type": {
				"id": "IBEACON"
			  }
			}

+ Response 200
			{
			  "status": "ok",
			  "response": 1
			}
			
### Retrieve Sensor Live Room Data [GET /sensors/live-room-utilization]

+ Parameters
    + floorId (int, `408`) ... ID of the floor

+ Response 200
			{
			  "status": "ok",
			  "response": {

			  }
			}
			
### Retrieve Sensor Live Room People Count [GET /sensors/live-room-people-count]

+ Parameters
    + floorId (int, `408`) ... ID of the floor
	+ aggregate (`max`)

+ Response 200	
			{
			  "status": "ok",
			  "response": {

			  }
			}
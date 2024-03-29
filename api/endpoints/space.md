# Group Space

## Hierarchy [/categories]
Hierarchy related resources of *iOffice API*

+ Model (application/json)
    JSON representation of the Category	Resource

## Add New Hierarchy [POST]
+ Request (application/json)
			{
				"name":"AddOn1",
				"categoryType":[{"id":3}]
			}
				
+ Response 201
			{
				"dateCreated": 1669805101765,
				"color": {},
				"name": "AddOn1",
				"id": 486
			}
			
## Update Hierarchy [PUT]
+ Request (application/json)
			{
				"id":493,
				"name":"NEWHIERARCHIMAINLEVEL"
			}
			
+ Response 200
			{
				"dateCreated": 1669836751583,
				"color": {},
				"name": "NEWHIERARCHIMAINLEVEL",
				"id": 493,
				"dateUpdated": 1669815993488
			}

## Delete Hierarchy [DELETE /categories/{id}]
+ Parameters
    + id (string) ... ID of the Category

+ Response 200
			{"response":"Successfully removed"}
			
## Retrieve Hierarchy Types [GET /categories/type/{id}]
+ Parameters
    + id (int, `3`) ... ID of the Category Type
	
+ Response 200
			[
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Country",
					"id": 46,
					"category": {
					  "name": "_",
					  "id": 17
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Region",
					"id": 44,
					"category": {
					  "name": "_",
					  "id": 17
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 3,
					"name": "Division",
					"id": 90,
					"category": {
					  "name": "_",
					  "id": 17
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Sub-Region",
					"id": 45,
					"category": {
					  "name": "_",
					  "id": 17
					},
					"fields": [

					]
				  }
				],
				"name": "_",
				"id": 17
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Unnamed Hierarchy Level",
					"id": 529,
					"category": {
					  "name": "0001 super",
					  "id": 355
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom04",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom04",
						"id": 321,
						"type": "input",
						"baseField": {
						  "code": "custom04",
						  "name": "Custom04",
						  "id": 404
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom05",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom05",
						"id": 322,
						"type": "input",
						"baseField": {
						  "code": "custom05",
						  "name": "Custom05",
						  "id": 405
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom06",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom06",
						"id": 323,
						"type": "input",
						"baseField": {
						  "code": "custom06",
						  "name": "Custom06",
						  "id": 406
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom07",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom07",
						"id": 324,
						"type": "input",
						"baseField": {
						  "code": "custom07",
						  "name": "Custom07",
						  "id": 407
						}
					  },
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 325,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"code": "SUP-01",
					"level": 2,
					"name": "super-duper",
					"id": 642,
					"category": {
					  "name": "0001 super",
					  "id": 355
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"code": "DUP",
					"level": 0,
					"name": "0001-01-super",
					"id": 440,
					"category": {
					  "name": "0001 super",
					  "id": 355
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 327,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom03",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom03",
						"id": 328,
						"type": "input",
						"baseField": {
						  "code": "custom03",
						  "name": "Custom03",
						  "id": 403
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom04",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom04",
						"id": 329,
						"type": "input",
						"baseField": {
						  "code": "custom04",
						  "name": "Custom04",
						  "id": 404
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom05",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom05",
						"id": 330,
						"type": "input",
						"baseField": {
						  "code": "custom05",
						  "name": "Custom05",
						  "id": 405
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom06",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom06",
						"id": 331,
						"type": "input",
						"baseField": {
						  "code": "custom06",
						  "name": "Custom06",
						  "id": 406
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom07",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom07",
						"id": 332,
						"type": "input",
						"baseField": {
						  "code": "custom07",
						  "name": "Custom07",
						  "id": 407
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom10",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom10",
						"id": 333,
						"type": "input",
						"baseField": {
						  "code": "custom10",
						  "name": "Custom10",
						  "id": 410
						}
					  },
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 334,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 326,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  }
				],
				"name": "0001 super",
				"id": 355
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Level 1",
					"id": 694,
					"category": {
					  "name": "a1",
					  "id": 472
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Level 2",
					"id": 695,
					"category": {
					  "name": "a1",
					  "id": 472
					},
					"fields": [

					]
				  }
				],
				"name": "a1",
				"id": 472
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 696,
					"category": {
					  "name": "a2",
					  "id": 473
					},
					"fields": [

					]
				  }
				],
				"name": "a2",
				"id": 473
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Hierarchy 1",
					"id": 697,
					"category": {
					  "name": "A3",
					  "id": 474
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Hierarchy 2",
					"id": 698,
					"category": {
					  "name": "A3",
					  "id": 474
					},
					"fields": [

					]
				  }
				],
				"name": "A3",
				"id": 474
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 663,
					"category": {
					  "name": "Ahead2",
					  "id": 454
					},
					"fields": [

					]
				  }
				],
				"name": "Ahead2",
				"id": 454
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 664,
					"category": {
					  "name": "Ahead3",
					  "id": 455
					},
					"fields": [

					]
				  }
				],
				"name": "Ahead3",
				"id": 455
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 665,
					"category": {
					  "name": "Ahead3",
					  "id": 456
					},
					"fields": [

					]
				  }
				],
				"name": "Ahead3",
				"id": 456
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 450,
					"category": {
					  "name": "Alan H Tesitng",
					  "id": 359
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 458,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom04",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom04",
						"id": 459,
						"type": "input",
						"baseField": {
						  "code": "custom04",
						  "name": "Custom04",
						  "id": 404
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom05",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom05",
						"id": 455,
						"type": "input",
						"baseField": {
						  "code": "custom05",
						  "name": "Custom05",
						  "id": 405
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom09",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom09",
						"id": 456,
						"type": "input",
						"baseField": {
						  "code": "custom09",
						  "name": "Custom09",
						  "id": 409
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 457,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Unnamed Hierarchy Level 1",
					"id": 451,
					"category": {
					  "name": "Alan H Tesitng",
					  "id": 359
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom03",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom03",
						"id": 478,
						"type": "input",
						"baseField": {
						  "code": "custom03",
						  "name": "Custom03",
						  "id": 403
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom04",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom04",
						"id": 479,
						"type": "input",
						"baseField": {
						  "code": "custom04",
						  "name": "Custom04",
						  "id": 404
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom05",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom05",
						"id": 476,
						"type": "input",
						"baseField": {
						  "code": "custom05",
						  "name": "Custom05",
						  "id": 405
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 477,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Unnamed Hierarchy Level.2",
					"id": 452,
					"category": {
					  "name": "Alan H Tesitng",
					  "id": 359
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom04",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom04",
						"id": 475,
						"type": "input",
						"baseField": {
						  "code": "custom04",
						  "name": "Custom04",
						  "id": 404
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom05",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom05",
						"id": 472,
						"type": "input",
						"baseField": {
						  "code": "custom05",
						  "name": "Custom05",
						  "id": 405
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom08",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom08",
						"id": 473,
						"type": "input",
						"baseField": {
						  "code": "custom08",
						  "name": "Custom08",
						  "id": 408
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 474,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  }
				],
				"name": "Alan H Tesitng",
				"id": 359
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Day",
					"id": 646,
					"category": {
					  "name": "April_20",
					  "id": 445
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Week",
					"id": 645,
					"category": {
					  "name": "April_20",
					  "id": 445
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Month",
					"id": 644,
					"category": {
					  "name": "April_20",
					  "id": 445
					},
					"fields": [

					]
				  }
				],
				"name": "April_20",
				"id": 445
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Level 1",
					"id": 649,
					"category": {
					  "name": "April21",
					  "id": 447
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Level 2",
					"id": 650,
					"category": {
					  "name": "April21",
					  "id": 447
					},
					"fields": [

					]
				  }
				],
				"name": "April21",
				"id": 447
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "space.Unnamed_Hierarchy_Level",
					"id": 408,
					"category": {
					  "name": "c_updatess",
					  "id": 336
					},
					"fields": [

					]
				  }
				],
				"name": "c_updatess",
				"id": 336
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 3,
					"name": "Level 3",
					"id": 420,
					"category": {
					  "name": "Campus",
					  "id": 331
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 497,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom03",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom03",
						"id": 498,
						"type": "input",
						"baseField": {
						  "code": "custom03",
						  "name": "Custom03",
						  "id": 403
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom04",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom04",
						"id": 499,
						"type": "input",
						"baseField": {
						  "code": "custom04",
						  "name": "Custom04",
						  "id": 404
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom05",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom05",
						"id": 500,
						"type": "input",
						"baseField": {
						  "code": "custom05",
						  "name": "Custom05",
						  "id": 405
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom06",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom06",
						"id": 501,
						"type": "input",
						"baseField": {
						  "code": "custom06",
						  "name": "Custom06",
						  "id": 406
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom07",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom07",
						"id": 502,
						"type": "input",
						"baseField": {
						  "code": "custom07",
						  "name": "Custom07",
						  "id": 407
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom08",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom08",
						"id": 503,
						"type": "input",
						"baseField": {
						  "code": "custom08",
						  "name": "Custom08",
						  "id": 408
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom09",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom09",
						"id": 504,
						"type": "input",
						"baseField": {
						  "code": "custom09",
						  "name": "Custom09",
						  "id": 409
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom10",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom10",
						"id": 505,
						"type": "input",
						"baseField": {
						  "code": "custom10",
						  "name": "Custom10",
						  "id": 410
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom11",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom11",
						"id": 506,
						"type": "input",
						"baseField": {
						  "code": "custom11",
						  "name": "Custom11",
						  "id": 411
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom12",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom12",
						"id": 507,
						"type": "input",
						"baseField": {
						  "code": "custom12",
						  "name": "Custom12",
						  "id": 412
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom13",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom13",
						"id": 508,
						"type": "input",
						"baseField": {
						  "code": "custom13",
						  "name": "Custom13",
						  "id": 413
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom14",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom14",
						"id": 509,
						"type": "input",
						"baseField": {
						  "code": "custom14",
						  "name": "Custom14",
						  "id": 414
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom15",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom15",
						"id": 510,
						"type": "input",
						"baseField": {
						  "code": "custom15",
						  "name": "Custom15",
						  "id": 415
						}
					  },
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 511,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 512,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Level 2",
					"id": 419,
					"category": {
					  "name": "Campus",
					  "id": 331
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 495,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 496,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Campus",
					"id": 403,
					"category": {
					  "name": "Campus",
					  "id": 331
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 143,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom03",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom03",
						"id": 144,
						"type": "input",
						"baseField": {
						  "code": "custom03",
						  "name": "Custom03",
						  "id": 403
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom04",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom04",
						"id": 145,
						"type": "input",
						"baseField": {
						  "code": "custom04",
						  "name": "Custom04",
						  "id": 404
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom05",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom05",
						"id": 146,
						"type": "input",
						"baseField": {
						  "code": "custom05",
						  "name": "Custom05",
						  "id": 405
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom06",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom06",
						"id": 147,
						"type": "input",
						"baseField": {
						  "code": "custom06",
						  "name": "Custom06",
						  "id": 406
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom07",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom07",
						"id": 148,
						"type": "input",
						"baseField": {
						  "code": "custom07",
						  "name": "Custom07",
						  "id": 407
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom08",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom08",
						"id": 149,
						"type": "input",
						"baseField": {
						  "code": "custom08",
						  "name": "Custom08",
						  "id": 408
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom09",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom09",
						"id": 150,
						"type": "input",
						"baseField": {
						  "code": "custom09",
						  "name": "Custom09",
						  "id": 409
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom10",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom10",
						"id": 151,
						"type": "input",
						"baseField": {
						  "code": "custom10",
						  "name": "Custom10",
						  "id": 410
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom11",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom11",
						"id": 152,
						"type": "input",
						"baseField": {
						  "code": "custom11",
						  "name": "Custom11",
						  "id": 411
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom12",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom12",
						"id": 153,
						"type": "input",
						"baseField": {
						  "code": "custom12",
						  "name": "Custom12",
						  "id": 412
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom13",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom13",
						"id": 154,
						"type": "input",
						"baseField": {
						  "code": "custom13",
						  "name": "Custom13",
						  "id": 413
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom14",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom14",
						"id": 155,
						"type": "input",
						"baseField": {
						  "code": "custom14",
						  "name": "Custom14",
						  "id": 414
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom15",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom15",
						"id": 156,
						"type": "input",
						"baseField": {
						  "code": "custom15",
						  "name": "Custom15",
						  "id": 415
						}
					  },
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 157,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 142,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Level 1",
					"id": 418,
					"category": {
					  "name": "Campus",
					  "id": 331
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 493,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 494,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  }
				],
				"name": "Campus",
				"id": 331
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Region",
					"id": 92,
					"category": {
					  "name": "Company",
					  "id": 58
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 23,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 22,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Parent Company",
					"id": 91,
					"category": {
					  "name": "Company",
					  "id": 58
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 35,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 34,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 3,
					"name": "Campus",
					"id": 421,
					"category": {
					  "name": "Company",
					  "id": 58
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 25,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 24,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"code": "DIV",
					"level": 2,
					"name": "Division",
					"id": 105,
					"category": {
					  "name": "Company",
					  "id": 58
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 21,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 20,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 4,
					"name": "Faculty",
					"id": 445,
					"category": {
					  "name": "Company",
					  "id": 58
					},
					"fields": [

					]
				  }
				],
				"name": "Company",
				"id": 58
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Unnamed Hierarchy Level2",
					"id": 654,
					"category": {
					  "name": "demo2",
					  "id": 449
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level1",
					"id": 653,
					"category": {
					  "name": "demo2",
					  "id": 449
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Unnamed Hierarchy Level3",
					"id": 655,
					"category": {
					  "name": "demo2",
					  "id": 449
					},
					"fields": [

					]
				  }
				],
				"name": "demo2",
				"id": 449
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Parent Level Fri Dec 10",
					"id": 598,
					"category": {
					  "name": "Fri Dec 10",
					  "id": 432
					},
					"fields": [

					]
				  }
				],
				"name": "Fri Dec 10",
				"id": 432
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Specialty",
					"id": 402,
					"category": {
					  "name": "Function",
					  "id": 330
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Function",
					"id": 401,
					"category": {
					  "name": "Function",
					  "id": 330
					},
					"fields": [

					]
				  }
				],
				"name": "Function",
				"id": 330
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Child Level 1",
					"id": 561,
					"category": {
					  "name": "IManage",
					  "id": 409
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Parent Level1",
					"id": 559,
					"category": {
					  "name": "IManage",
					  "id": 409
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Grand child Level1",
					"id": 562,
					"category": {
					  "name": "IManage",
					  "id": 409
					},
					"fields": [

					]
				  }
				],
				"name": "IManage",
				"id": 409
			  },
			  {
				"code": "007",
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"code": "8877",
					"level": 3,
					"name": "Depth II",
					"id": 632,
					"category": {
					  "code": "007",
					  "name": "Jasper Join Test",
					  "id": 442
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"code": "12345",
					"level": 1,
					"name": "Depth I",
					"id": 628,
					"category": {
					  "code": "007",
					  "name": "Jasper Join Test",
					  "id": 442
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"code": "8765",
					"level": 2,
					"name": "Depth II",
					"id": 631,
					"category": {
					  "code": "007",
					  "name": "Jasper Join Test",
					  "id": 442
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"code": "990",
					"level": 0,
					"name": "Jasper Join Test",
					"id": 627,
					"category": {
					  "code": "007",
					  "name": "Jasper Join Test",
					  "id": 442
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"code": "004",
					"level": 4,
					"name": "Depth 4",
					"id": 633,
					"category": {
					  "code": "007",
					  "name": "Jasper Join Test",
					  "id": 442
					},
					"fields": [

					]
				  }
				],
				"name": "Jasper Join Test",
				"id": 442
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Purple Hierarchy Level",
					"id": 439,
					"category": {
					  "name": "JBen",
					  "id": 354
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 262,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  },
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 263,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 261,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Red Hierarchy Level",
					"id": 503,
					"category": {
					  "name": "JBen",
					  "id": 354
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom03",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom03",
						"id": 264,
						"type": "input",
						"baseField": {
						  "code": "custom03",
						  "name": "Custom03",
						  "id": 403
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom04",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom04",
						"id": 265,
						"type": "input",
						"baseField": {
						  "code": "custom04",
						  "name": "Custom04",
						  "id": 404
						}
					  }
					]
				  }
				],
				"name": "JBen",
				"id": 354
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "State",
					"id": 447,
					"category": {
					  "name": "Jessica 5/19 Testing",
					  "id": 358
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 69,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Country",
					"id": 446,
					"category": {
					  "name": "Jessica 5/19 Testing",
					  "id": 358
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 68,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 3,
					"name": "Subdivision",
					"id": 616,
					"category": {
					  "name": "Jessica 5/19 Testing",
					  "id": 358
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "City",
					"id": 448,
					"category": {
					  "name": "Jessica 5/19 Testing",
					  "id": 358
					},
					"fields": [

					]
				  }
				],
				"name": "Jessica 5/19 Testing",
				"id": 358
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 4,
					"name": "Unnamed Hierarchy Level",
					"id": 458,
					"category": {
					  "name": "Jessica 5/26 Testing",
					  "id": 360
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 205,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom07",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom07",
						"id": 206,
						"type": "input",
						"baseField": {
						  "code": "custom07",
						  "name": "Custom07",
						  "id": 407
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom08",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom08",
						"id": 207,
						"type": "input",
						"baseField": {
						  "code": "custom08",
						  "name": "Custom08",
						  "id": 408
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 204,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Country",
					"id": 453,
					"category": {
					  "name": "Jessica 5/26 Testing",
					  "id": 360
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 211,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom05",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom05",
						"id": 212,
						"type": "input",
						"baseField": {
						  "code": "custom05",
						  "name": "Custom05",
						  "id": 405
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom06",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom06",
						"id": 213,
						"type": "input",
						"baseField": {
						  "code": "custom06",
						  "name": "Custom06",
						  "id": 406
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "City",
					"id": 455,
					"category": {
					  "name": "Jessica 5/26 Testing",
					  "id": 360
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 3,
					"name": "Unnamed Hierarchy Level",
					"id": 457,
					"category": {
					  "name": "Jessica 5/26 Testing",
					  "id": 360
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "State",
					"id": 454,
					"category": {
					  "name": "Jessica 5/26 Testing",
					  "id": 360
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 71,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  }
				],
				"name": "Jessica 5/26 Testing",
				"id": 360
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 4,
					"name": "Unnamed Hierarchy Test",
					"id": 442,
					"category": {
					  "name": "Jessica's New Hierarchy",
					  "id": 348
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Global Region",
					"id": 438,
					"category": {
					  "name": "Jessica's New Hierarchy",
					  "id": 348
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Unnamed Test Level",
					"id": 449,
					"category": {
					  "name": "Jessica's New Hierarchy",
					  "id": 348
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 5,
					"name": "City",
					"id": 427,
					"category": {
					  "name": "Jessica's New Hierarchy",
					  "id": 348
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Country-",
					"id": 425,
					"category": {
					  "name": "Jessica's New Hierarchy",
					  "id": 348
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 3,
					"name": "State",
					"id": 426,
					"category": {
					  "name": "Jessica's New Hierarchy",
					  "id": 348
					},
					"fields": [

					]
				  }
				],
				"name": "Jessica's New Hierarchy",
				"id": 348
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Level 2",
					"id": 652,
					"category": {
					  "name": "May22",
					  "id": 448
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Level 1",
					"id": 651,
					"category": {
					  "name": "May22",
					  "id": 448
					},
					"fields": [

					]
				  }
				],
				"name": "May22",
				"id": 448
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "State",
					"id": 570,
					"category": {
					  "name": "My Portfolio",
					  "id": 414
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Country",
					"id": 569,
					"category": {
					  "name": "My Portfolio",
					  "id": 414
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 3,
					"name": "City",
					"id": 572,
					"category": {
					  "name": "My Portfolio",
					  "id": 414
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 480,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "County",
					"id": 571,
					"category": {
					  "name": "My Portfolio",
					  "id": 414
					},
					"fields": [

					]
				  }
				],
				"name": "My Portfolio",
				"id": 414
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 661,
					"category": {
					  "name": "name1",
					  "id": 452
					},
					"fields": [

					]
				  }
				],
				"name": "name1",
				"id": 452
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 662,
					"category": {
					  "name": "name2",
					  "id": 453
					},
					"fields": [

					]
				  }
				],
				"name": "name2",
				"id": 453
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 674,
					"category": {
					  "name": "New one1",
					  "id": 460
					},
					"fields": [

					]
				  }
				],
				"name": "New one1",
				"id": 460
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Unnamed Hierarchy Level2",
					"id": 703,
					"category": {
					  "name": "Nov23",
					  "id": 477
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level 1",
					"id": 702,
					"category": {
					  "name": "Nov23",
					  "id": 477
					},
					"fields": [

					]
				  }
				],
				"name": "Nov23",
				"id": 477
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 688,
					"category": {
					  "name": "OCt",
					  "id": 467
					},
					"fields": [

					]
				  }
				],
				"name": "OCt",
				"id": 467
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "First",
					"id": 681,
					"category": {
					  "name": "Oct21",
					  "id": 463
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Thrid",
					"id": 683,
					"category": {
					  "name": "Oct21",
					  "id": 463
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Second",
					"id": 682,
					"category": {
					  "name": "Oct21",
					  "id": 463
					},
					"fields": [

					]
				  }
				],
				"name": "Oct21",
				"id": 463
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Level 1",
					"id": 684,
					"category": {
					  "name": "Oct25",
					  "id": 464
					},
					"fields": [

					]
				  }
				],
				"name": "Oct25",
				"id": 464
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 686,
					"category": {
					  "name": "OCt25-2",
					  "id": 465
					},
					"fields": [

					]
				  }
				],
				"name": "OCt25-2",
				"id": 465
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 687,
					"category": {
					  "name": "Oct25-3",
					  "id": 466
					},
					"fields": [

					]
				  }
				],
				"name": "Oct25-3",
				"id": 466
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level 1",
					"id": 689,
					"category": {
					  "name": "Oct25-4",
					  "id": 468
					},
					"fields": [

					]
				  }
				],
				"name": "Oct25-4",
				"id": 468
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 690,
					"category": {
					  "name": "OCT26",
					  "id": 469
					},
					"fields": [

					]
				  }
				],
				"name": "OCT26",
				"id": 469
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Unnamed Hierarchy Level",
					"id": 692,
					"category": {
					  "name": "oct26-2",
					  "id": 470
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 691,
					"category": {
					  "name": "oct26-2",
					  "id": 470
					},
					"fields": [

					]
				  }
				],
				"name": "oct26-2",
				"id": 470
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 564,
					"category": {
					  "name": "Presentation ",
					  "id": 411
					},
					"fields": [

					]
				  }
				],
				"name": "Presentation ",
				"id": 411
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "City_5555555",
					"id": 705,
					"category": {
					  "name": "PT_1111111",
					  "id": 478
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "State_5555555",
					"id": 704,
					"category": {
					  "name": "PT_1111111",
					  "id": 478
					},
					"fields": [

					]
				  }
				],
				"name": "PT_1111111",
				"id": 478
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy",
					"id": 693,
					"category": {
					  "name": "Q",
					  "id": 471
					},
					"fields": [

					]
				  }
				],
				"name": "Q",
				"id": 471
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "QA Join Test",
					"id": 622,
					"category": {
					  "name": "QA Join Test",
					  "id": 440
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 3,
					"name": "Depth III",
					"id": 625,
					"category": {
					  "name": "QA Join Test",
					  "id": 440
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Depth I",
					"id": 623,
					"category": {
					  "name": "QA Join Test",
					  "id": 440
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Depth II",
					"id": 624,
					"category": {
					  "name": "QA Join Test",
					  "id": 440
					},
					"fields": [

					]
				  }
				],
				"name": "QA Join Test",
				"id": 440
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "RB Hierarchy Level 1",
					"id": 554,
					"category": {
					  "name": "Rainbow hierarchy",
					  "id": 408
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 4,
					"name": "RB Level 5",
					"id": 558,
					"category": {
					  "name": "Rainbow hierarchy",
					  "id": 408
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "RB Level 3",
					"id": 556,
					"category": {
					  "name": "Rainbow hierarchy",
					  "id": 408
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 3,
					"name": "RB Level 4",
					"id": 557,
					"category": {
					  "name": "Rainbow hierarchy",
					  "id": 408
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "RB Level 2",
					"id": 555,
					"category": {
					  "name": "Rainbow hierarchy",
					  "id": 408
					},
					"fields": [

					]
				  }
				],
				"name": "Rainbow hierarchy",
				"id": 408
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Sab Level 3 new",
					"id": 472,
					"category": {
					  "name": "Sabera's test Heirarchy",
					  "id": 364
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 271,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Sab level 1 new",
					"id": 468,
					"category": {
					  "name": "Sabera's test Heirarchy",
					  "id": 364
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom01",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Hello",
						"id": 266,
						"type": "input",
						"baseField": {
						  "code": "custom01",
						  "name": "Hello",
						  "id": 401
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Sab Level 2 new",
					"id": 469,
					"category": {
					  "name": "Sabera's test Heirarchy",
					  "id": 364
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "custom02",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom02",
						"id": 481,
						"type": "input",
						"baseField": {
						  "code": "custom02",
						  "name": "Custom02",
						  "id": 402
						}
					  },
					  {
						"displayType": "Input",
						"code": "custom03",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Custom03",
						"id": 482,
						"type": "input",
						"baseField": {
						  "code": "custom03",
						  "name": "Custom03",
						  "id": 403
						}
					  }
					]
				  }
				],
				"name": "Sabera's test Heirarchy",
				"id": 364
			  },
			  {
				"code": "STC",
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Floor",
					"id": 637,
					"category": {
					  "code": "STC",
					  "name": "Sergeo Test Category",
					  "id": 443
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 3,
					"name": "Space",
					"id": 638,
					"category": {
					  "code": "STC",
					  "name": "Sergeo Test Category",
					  "id": 443
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Level",
					"id": 643,
					"category": {
					  "code": "STC",
					  "name": "Sergeo Test Category",
					  "id": 443
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"code": "STC",
					"level": 0,
					"name": "Sergeo Test Category",
					"id": 634,
					"category": {
					  "code": "STC",
					  "name": "Sergeo Test Category",
					  "id": 443
					},
					"fields": [

					]
				  }
				],
				"name": "Sergeo Test Category",
				"id": 443
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "State",
					"id": 524,
					"category": {
					  "name": "Site Location",
					  "id": 398
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Country",
					"id": 523,
					"category": {
					  "name": "Site Location",
					  "id": 398
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 273,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "City",
					"id": 525,
					"category": {
					  "name": "Site Location",
					  "id": 398
					},
					"fields": [

					]
				  }
				],
				"name": "Site Location",
				"id": 398
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Unnamed Hierarchy Level",
					"id": 592,
					"category": {
					  "name": "Snow White",
					  "id": 429
					},
					"fields": [

					]
				  }
				],
				"name": "Snow White",
				"id": 429
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Level 3",
					"id": 614,
					"category": {
					  "name": "TEST",
					  "id": 437
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 491,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Level 1",
					"id": 612,
					"category": {
					  "name": "TEST",
					  "id": 437
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 527,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  }
					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Level 2",
					"id": 613,
					"category": {
					  "name": "TEST",
					  "id": 437
					},
					"fields": [
					  {
						"displayType": "Input",
						"code": "description",
						"dataType": "TEXT",
						"options": "{\"password\":false,\"multiline\":false}",
						"name": "Description",
						"id": 492,
						"type": "input",
						"baseField": {
						  "code": "description",
						  "name": "Description",
						  "id": 395
						}
					  }
					]
				  }
				],
				"name": "TEST",
				"id": 437
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "Parent Level",
					"id": 550,
					"category": {
					  "name": "Test",
					  "id": 406
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "Grand Child Level",
					"id": 563,
					"category": {
					  "name": "Test",
					  "id": 406
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "Child Level",
					"id": 551,
					"category": {
					  "name": "Test",
					  "id": 406
					},
					"fields": [

					]
				  }
				],
				"name": "Test",
				"id": 406
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "test desktop categories",
					"id": 576,
					"category": {
					  "name": "test desktop categories",
					  "id": 416
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "new depth",
					"id": 577,
					"category": {
					  "name": "test desktop categories",
					  "id": 416
					},
					"fields": [

					]
				  }
				],
				"name": "test desktop categories",
				"id": 416
			  },
			  {
				"depths": [
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 0,
					"name": "top",
					"id": 706,
					"category": {
					  "name": "Test Tree",
					  "id": 479
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 1,
					"name": "middle",
					"id": 707,
					"category": {
					  "name": "Test Tree",
					  "id": 479
					},
					"fields": [

					]
				  },
				  {
					"availableFields": [
					  {
						"code": "custom02",
						"name": "Custom02",
						"id": 402
					  },
					  {
						"code": "custom03",
						"name": "Custom03",
						"id": 403
					  },
					  {
						"code": "custom04",
						"name": "Custom04",
						"id": 404
					  },
					  {
						"code": "custom05",
						"name": "Custom05",
						"id": 405
					  },
					  {
						"code": "custom06",
						"name": "Custom06",
						"id": 406
					  },
					  {
						"code": "custom07",
						"name": "Custom07",
						"id": 407
					  },
					  {
						"code": "custom08",
						"name": "Custom08",
						"id": 408
					  },
					  {
						"code": "custom09",
						"name": "Custom09",
						"id": 409
					  },
					  {
						"code": "custom10",
						"name": "Custom10",
						"id": 410
					  },
					  {
						"code": "custom11",
						"name": "Custom11",
						"id": 411
					  },
					  {
						"code": "custom12",
						"name": "Custom12",
						"id": 412
					  },
					  {
						"code": "custom13",
						"name": "Custom13",
						"id": 413
					  },
					  {
						"code": "custom14",
						"name": "Custom14",
						"id": 414
					  },
					  {
						"code": "custom15",
						"name": "Custom15",
						"id": 415
					  },
					  {
						"code": "description",
						"name": "Description",
						"id": 395
					  },
					  {
						"code": "custom01",
						"name": "Hello",
						"id": 401
					  }
					],
					"level": 2,
					"name": "bottom",
					"id": 708,
					"category": {
					  "name": "Test Tree",
					  "id": 479
					},
					"fields": [

					]
				  }
				],
				"name": "Test Tree",
				"id": 479
			  }
			]

## Retrieve Spaces based on Hierarchy [GET /categories/items]
+ Parameters
	+ category (int, `331`)
    + root (boolean, `true`)
	
+ Response 200
			[
			  {
				"depth": {
				  "level": 0,
				  "name": "Campus",
				  "id": 403
				},
				"name": "Houston Campus",
				"childCount": 1,
				"id": 1280,
				"category": {
				  "depths": [
					{
					  "level": 0,
					  "name": "Campus",
					  "id": 403
					},
					{
					  "level": 2,
					  "name": "Level 2",
					  "id": 419
					},
					{
					  "level": 3,
					  "name": "Level 3",
					  "id": 420
					},
					{
					  "level": 1,
					  "name": "Level 1",
					  "id": 418
					}
				  ],
				  "name": "Campus",
				  "id": 331
				},
				"parents": [

				]
			  },
			  {
				"code": "AC1 - Code",
				"depth": {
				  "level": 0,
				  "name": "Campus",
				  "id": 403
				},
				"name": "Austin Campus - Name",
				"childCount": 2,
				"id": 1281,
				"category": {
				  "depths": [
					{
					  "level": 0,
					  "name": "Campus",
					  "id": 403
					},
					{
					  "level": 2,
					  "name": "Level 2",
					  "id": 419
					},
					{
					  "level": 3,
					  "name": "Level 3",
					  "id": 420
					},
					{
					  "level": 1,
					  "name": "Level 1",
					  "id": 418
					}
				  ],
				  "name": "Campus",
				  "id": 331
				},
				"parents": [

				]
			  },
			  {
				"depth": {
				  "level": 0,
				  "name": "Campus",
				  "id": 403
				},
				"name": "San Antonio Campus",
				"childCount": 0,
				"id": 1282,
				"category": {
				  "depths": [
					{
					  "level": 0,
					  "name": "Campus",
					  "id": 403
					},
					{
					  "level": 2,
					  "name": "Level 2",
					  "id": 419
					},
					{
					  "level": 3,
					  "name": "Level 3",
					  "id": 420
					},
					{
					  "level": 1,
					  "name": "Level 1",
					  "id": 418
					}
				  ],
				  "name": "Campus",
				  "id": 331
				},
				"parents": [

				]
			  }
			]
			
## Level In Hierarchy [/categories/depths]
Level related resources of *iOffice API*

+ Model (application/json)
    JSON representation of the Category	Resource
	
## Add New Level In Hierarchy [POST]
+ Request (application/json)
			{ 	
				"name":"Unnamed Hierarchy Level",
				"category":{"id":492},
				"level":1
			}
			
+ Response 201
			{
			  "dateCreated": 1669814609962,
			  "level": 1,
			  "name": "Unnamed Hierarchy Level",
			  "id": 727,
			  "category": {
				"dateCreated": 1669834292027,
				"color": {

				},
				"name": "TestAdd",
				"id": 492,
				"dateUpdated": 1669812693803
			  }
			}

## Update Level In Hierarchy [PUT]
+ Parameters
    + id (string) ... ID of the Level/Depth
	
+ Request (application/json)
			{
				"id":{id},
				"name":"Level1"
			}
				
+ Response 200
			{
				"dateCreated": 1669815214240,
				"level": 1,
				"name": "UpdatedFromPMAN",
				"id": 730,
				"category": {
					"dateCreated": 1669836751583,
					"color": {},
					"name": "Newra",
					"id": 493,
					"dateUpdated": 1669815266397
				},
				"dateUpdated": 1669815401648
			}

## Delete Level In Hierarchy [DELETE /categories/depths/{id}]
+ Parameters
    + id (string) ... ID of the Level/Depth

+ Response 200
			{"response":"Successfully removed"}


## Space Types [/rooms/types]
Space Types related resources of *iOffice API*

+ Model (application/json)
    JSON representation of the Space Types Resource
   
### Retrieve Space Types [GET]
+ Parameters
    + includeParking (boolean, `true`) ... If true, query will include rooms with parking spaces

+ Response 200
			[	
				{
					"hexColor": "ffffff",
					"contentFlag": 1,
					"defaultRoomType": false,
					"cost": 0.0,
					"name": "5SW3.04",
					"id": 195,
					"spaceTypeGroup": {
					"hexColor": "cbcbcb",
					"roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": "ff"
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "Acc. WC",
								"id": 216,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "fffeb0",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "another type",
								"id": 170,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "8d55b0",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "AREA",
								"id": 52,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"spaceTypeClassification": {
								  "hexColor": "a55dbb",
								  "superCategory": {
									"name": "Service Area",
									"id": 1
								  },
								  "name": "Base Building Circulation",
								  "id": 21
								},
								"typeCode": "purple poop"
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "ATRIUM",
								"id": 97,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "f1bb6b",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "ATTIC STORAGE",
								"id": 53,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"spaceTypeClassification": {
								  "hexColor": "725eb6",
								  "superCategory": {
									"name": "Service Area",
									"id": 1
								  },
								  "name": "Building Common",
								  "id": 18
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "6595f8",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "BOARD ROOM",
								"id": 39,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"spaceTypeClassification": {
								  "hexColor": "abe3ed",
								  "superCategory": {
									"name": "Usable Area",
									"id": 3
								  },
								  "name": "Secondary Circulation",
								  "id": 15
								},
								"typeCode": "Building Services - May be outside lease perimeter"
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "Booth",
								"id": 213,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "BREAK OUT RM",
								"id": 155,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"spaceTypeClassification": {
								  "hexColor": "70605b",
								  "superCategory": {
									"name": "Other Area",
									"id": 4
								  },
								  "name": "Building Projections",
								  "id": 26
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "BREAK RM",
								"id": 141,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"spaceTypeClassification": {
								  "hexColor": "a55dbb",
								  "superCategory": {
									"name": "Service Area",
									"id": 1
								  },
								  "name": "Base Building Circulation",
								  "id": 21
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "d6ead3",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 2.0,
								"name": "BREAKROOM",
								"id": 23,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"spaceTypeClassification": {
								  "hexColor": "a55dbb",
								  "superCategory": {
									"name": "Service Area",
									"id": 1
								  },
								  "name": "Base Building Circulation",
								  "id": 21
								},
								"typeCode": "001"
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "Building Service",
								"id": 105,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "d15d81",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "BUTLER'S PANTRY",
								"id": 28,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": "45454545454545454545454545454545454545454545454545"
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "Circulation",
								"id": 222,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "CLASSROOM",
								"id": 66,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"spaceTypeClassification": {
								  "hexColor": "f1bb6b",
								  "superCategory": {
									"name": "Vertical Penetration",
									"id": 2
								  },
								  "name": "Building Core",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "f0a75d",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "CLOSET",
								"id": 30,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"spaceTypeClassification": {
								  "hexColor": "a55dbb",
								  "superCategory": {
									"name": "Service Area",
									"id": 1
								  },
								  "name": "Base Building Circulation",
								  "id": 21
								},
								"typeCode": "1102"
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "COATS",
								"id": 156,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "COFFEE",
								"id": 152,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "COLLAB",
								"id": 134,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "Collaboration Area",
								"id": 125,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "85bd7c",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "COMMUNICATION",
								"id": 9,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"spaceTypeClassification": {
								  "hexColor": "a55dbb",
								  "superCategory": {
									"name": "Service Area",
									"id": 1
								  },
								  "name": "Base Building Circulation",
								  "id": 21
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "75c5d9",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "CONF",
								"id": 3,
								"spaceTypeGroup": {
								  "hexColor": "fade6d",
								  "roomTypes": [
									{
									  "name": "CONF",
									  "id": 3
									},
									{
									  "name": "MULTI-PURPOSE ROOM",
									  "id": 35
									},
									{
									  "name": "CONFERENCE ROOM",
									  "id": 38
									},
									{
									  "name": "Vwilliams",
									  "id": 171
									}
								  ],
								  "name": "We Spaces",
								  "id": 3
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "CONF RM",
								"id": 65,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "694a9f",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "CONFERENCE",
								"id": 19,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"spaceTypeClassification": {
								  "hexColor": "a55dbb",
								  "superCategory": {
									"name": "Service Area",
									"id": 1
								  },
								  "name": "Base Building Circulation",
								  "id": 21
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "fdee80",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "CONFERENCE ROOM",
								"id": 38,
								"spaceTypeGroup": {
								  "hexColor": "fade6d",
								  "roomTypes": [
									{
									  "name": "CONF",
									  "id": 3
									},
									{
									  "name": "MULTI-PURPOSE ROOM",
									  "id": 35
									},
									{
									  "name": "CONFERENCE ROOM",
									  "id": 38
									},
									{
									  "name": "Vwilliams",
									  "id": 171
									}
								  ],
								  "name": "We Spaces",
								  "id": 3
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "8bdefc",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "Conference Room",
								"id": 79,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "Convenience Copy Center",
								"id": 109,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "COPIER ROOM",
								"id": 184,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": "dfdx"
							  },
							  {
								"hexColor": "cbedf4",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "COPY",
								"id": 50,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "COPY PRINT",
								"id": 138,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "d1f6d7",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "COPY/FAX",
								"id": 21,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "CORE",
								"id": 64,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "CORRIDOR",
								"id": 93,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "creating space",
								"id": 172,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "655652",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "CUBE",
								"id": 29,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "Dedicated Meeting Room",
								"id": 102,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "f8e079",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "DINING ROOM",
								"id": 37,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "ELEC",
								"id": 70,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "ELEC RM",
								"id": 90,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "ELEC. CL",
								"id": 148,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "85bd7c",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "ELECTRICAL",
								"id": 10,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": "c"
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "ELEV",
								"id": 143,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "ELEV EQUIP",
								"id": 139,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "eef6ee",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "ELEVATOR",
								"id": 48,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "bef7ad",
								"contentFlag": 1,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "Elevator Lobby",
								"id": 110,
								"spaceTypeGroup": {
								  "hexColor": "cbcbcb",
								  "roomTypes": [
									{
									  "name": "KITCHEN",
									  "id": 4
									},
									{
									  "name": "FILE",
									  "id": 5
									},
									{
									  "name": "wkst",
									  "id": 7
									},
									{
									  "name": "PRINTER-FAX",
									  "id": 8
									},
									{
									  "name": "COMMUNICATION",
									  "id": 9
									},
									{
									  "name": "ELECTRICAL",
									  "id": 10
									},
									{
									  "name": "STORAGE",
									  "id": 11
									},
									{
									  "name": "PARKING SPACE",
									  "id": 12
									},
									{
									  "name": "LIBRARY",
									  "id": 13
									},
									{
									  "name": "MECHANICAL",
									  "id": 14
									},
									{
									  "name": "TRAINING",
									  "id": 15
									},
									{
									  "name": "SAFETY",
									  "id": 16
									},
									{
									  "name": "CONFERENCE",
									  "id": 19
									},
									{
									  "name": "HOTELING",
									  "id": 20
									},
									{
									  "name": "COPY/FAX",
									  "id": 21
									},
									{
									  "name": "MEETING ROOM",
									  "id": 22
									},
									{
									  "name": "BREAKROOM",
									  "id": 23
									},
									{
									  "name": "Huddle",
									  "id": 24
									},
									{
									  "name": "RESTROOM",
									  "id": 27
									},
									{
									  "name": "CUBE",
									  "id": 29
									},
									{
									  "name": "WAR ROOM",
									  "id": 36
									},
									{
									  "name": "BOARD ROOM",
									  "id": 39
									},
									{
									  "name": "CONF RM",
									  "id": 65
									},
									{
									  "name": "HUDDLE RM",
									  "id": 75
									},
									{
									  "name": "Conference Room",
									  "id": 79
									},
									{
									  "name": "Focus Room",
									  "id": 80
									},
									{
									  "name": "IDF Closet",
									  "id": 81
									},
									{
									  "name": "LAB",
									  "id": 82
									},
									{
									  "name": "Pantry/Vending/Breakroom",
									  "id": 83
									},
									{
									  "name": "Printer/Copy/Mail",
									  "id": 84
									},
									{
									  "name": "PRINT/COPY",
									  "id": 87
									},
									{
									  "name": "WOMENS",
									  "id": 88
									},
									{
									  "name": "MENS",
									  "id": 91
									},
									{
									  "name": "CORRIDOR",
									  "id": 93
									},
									{
									  "name": "ATRIUM",
									  "id": 97
									},
									{
									  "name": "Walk-up WKST",
									  "id": 106
									},
									{
									  "name": "Elevator Lobby",
									  "id": 110
									},
									{
									  "name": "Collaboration Area",
									  "id": 125
									},
									{
									  "name": "Mail/Print",
									  "id": 129
									},
									{
									  "name": "Jans",
									  "id": 130
									},
									{
									  "name": "Jans-Admin",
									  "id": 131
									},
									{
									  "name": "ID3 Reservable Space",
									  "id": 157
									},
									{
									  "name": "TESTKB",
									  "id": 158
									},
									{
									  "name": "Lounge",
									  "id": 160
									},
									{
									  "name": "Lounge 2",
									  "id": 161
									},
									{
									  "name": "Wine Cellar",
									  "id": 162
									},
									{
									  "name": "Testing2",
									  "id": 164
									},
									{
									  "name": "1123",
									  "id": 166
									},
									{
									  "name": "testing group",
									  "id": 167
									},
									{
									  "name": "Patrick Check!",
									  "id": 169
									},
									{
									  "name": "another type",
									  "id": 170
									},
									{
									  "name": "creating space",
									  "id": 172
									},
									{
									  "name": "SabPa",
									  "id": 173
									},
									{
									  "name": "Sab",
									  "id": 174
									},
									{
									  "name": "Sabr",
									  "id": 175
									},
									{
									  "name": "SabPantry",
									  "id": 176
									},
									{
									  "name": "SabPantry",
									  "id": 177
									},
									{
									  "name": "New Space Type",
									  "id": 178
									},
									{
									  "name": "WORKSTATION",
									  "id": 179
									},
									{
									  "name": "WORKSTATION - EXECUTIVE",
									  "id": 180
									},
									{
									  "name": "PRIVACY/QUIET ROOM",
									  "id": 181
									},
									{
									  "name": "TELPHONE/DATA ROOM",
									  "id": 182
									},
									{
									  "name": "STORAGE - BUSINESS SUPPORT",
									  "id": 183
									},
									{
									  "name": "COPIER ROOM",
									  "id": 184
									},
									{
									  "name": "MISCELLANEOUS - PROPERTY COMMON",
									  "id": 185
									},
									{
									  "name": "FOOD SERVICE",
									  "id": 186
									},
									{
									  "name": "WORKROOM",
									  "id": 187
									},
									{
									  "name": "Space",
									  "id": 188
									},
									{
									  "name": "SE STAIR",
									  "id": 189
									},
									{
									  "name": "MECHANICAL ROOM",
									  "id": 190
									},
									{
									  "name": "MEN'S RESTROOM",
									  "id": 191
									},
									{
									  "name": "WOMEN'S RESTROOM",
									  "id": 192
									},
									{
									  "name": "vgvgv",
									  "id": 194
									},
									{
									  "name": "5SW3.04",
									  "id": 195
									},
									{
									  "name": "Type Test",
									  "id": 196
									},
									{
									  "name": "SPACES",
									  "id": 200
									},
									{
									  "name": "S-FLEX",
									  "id": 201
									},
									{
									  "name": "Project Space",
									  "id": 202
									},
									{
									  "name": "Large Meeting Room",
									  "id": 203
									},
									{
									  "name": "Standard Meeting Room",
									  "id": 204
									},
									{
									  "name": "Print Hub",
									  "id": 205
									},
									{
									  "name": "Relax Area",
									  "id": 206
									},
									{
									  "name": "Informal Collaboration Area",
									  "id": 207
									},
									{
									  "name": "Touchdown",
									  "id": 208
									},
									{
									  "name": "Workstations",
									  "id": 209
									},
									{
									  "name": "Small Meeting Room",
									  "id": 210
									},
									{
									  "name": "Lockers and Cloaks",
									  "id": 211
									},
									{
									  "name": "Phone Zone",
									  "id": 212
									},
									{
									  "name": "Booth",
									  "id": 213
									},
									{
									  "name": "Tea Point",
									  "id": 214
									},
									{
									  "name": "Social Space",
									  "id": 215
									},
									{
									  "name": "Acc. WC",
									  "id": 216
									},
									{
									  "name": "Male WCs",
									  "id": 217
									},
									{
									  "name": "Female WCs",
									  "id": 218
									},
									{
									  "name": "WC Lobby",
									  "id": 219
									},
									{
									  "name": "Quiet Room",
									  "id": 220
									},
									{
									  "name": "GWM Control Room",
									  "id": 221
									},
									{
									  "name": "Circulation",
									  "id": 222
									},
									{
									  "name": "Kitchen (Trading)",
									  "id": 223
									},
									{
									  "name": "Male WC",
									  "id": 224
									},
									{
									  "name": "Female WC",
									  "id": 225
									},
									{
									  "name": "Stair Lobby",
									  "id": 226
									},
									{
									  "name": "New Parking type",
									  "id": 227
									},
									{
									  "name": "Sergeo Test",
									  "id": 228
									},
									{
									  "name": "Rohan's Parking",
									  "id": 229
									},
									{
									  "name": "one",
									  "id": 230
									},
									{
									  "name": "one",
									  "id": 231
									},
									{
									  "name": "two",
									  "id": 232
									},
									{
									  "name": "two",
									  "id": 233
									},
									{
									  "name": "sa",
									  "id": 234
									},
									{
									  "name": "sa",
									  "id": 235
									},
									{
									  "name": "vxc",
									  "id": 236
									}
								  ],
								  "name": "None",
								  "id": 1
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "EQUIP",
								"id": 146,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "ffffff",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "EQUIPMENT",
								"id": 147,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "68aab7",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "EXECUTIVE DINING ROOM",
								"id": 34,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "5985c8",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "EXECUTIVE KITCHEN",
								"id": 33,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								  ],
								  "name": "Me Spaces",
								  "id": 2
								},
								"typeCode": ""
							  },
							  {
								"hexColor": "eb9d5f",
								"contentFlag": 3,
								"defaultRoomType": false,
								"cost": 0.0,
								"name": "EXPANSION    ",
								"id": 61,
								"spaceTypeGroup": {
								  "hexColor": "f29373",
								  "roomTypes": [
									{
									  "name": "WKST",
									  "id": 1
									},
									{
									  "name": "OFFICE",
									  "id": 2
									},
									{
									  "name": "RECEPTION",
									  "id": 6
									},
									{
									  "name": "VP room",
									  "id": 17
									},
									{
									  "name": "IT",
									  "id": 18
									},
									{
									  "name": "JANITORS CLOSET",
									  "id": 25
									},
									{
									  "name": "PANTRY",
									  "id": 26
									},
									{
									  "name": "BUTLER'S PANTRY",
									  "id": 28
									},
									{
									  "name": "CLOSET",
									  "id": 30
									},
									{
									  "name": "WOMEN",
									  "id": 31
									},
									{
									  "name": "MEN",
									  "id": 32
									},
									{
									  "name": "EXECUTIVE KITCHEN",
									  "id": 33
									},
									{
									  "name": "EXECUTIVE DINING ROOM",
									  "id": 34
									},
									{
									  "name": "DINING ROOM",
									  "id": 37
									},
									{
									  "name": "Lobby",
									  "id": 40
									},
									{
									  "name": "Inactive",
									  "id": 41
									},
									{
									  "name": "Telecom",
									  "id": 42
									},
									{
									  "name": "Waiting",
									  "id": 43
									},
									{
									  "name": "Inactive",
									  "id": 44
									},
									{
									  "name": "STAIR",
									  "id": 45
									},
									{
									  "name": "MALE",
									  "id": 46
									},
									{
									  "name": "FEMALE",
									  "id": 47
									},
									{
									  "name": "ELEVATOR",
									  "id": 48
									},
									{
									  "name": "PHONE",
									  "id": 49
									},
									{
									  "name": "COPY",
									  "id": 50
									},
									{
									  "name": "Inactive",
									  "id": 51
									},
									{
									  "name": "AREA",
									  "id": 52
									},
									{
									  "name": "ATTIC STORAGE",
									  "id": 53
									},
									{
									  "name": "STAIR 2      ",
									  "id": 54
									},
									{
									  "name": "NEWROOM      ",
									  "id": 55
									},
									{
									  "name": "ROOM         ",
									  "id": 56
									},
									{
									  "name": "Inactive",
									  "id": 57
									},
									{
									  "name": "Inactive",
									  "id": 58
									},
									{
									  "name": "Inactive",
									  "id": 59
									},
									{
									  "name": "STAIR 1      ",
									  "id": 60
									},
									{
									  "name": "EXPANSION    ",
									  "id": 61
									},
									{
									  "name": "NEW ROOM TYPE",
									  "id": 62
									},
									{
									  "name": "FLOOR SUPPORT",
									  "id": 63
									},
									{
									  "name": "CORE",
									  "id": 64
									},
									{
									  "name": "CLASSROOM",
									  "id": 66
									},
									{
									  "name": "PLAYROOM",
									  "id": 67
									},
									{
									  "name": "WKSTN",
									  "id": 68
									},
									{
									  "name": "Outlook HOTEL",
									  "id": 69
									},
									{
									  "name": "ELEC",
									  "id": 70
									},
									{
									  "name": "RISER",
									  "id": 71
									},
									{
									  "name": "JAN",
									  "id": 72
									},
									{
									  "name": "IDF",
									  "id": 73
									},
									{
									  "name": "WORK RM",
									  "id": 74
									},
									{
									  "name": "KITCHEN/LOUNGE",
									  "id": 76
									},
									{
									  "name": "KITCHEN/COPY",
									  "id": 77
									},
									{
									  "name": "MEETING RM",
									  "id": 78
									},
									{
									  "name": "Private room",
									  "id": 85
									},
									{
									  "name": "Workstation",
									  "id": 86
									},
									{
									  "name": "JAN RM",
									  "id": 89
									},
									{
									  "name": "ELEC RM",
									  "id": 90
									},
									{
									  "name": "FILE ROOM",
									  "id": 92
									},
									{
									  "name": "PRIMARY COORIDOR",
									  "id": 94
									},
									{
									  "name": "STAIRWELL",
									  "id": 95
									},
									{
									  "name": "KITCHENETTE",
									  "id": 96
									},
									{
									  "name": "MECH SHAFT",
									  "id": 98
									},
									{
									  "name": "FILE AREA",
									  "id": 99
									},
									{
									  "name": "STORAGE ROOM",
									  "id": 100
									},
									{
									  "name": "Wrkst",
									  "id": 101
									},
									{
									  "name": "Dedicated Meeting Room",
									  "id": 102
									},
									{
									  "name": "Phone Room",
									  "id": 103
									},
									{
									  "name": "Monumental Stair",
									  "id": 104
									},
									{
									  "name": "Building Service",
									  "id": 105
									},
									{
									  "name": "Project Room",
									  "id": 107
									},
									{
									  "name": "Fitness Center",
									  "id": 108
									},
									{
									  "name": "Convenience Copy Center",
									  "id": 109
									},
									{
									  "name": "Stairway",
									  "id": 111
									},
									{
									  "name": "Lobby/Reception",
									  "id": 112
									},
									{
									  "name": "Locker Room",
									  "id": 113
									},
									{
									  "name": "Room Support",
									  "id": 114
									},
									{
									  "name": "Mechanical Electrical Support Area",
									  "id": 115
									},
									{
									  "name": "Laboratory Storage",
									  "id": 116
									},
									{
									  "name": "Specialized Room",
									  "id": 117
									},
									{
									  "name": "Other Support",
									  "id": 118
									},
									{
									  "name": "Secondary Circulation",
									  "id": 119
									},
									{
									  "name": "Vertical Penetration",
									  "id": 120
									},
									{
									  "name": "Office-Exec.",
									  "id": 121
									},
									{
									  "name": "Primary Circulation",
									  "id": 122
									},
									{
									  "name": "Laboratory Support",
									  "id": 123
									},
									{
									  "name": "Laboratory",
									  "id": 124
									},
									{
									  "name": "Mail Services",
									  "id": 126
									},
									{
									  "name": "IDF/MDF",
									  "id": 127
									},
									{
									  "name": "Wrkst-Specialized",
									  "id": 128
									},
									{
									  "name": "FOCUS",
									  "id": 132
									},
									{
									  "name": "TEAM RM",
									  "id": 133
									},
									{
									  "name": "COLLAB",
									  "id": 134
									},
									{
									  "name": "SERVER RM",
									  "id": 135
									},
									{
									  "name": "WELLNESS",
									  "id": 136
									},
									{
									  "name": "SPECIALTY",
									  "id": 137
									},
									{
									  "name": "COPY PRINT",
									  "id": 138
									},
									{
									  "name": "ELEV EQUIP",
									  "id": 139
									},
									{
									  "name": "JANITOR",
									  "id": 140
									},
									{
									  "name": "BREAK RM",
									  "id": 141
									},
									{
									  "name": "WKSTN",
									  "id": 142
									},
									{
									  "name": "ELEV",
									  "id": 143
									},
									{
									  "name": "VESTIBULE",
									  "id": 144
									},
									{
									  "name": "TEL/DATA",
									  "id": 145
									},
									{
									  "name": "EQUIP",
									  "id": 146
									},
									{
									  "name": "EQUIPMENT",
									  "id": 147
									},
									{
									  "name": "ELEC. CL",
									  "id": 148
									},
									{
									  "name": "SERVER",
									  "id": 149
									},
									{
									  "name": "SHARE",
									  "id": 150
									},
									{
									  "name": "MED.",
									  "id": 151
									},
									{
									  "name": "COFFEE",
									  "id": 152
									},
									{
									  "name": "OFFICE-1P",
									  "id": 153
									},
									{
									  "name": "SMALL",
									  "id": 154
									},
									{
									  "name": "BREAK OUT RM",
									  "id": 155
									},
									{
									  "name": "COATS",
									  "id": 156
									},
									{
									  "name": "KBTEST",
									  "id": 159
									},
									{
									  "name": "Testing",
									  "id": 163
									},
									{
									  "name": "second test",
									  "id": 165
									},
									{
									  "name": "Patrick Check!",
									  "id": 168
									},
									{
									  "name": "WORKSTATION - HOTELING",
									  "id": 193
									}
								 ],
						"name": "Me Spaces",
						"id": 2
					},
					"typeCode": "    "
				}
			]
  
### Create Space Type [POST]
The following attributes are required to Create Space Type:

`name`, `contentFlag`, `typeCode`, `defaultRoomType`, `cost`, `spaceTypeGroup`

+ Request (application/json)
			{
				"name":"SpaceTypeAdd",
				"contentFlag":1,
				"typeCode":"",
				"defaultRoomType":false,
				"cost":0,
				"spaceTypeGroup":{"id":1}
			}
+ Response 201
			{
			  "hexColor": "ffffff",
			  "contentFlag": 1,
			  "defaultRoomType": false,
			  "cost": 0.0,
			  "sortOrder": 234,
			  "name": "SpaceTypeAdd",
			  "id": 238,
			  "spaceTypeGroup": {
				"hexColor": "cbcbcb",
				"roomTypes": [
							  {
								"name": "KITCHEN",
								"id": 4
							  },
							  {
								"name": "FILE",
								"id": 5
							  },
							  {
								"name": "wkst",
								"id": 7
							  },
							  {
								"name": "PRINTER-FAX",
								"id": 8
							  },
							  {
								"name": "COMMUNICATION",
								"id": 9
							  },
							  {
								"name": "ELECTRICAL",
								"id": 10
							  },
							  {
								"name": "STORAGE",
								"id": 11
							  },
							  {
								"name": "PARKING SPACE",
								"id": 12
							  },
							  {
								"name": "LIBRARY",
								"id": 13
							  },
							  {
								"name": "MECHANICAL",
								"id": 14
							  },
							  {
								"name": "TRAINING",
								"id": 15
							  },
							  {
								"name": "SAFETY",
								"id": 16
							  },
							  {
								"name": "CONFERENCE",
								"id": 19
							  },
							  {
								"name": "HOTELING",
								"id": 20
							  },
							  {
								"name": "COPY/FAX",
								"id": 21
							  },
							  {
								"name": "MEETING ROOM",
								"id": 22
							  },
							  {
								"name": "BREAKROOM",
								"id": 23
							  },
							  {
								"name": "Huddle",
								"id": 24
							  },
							  {
								"name": "RESTROOM",
								"id": 27
							  },
							  {
								"name": "CUBE",
								"id": 29
							  },
							  {
								"name": "WAR ROOM",
								"id": 36
							  },
							  {
								"name": "BOARD ROOM",
								"id": 39
							  },
							  {
								"name": "CONF RM",
								"id": 65
							  },
							  {
								"name": "HUDDLE RM",
								"id": 75
							  },
							  {
								"name": "Conference Room",
								"id": 79
							  },
							  {
								"name": "Focus Room",
								"id": 80
							  },
							  {
								"name": "IDF Closet",
								"id": 81
							  },
							  {
								"name": "LAB",
								"id": 82
							  },
							  {
								"name": "Pantry/Vending/Breakroom",
								"id": 83
							  },
							  {
								"name": "Printer/Copy/Mail",
								"id": 84
							  },
							  {
								"name": "PRINT/COPY",
								"id": 87
							  },
							  {
								"name": "WOMENS",
								"id": 88
							  },
							  {
								"name": "MENS",
								"id": 91
							  },
							  {
								"name": "CORRIDOR",
								"id": 93
							  },
							  {
								"name": "ATRIUM",
								"id": 97
							  },
							  {
								"name": "Walk-up WKST",
								"id": 106
							  },
							  {
								"name": "Elevator Lobby",
								"id": 110
							  },
							  {
								"name": "Collaboration Area",
								"id": 125
							  },
							  {
								"name": "Mail/Print",
								"id": 129
							  },
							  {
								"name": "Jans",
								"id": 130
							  },
							  {
								"name": "Jans-Admin",
								"id": 131
							  },
							  {
								"name": "ID3 Reservable Space",
								"id": 157
							  },
							  {
								"name": "TESTKB",
								"id": 158
							  },
							  {
								"name": "Lounge",
								"id": 160
							  },
							  {
								"name": "Lounge 2",
								"id": 161
							  },
							  {
								"name": "Wine Cellar",
								"id": 162
							  },
							  {
								"name": "Testing2",
								"id": 164
							  },
							  {
								"name": "1123",
								"id": 166
							  },
							  {
								"name": "testing group",
								"id": 167
							  },
							  {
								"name": "Patrick Check!",
								"id": 169
							  },
							  {
								"name": "another type",
								"id": 170
							  },
							  {
								"name": "creating space",
								"id": 172
							  },
							  {
								"name": "SabPa",
								"id": 173
							  },
							  {
								"name": "Sab",
								"id": 174
							  },
							  {
								"name": "Sabr",
								"id": 175
							  },
							  {
								"name": "SabPantry",
								"id": 176
							  },
							  {
								"name": "SabPantry",
								"id": 177
							  },
							  {
								"name": "New Space Type",
								"id": 178
							  },
							  {
								"name": "WORKSTATION",
								"id": 179
							  },
							  {
								"name": "WORKSTATION - EXECUTIVE",
								"id": 180
							  },
							  {
								"name": "PRIVACY/QUIET ROOM",
								"id": 181
							  },
							  {
								"name": "TELPHONE/DATA ROOM",
								"id": 182
							  },
							  {
								"name": "STORAGE - BUSINESS SUPPORT",
								"id": 183
							  },
							  {
								"name": "COPIER ROOM",
								"id": 184
							  },
							  {
								"name": "MISCELLANEOUS - PROPERTY COMMON",
								"id": 185
							  },
							  {
								"name": "FOOD SERVICE",
								"id": 186
							  },
							  {
								"name": "WORKROOM",
								"id": 187
							  },
							  {
								"name": "Space",
								"id": 188
							  },
							  {
								"name": "SE STAIR",
								"id": 189
							  },
							  {
								"name": "MECHANICAL ROOM",
								"id": 190
							  },
							  {
								"name": "MEN'S RESTROOM",
								"id": 191
							  },
							  {
								"name": "WOMEN'S RESTROOM",
								"id": 192
							  },
							  {
								"name": "vgvgv",
								"id": 194
							  },
							  {
								"name": "5SW3.04",
								"id": 195
							  },
							  {
								"name": "Type Test",
								"id": 196
							  },
							  {
								"name": "SPACES",
								"id": 200
							  },
							  {
								"name": "S-FLEX",
								"id": 201
							  },
							  {
								"name": "Project Space",
								"id": 202
							  },
							  {
								"name": "Large Meeting Room",
								"id": 203
							  },
							  {
								"name": "Standard Meeting Room",
								"id": 204
							  },
							  {
								"name": "Print Hub",
								"id": 205
							  },
							  {
								"name": "Relax Area",
								"id": 206
							  },
							  {
								"name": "Informal Collaboration Area",
								"id": 207
							  },
							  {
								"name": "Touchdown",
								"id": 208
							  },
							  {
								"name": "Workstations",
								"id": 209
							  },
							  {
								"name": "Small Meeting Room",
								"id": 210
							  },
							  {
								"name": "Lockers and Cloaks",
								"id": 211
							  },
							  {
								"name": "Phone Zone",
								"id": 212
							  },
							  {
								"name": "Booth",
								"id": 213
							  },
							  {
								"name": "Tea Point",
								"id": 214
							  },
							  {
								"name": "Social Space",
								"id": 215
							  },
							  {
								"name": "Acc. WC",
								"id": 216
							  },
							  {
								"name": "Male WCs",
								"id": 217
							  },
							  {
								"name": "Female WCs",
								"id": 218
							  },
							  {
								"name": "WC Lobby",
								"id": 219
							  },
							  {
								"name": "Quiet Room",
								"id": 220
							  },
							  {
								"name": "GWM Control Room",
								"id": 221
							  },
							  {
								"name": "Circulation",
								"id": 222
							  },
							  {
								"name": "Kitchen (Trading)",
								"id": 223
							  },
							  {
								"name": "Male WC",
								"id": 224
							  },
							  {
								"name": "Female WC",
								"id": 225
							  },
							  {
								"name": "Stair Lobby",
								"id": 226
							  },
							  {
								"name": "New Parking type",
								"id": 227
							  },
							  {
								"name": "Sergeo Test",
								"id": 228
							  },
							  {
								"name": "Rohan's Parking",
								"id": 229
							  },
							  {
								"name": "one",
								"id": 230
							  },
							  {
								"name": "one",
								"id": 231
							  },
							  {
								"name": "two",
								"id": 232
							  },
							  {
								"name": "two",
								"id": 233
							  },
							  {
								"name": "sa",
								"id": 234
							  },
							  {
								"name": "sa",
								"id": 235
							  },
							  {
								"name": "vxc",
								"id": 236
							  },
							  {
								"name": "SpaceTypeAdd",
								"id": 238
							  }
							],
				"name": "None",
				"id": 1
			  },
			  "typeCode": ""
			}
			
### Update Space Type [PUT]

The following attributes are required to Update Space Type:
hexColor, contentFlag, defaultRoomType, cost, sortOrder, name, id, spaceTypeGroup, typeCode
	
+ Request (application/json)
			{
			  "hexColor": "ffffff",
			  "contentFlag": 1,
			  "defaultRoomType": false,
			  "cost": 0,
			  "sortOrder": 234,
			  "name": "A1234",
			  "id": 238,
			  "spaceTypeGroup": {
				"id": 1
			  },
			  "typeCode": ""
			}
+ Response 200
			{
			  "hexColor": "ffffff",
			  "contentFlag": 1,
			  "defaultRoomType": false,
			  "cost": 0.0,
			  "sortOrder": 234,
			  "name": "A1234",
			  "id": 238,
			  "spaceTypeGroup": {
				"hexColor": "cbcbcb",
				"roomTypes": [
								  {
									"name": "KITCHEN",
									"id": 4
								  },
								  {
									"name": "FILE",
									"id": 5
								  },
								  {
									"name": "wkst",
									"id": 7
								  },
								  {
									"name": "PRINTER-FAX",
									"id": 8
								  },
								  {
									"name": "COMMUNICATION",
									"id": 9
								  },
								  {
									"name": "ELECTRICAL",
									"id": 10
								  },
								  {
									"name": "STORAGE",
									"id": 11
								  },
								  {
									"name": "PARKING SPACE",
									"id": 12
								  },
								  {
									"name": "LIBRARY",
									"id": 13
								  },
								  {
									"name": "MECHANICAL",
									"id": 14
								  },
								  {
									"name": "TRAINING",
									"id": 15
								  },
								  {
									"name": "SAFETY",
									"id": 16
								  },
								  {
									"name": "CONFERENCE",
									"id": 19
								  },
								  {
									"name": "HOTELING",
									"id": 20
								  },
								  {
									"name": "COPY/FAX",
									"id": 21
								  },
								  {
									"name": "MEETING ROOM",
									"id": 22
								  },
								  {
									"name": "BREAKROOM",
									"id": 23
								  },
								  {
									"name": "Huddle",
									"id": 24
								  },
								  {
									"name": "RESTROOM",
									"id": 27
								  },
								  {
									"name": "CUBE",
									"id": 29
								  },
								  {
									"name": "WAR ROOM",
									"id": 36
								  },
								  {
									"name": "BOARD ROOM",
									"id": 39
								  },
								  {
									"name": "CONF RM",
									"id": 65
								  },
								  {
									"name": "HUDDLE RM",
									"id": 75
								  },
								  {
									"name": "Conference Room",
									"id": 79
								  },
								  {
									"name": "Focus Room",
									"id": 80
								  },
								  {
									"name": "IDF Closet",
									"id": 81
								  },
								  {
									"name": "LAB",
									"id": 82
								  },
								  {
									"name": "Pantry/Vending/Breakroom",
									"id": 83
								  },
								  {
									"name": "Printer/Copy/Mail",
									"id": 84
								  },
								  {
									"name": "PRINT/COPY",
									"id": 87
								  },
								  {
									"name": "WOMENS",
									"id": 88
								  },
								  {
									"name": "MENS",
									"id": 91
								  },
								  {
									"name": "CORRIDOR",
									"id": 93
								  },
								  {
									"name": "ATRIUM",
									"id": 97
								  },
								  {
									"name": "Walk-up WKST",
									"id": 106
								  },
								  {
									"name": "Elevator Lobby",
									"id": 110
								  },
								  {
									"name": "Collaboration Area",
									"id": 125
								  },
								  {
									"name": "Mail/Print",
									"id": 129
								  },
								  {
									"name": "Jans",
									"id": 130
								  },
								  {
									"name": "Jans-Admin",
									"id": 131
								  },
								  {
									"name": "ID3 Reservable Space",
									"id": 157
								  },
								  {
									"name": "TESTKB",
									"id": 158
								  },
								  {
									"name": "Lounge",
									"id": 160
								  },
								  {
									"name": "Lounge 2",
									"id": 161
								  },
								  {
									"name": "Wine Cellar",
									"id": 162
								  },
								  {
									"name": "Testing2",
									"id": 164
								  },
								  {
									"name": "1123",
									"id": 166
								  },
								  {
									"name": "testing group",
									"id": 167
								  },
								  {
									"name": "Patrick Check!",
									"id": 169
								  },
								  {
									"name": "another type",
									"id": 170
								  },
								  {
									"name": "creating space",
									"id": 172
								  },
								  {
									"name": "SabPa",
									"id": 173
								  },
								  {
									"name": "Sab",
									"id": 174
								  },
								  {
									"name": "Sabr",
									"id": 175
								  },
								  {
									"name": "SabPantry",
									"id": 176
								  },
								  {
									"name": "SabPantry",
									"id": 177
								  },
								  {
									"name": "New Space Type",
									"id": 178
								  },
								  {
									"name": "WORKSTATION",
									"id": 179
								  },
								  {
									"name": "WORKSTATION - EXECUTIVE",
									"id": 180
								  },
								  {
									"name": "PRIVACY/QUIET ROOM",
									"id": 181
								  },
								  {
									"name": "TELPHONE/DATA ROOM",
									"id": 182
								  },
								  {
									"name": "STORAGE - BUSINESS SUPPORT",
									"id": 183
								  },
								  {
									"name": "COPIER ROOM",
									"id": 184
								  },
								  {
									"name": "MISCELLANEOUS - PROPERTY COMMON",
									"id": 185
								  },
								  {
									"name": "FOOD SERVICE",
									"id": 186
								  },
								  {
									"name": "WORKROOM",
									"id": 187
								  },
								  {
									"name": "Space",
									"id": 188
								  },
								  {
									"name": "SE STAIR",
									"id": 189
								  },
								  {
									"name": "MECHANICAL ROOM",
									"id": 190
								  },
								  {
									"name": "MEN'S RESTROOM",
									"id": 191
								  },
								  {
									"name": "WOMEN'S RESTROOM",
									"id": 192
								  },
								  {
									"name": "vgvgv",
									"id": 194
								  },
								  {
									"name": "5SW3.04",
									"id": 195
								  },
								  {
									"name": "Type Test",
									"id": 196
								  },
								  {
									"name": "SPACES",
									"id": 200
								  },
								  {
									"name": "S-FLEX",
									"id": 201
								  },
								  {
									"name": "Project Space",
									"id": 202
								  },
								  {
									"name": "Large Meeting Room",
									"id": 203
								  },
								  {
									"name": "Standard Meeting Room",
									"id": 204
								  },
								  {
									"name": "Print Hub",
									"id": 205
								  },
								  {
									"name": "Relax Area",
									"id": 206
								  },
								  {
									"name": "Informal Collaboration Area",
									"id": 207
								  },
								  {
									"name": "Touchdown",
									"id": 208
								  },
								  {
									"name": "Workstations",
									"id": 209
								  },
								  {
									"name": "Small Meeting Room",
									"id": 210
								  },
								  {
									"name": "Lockers and Cloaks",
									"id": 211
								  },
								  {
									"name": "Phone Zone",
									"id": 212
								  },
								  {
									"name": "Booth",
									"id": 213
								  },
								  {
									"name": "Tea Point",
									"id": 214
								  },
								  {
									"name": "Social Space",
									"id": 215
								  },
								  {
									"name": "Acc. WC",
									"id": 216
								  },
								  {
									"name": "Male WCs",
									"id": 217
								  },
								  {
									"name": "Female WCs",
									"id": 218
								  },
								  {
									"name": "WC Lobby",
									"id": 219
								  },
								  {
									"name": "Quiet Room",
									"id": 220
								  },
								  {
									"name": "GWM Control Room",
									"id": 221
								  },
								  {
									"name": "Circulation",
									"id": 222
								  },
								  {
									"name": "Kitchen (Trading)",
									"id": 223
								  },
								  {
									"name": "Male WC",
									"id": 224
								  },
								  {
									"name": "Female WC",
									"id": 225
								  },
								  {
									"name": "Stair Lobby",
									"id": 226
								  },
								  {
									"name": "New Parking type",
									"id": 227
								  },
								  {
									"name": "Sergeo Test",
									"id": 228
								  },
								  {
									"name": "Rohan's Parking",
									"id": 229
								  },
								  {
									"name": "one",
									"id": 230
								  },
								  {
									"name": "one",
									"id": 231
								  },
								  {
									"name": "two",
									"id": 232
								  },
								  {
									"name": "two",
									"id": 233
								  },
								  {
									"name": "sa",
									"id": 234
								  },
								  {
									"name": "sa",
									"id": 235
								  },
								  {
									"name": "vxc",
									"id": 236
								  },
								  {
									"name": "SpaceTypeAdd",
									"id": 237
								  },
								  {
									"name": "A1234",
									"id": 238
								  }
								],
							 "name": "None",
							 "id": 1
							},
				"typeCode": ""
			}
			
### Delete Space Type [DELETE]
+ Parameters
    + id (string) ... ID of the Space/room
    
+ Response 200
	
	{"response":"Successfully removed"}
          
### Reset Sort Order of Space Types [POST /rooms/types/resetSortOrders]
+ Request (application/json)
	{}
	
+ Response 200
    
	{"response":"Sort orders reset successfully"}
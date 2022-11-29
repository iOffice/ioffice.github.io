# Group Space

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
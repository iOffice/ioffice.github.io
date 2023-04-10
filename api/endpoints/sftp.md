# Group SFTP
SFTP Access related resources of *iOffice API*

## Setup SFTP Access [/sftp]

## Retrieve SFTP Details [GET]

+ Parameters
    + orderBy(`dateCreated`)
	+ orderByType(`desc`)
	+ selector(`cancelled%2Ccancelled%2CdateCreated%2CenteredBy%2Cexpired%2ClastUpdatedBy
	`%2CpasswordResetAllowed%2CpasswordResetRedeemed%2CrecipientEmail%2CrecipientName%2CsshKeyAllowed%2CsshKeyRedeemed`)

+ Response 200

    [
	  {
		"passwordResetAllowed": false,
		"dateCreated": 1672331684510,
		"expired": true,
		"cancelled": false,
		"recipientName": "Carlos Rojas",
		"sshKeyAllowed": true,
		"id": 51,
		"enteredBy": {
		  "name": "Customer Service",
		  "id": 1
		},
		"recipientEmail": "carlos.rojas@eptura.com"
	  },
	  {
		"passwordResetAllowed": false,
		"dateCreated": 1663693163523,
		"expired": true,
		"sshKeyRedeemed": 1663693232074,
		"cancelled": true,
		"recipientName": "Carlos Rojas",
		"sshKeyAllowed": true,
		"id": 45,
		"enteredBy": {
		  "name": "Customer Service",
		  "id": 1
		},
		"recipientEmail": "carlos.rojas@spaceiq.com"
	  },
	  {
		"passwordResetAllowed": false,
		"dateCreated": 1663688819606,
		"expired": true,
		"sshKeyRedeemed": 1663689320499,
		"cancelled": true,
		"recipientName": "Carlos Rojas",
		"sshKeyAllowed": true,
		"id": 44,
		"enteredBy": {
		  "name": "Customer Service",
		  "id": 1
		},
		"recipientEmail": "carlos.rojas@spaceiq.com"
	  },
	  {
		"passwordResetAllowed": true,
		"passwordResetRedeemed": 1658844365931,
		"dateCreated": 1658844224580,
		"expired": true,
		"cancelled": false,
		"recipientName": "Ashitosh Wagh",
		"sshKeyAllowed": false,
		"id": 43,
		"enteredBy": {
		  "name": "Admin Wagh",
		  "id": 3951
		},
		"recipientEmail": "ashitosh.wagh@spaceiq.com"
	  },
	  {
		"passwordResetAllowed": false,
		"dateCreated": 1648571513726,
		"expired": true,
		"cancelled": false,
		"recipientName": "Matthew",
		"sshKeyAllowed": true,
		"id": 42,
		"enteredBy": {
		  "name": "Customer Service",
		  "id": 1
		},
		"recipientEmail": "matthew.farmer@spaceiq.com"
	  }
	]

### Provide SFTP Access(Add SFTP User) [POST /sftp/create]

+ Parameters
   + selector (`cancelled%2Ccancelled%2CdateCreated%2CenteredBy%2Cexpired%2ClastUpdatedBy%2CpasswordResetAllowed
   `%2CpasswordResetRedeemed%2CrecipientEmail%2CrecipientName%2CsshKeyAllowed%2CsshKeyRedeemed`)

 + Request (application/json)

	{
	  "recipientName": "Rushikesh",
	  "recipientEmail": "Rushikesh.Mali@eptura.com",
	  "passwordResetAllowed": true,
	  "sshKeyAllowed": false
	}
	
+  Response 200
	
	{
	  "passwordResetAllowed": true,
	  "dateCreated": 1680625515742,
	  "expired": false,
	  "cancelled": false,
	  "recipientName": "Rushikesh",
	  "sshKeyAllowed": false,
	  "id": 54,
	  "enteredBy": {
		"name": "SiteAdmin 1234",
		"id": 3887
	  },
	  "recipientEmail": "Rushikesh.Mali@eptura.com"
	}
	

### Cancel SFTP Access Invite [PUT /sftp/{id}/cancel]

+ Request (application/json)
	{}

+ Response 200

	{
	  "passwordResetAllowed": true,
	  "dateCreated": 1680625515803,
	  "cancelled": true,
	  "recipientName": "Rushikesh",
	  "id": 54,
	  "sshKeyAllowed": false,
	  "recipientEmail": "Rushikesh.Mali@eptura.com",
	  "dateUpdated": 1680625971533
	}	

### SFTP Enabled [GET /sftp/enabled]

+ Response 200
	{"response":"dev_jcook_testing"}
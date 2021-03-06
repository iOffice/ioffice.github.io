FORMAT: X-1A
# iOffice API

# Group iOffice API
The iOffice API provides access to many iOffice modules for CRUD operations.

## Endpoints
The base URL will be https://`siteaddress`/external/api/rest/v2/

All endpoints in the document are relative to this url.

Note: The term "room" has been amended to "space"; all references to a "room" or "rooms" will now be referred to as a "space" or "spaces". This change does not affect current endpoints.  

## Authentication
In order to authenticate your request, in each request include the following in the request headers.
All requests are over **HTTPS**.

```http
x-auth-password: password
x-auth-username: username
```

## Media Types
Where applicable this API uses the JSON media-type to represent resources states and affordances.

Requests with a message-body are using plain JSON to set or update resource states.

## Error States
The common [HTTP Response Status Codes](https://github.com/for-GET/know-your-http-well/blob/master/status-codes.md) are used.

## Global Request Params
| Paramater  | Value |
| ------------- | ------------- |
| search | String to search for asset  |
| limit | maximum results to show (default: 50, maximum: 500). Obtain results beyond max with pagination: `startAt={nextResult}&limit={limit}`  |
| startAt | for pagination, the offset of where to start (default: 0)  |
| orderBy | Property to order results by (default: 'id')  |
| orderByType | Choose to order results in either ascending(`asc`) or descending(`desc`)order (default: 'asc')  |

Example usage to search users by employeeID:

https://`siteaddress`/external/api/rest/v2/users?search={employeeID}

## Resource Requests


NOTE: When updating a resource (with a `PUT` request), all that is needed is the ID of the object, and the value(s) you wish to update.
        
* e.g. Updating a resource's `printerName` to another, when that resource's `id` is `5`.

Headers

`Content-Type: application/json`

Body
```
{
	"id": 5,
	"printerName": "NEW PRINTER TEST NAME"
}
```
Response `200`


Note: Many of the `List of all XXXX` endpoints that return a collection have a `/count` variation that will return the number of available records. All parameters supported by the main endpoint are supported by the `/count` endpoint. 


+ e.g. To retrieve the total number of users available: `/users/count`
	
+ e.g. To retrieve the total number of category items available: `/categories/items/count`

+ e.g. To retrieve the total number of buildings in a city: `/buildings/count?locationSearch={city,state}`
	


<!-- include(endpoints/user.md) -->

<!-- include(endpoints/move.md) -->

<!-- include(endpoints/mail.md) -->

<!-- include(endpoints/contact.md) -->

<!-- include(endpoints/building.md) -->

<!-- include(endpoints/country.md) -->

<!-- include(endpoints/floor.md) -->

<!-- include(endpoints/room.md) -->

<!-- include(endpoints/asset.md) -->

<!-- include(endpoints/reservation.md) -->

<!-- include(endpoints/maintenance.md) -->

<!-- include(endpoints/agreement.md) -->

<!-- include(endpoints/categoryitem.md) -->

<!-- include(endpoints/category.md) -->

<!-- include(endpoints/categorydepth.md) -->

<!-- include(endpoints/savedsearch.md) -->

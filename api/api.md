FORMAT: X-1A
# iOffice API

# Group iOffice API
The iOffice API provides access to many iOffice modules for CRUD operations

## Endpoints
The base URL will be https://`siteaddress`/external/api/rest/v2/

All endpoints in the document are relative to this url.

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
| limit | maximum results to show (default: 50)  |
| startAt | for pagination, the offset of where to start (default: 0)  |
| orderBy | Property to order results by (default: 'id')  |
| orderByType | Choose to order results in either ascending(`asc`) or descending(`desc`)order (default: 'asc')  |

## Resource Requests
NOTE: When creating/updating an object, all that is needed is the ID of new object
        
    e.g. Updating a resource's contact to another with an ID of 5
    + Request (application/json)
        {
            contact: {
                id: 5
            }
        }


<!-- include(endpoints/user.md) -->

<!-- include(endpoints/move.md) -->

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

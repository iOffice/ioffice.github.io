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
| limit | maximum results to show (default: 50, maximum: 100).  |
| startAt | for pagination, the offset of where to start (default: 0)  |
| orderBy | Property to order results by (default: 'id')  |
| orderByType | Choose to order results in either ascending(`asc`) or descending(`desc`)order (default: 'asc')  |

Example usage to search users by employeeID:

https://`siteaddress`/external/api/rest/v2/users?search={employeeID}

## Pagination
Obtain results beyond max with pagination using the `limit` and `startAt` query parameters: `startAt={nextResult}&limit={limit}`

It is recommended to implement pagination on all requests, and to limit page sizes to ensure the best possible performance.

An example using rooms:
* `/external/api/rest/v2/rooms/?limit=10&startAt=0`
* `/external/api/rest/v2/rooms/?limit=10&startAt=10`

You can implement a stop to pagination by checking the result set. If the `limit` is 10, and the response contains 10 records, you can request the next page by increasing your `startAt` by 10. If your `limit` is 10, but your response contains less than 10 records, it is not necessary to request the next page.

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

## API Usage Best Practices
This API is fantastic tool to create customizations that enhance and extend the
iOFFICE product. In order to have the best integration experience, we recommend
following these industry best practices.

1. *Restrict requests to needed data.* Where possible, use of tools that limit
   the response body to just what is needed will provide a faster response.
2. *Implement retry logic and backoff policies.* Any service may experience an
   intermittent error. Retrying a request on a 500 (or similar) response status
   code, with backoff, will provide a more robust integration experience.
3. *Leverage the use of pagination.* Limiting page sizes, even to smaller that
   the default page size, can overcome a variety of issues. In addition,
   smaller pages will provide a faster response.
4. *Make sequential, as opposed to parrallel, page requests.* Queueing up a set of
   requests to get multiple pages of data at once, will result in getting 429
   response status code. This also leads to other poor API integration
   experiences. Making calls sequentially allows you to get fast incremental
   responses. UI's can be updated to display results as they come, enabling a
   better user experience.
5. *Request data at each collection level.* In cases of heirarchy or nested data, making
   multiple requests, one to ecah data level, is best practice. This allows you
   to cache common elements, reduce payload size, and number of overall
   requsets.
6. *Implement local logging.* Local logging will allow you to log interactions with
   the API that contain the specific context of your application. This facilitates
   faster troubleshooting and resolution should there be a persistent issue.


<!-- include(endpoints/user.md) -->

<!-- include(endpoints/visitor.md) -->

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

<!-- include(endpoints/space.md) -->

<!-- include(endpoints/centers.md) -->

<!-- include(endpoints/neighborhoods.md) -->
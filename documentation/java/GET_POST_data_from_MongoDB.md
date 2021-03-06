# GET/POST data from MongoDB

This task is designed to create new 2 endpoints which will implement reading and writing functionality to/from the MongoDB.

## Task

The task will implement the storage of a User object in the MongoDB. A User will have 3 fields of information, an ID and their "firstName" and "lastName" stored. In order to complete the task, the following is required:

-   A new "GET /users" endpoint, which will return a JSON object containing the 3 mandatory fields e.g.

>     [
>        {
>           "id":1,
>           "firstName":"Dave",
>           "lastName":"Smith"
>        },
>        {
>           "id":2,
>           "firstName":"Mary",
>           "lastName":"McDonald"
>        }
>     ]

-   A new "POST /users" endpoint, allowing the writing of a single USER to the MongoDB and requiring the 2 fields: firstName and lastName. The ID should be automatically assigned by the database e.g.

>     {
>        "firstName":"Dave",
>        "lastName":"Smith"
>     }

-   Unit tests and integration tests for the new methods.
-   Check that the swagger documentation has been updated and that the endpoints can be called using Postman or a CURL command (available from Swagger).

## Extra Help - Mongo DB

<https://www.tutorialspoint.com/mongodb/index.htm>

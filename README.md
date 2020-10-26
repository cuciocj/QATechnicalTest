# QATechnicalTest
This repo is for QA analyst assignment for Freightways Information Services

## Solution
- Expect if the response status code is 200 (GET, PUT, DELETE) or 201 (POST).
- Expect if the json response is of type array (GET /posts) or is of type object (GET /posts/1, POST, PUT, DELETE).
- Expect if the json response has the correct keys/properties.
- Expect if each of json properties are in correct data types.
- Number properties such as id and userId must be greater than zero.
- Added schema validation for each request.

# Exam Call 2

## Structure

The structure of this repository is the following:
  - [JSON Schemas](./JSON%20Schemas) contains the design of the JSON Schemas;
  - [REST APIs Design](./REST%20APIs%20Design) contains the full Open API documentation of the REST APIs, including examples of JSON documents to be used when invoking the operations;
  - [ToDoManager Implementation](./ToDoManager%20Implementation) contains the code of the ToDoManager service application.

## ToDoManager Service - Instructions

### Overview

This server was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.  By using the [OpenAPI-Spec](https://github.com/OAI/OpenAPI-Specification) from a remote server, you can easily generate a server stub.

### Running the server - Linux

To install dependencies and to launch the server:

```bash
distributed-exam> cd ./ToDoManager\ Implementation
distributed-exam/ToDoManager Implementation> npm start
```

To view the Swagger UI interface:
open the [docs](http://localhost:3000/docs) link

Database can be visualised by means of https://sqlitebrowser.org/ by importing:
[distributed-exam/ToDoManager Implementation/database/databaseV2.db](./ToDoManager%20Implementation/database/databaseV2.db)

To test the app, use the following credentials:
- Username: user.dsp@polito.it
- Password: password


To set the number of items in each page of the pagination mechanism, change the OFFSET variable in:
[distributed-exam/ToDoManager Implementation/utils/constants.js](./ToDoManager%20Implementation/utils/constants.js).

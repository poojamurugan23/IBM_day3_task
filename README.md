STUDENT MANAGEMENT SYSTEM REST API


PROJECT OVERVIEW

This project is a Student Management System RESTful API developed using Node.js and Express.js.

It provides endpoints to perform CRUD (Create, Read, Update, Delete) operations on student data with support for both single and bulk requests.

The project uses in-memory data storage and follows RESTful API design principles.


FEATURES

RESTful API using Express.js

Create, Read, Update, and Delete operations

Single and bulk student processing

Partial updates supported

Duplicate student ID validation

Proper HTTP status codes and error handling

In-memory data storage using arrays


TECHNOLOGIES USED

Node.js

Express.js

JavaScript


PROJECT STRUCTURE

student-database/

├── index.js

├── routers/

│   └── studentRouters.js

├── package.json

├── package-lock.json

├── .gitignore

└── README.md


API ENDPOINTS

Health Check

GET /

Returns a message to confirm the server is running.

Read Students

GET /students

Fetches all student records.

Create Student

POST /students

Creates a single student record.

Create Multiple Students

POST /students/bulk

Creates multiple student records in one request.

Update Student

PUT /students/:id

Updates a single student (partial update supported).

Update Multiple Students

PUT /students

Updates multiple students at once.

Delete Student

DELETE /students/:id

Deletes a single student by ID.

Delete Multiple Students

DELETE /students

Deletes multiple students using an array of IDs.


TESTING

All API endpoints were tested using API testing tools

CRUD operations were verified

Bulk operations were tested for partial success handling


WHAT I LEARNED

Building RESTful APIs with Express.js

Implementing CRUD operations

Handling bulk data operations

Validating input data

Managing in-memory data storage

Proper error handling in APIs

CHALLENGES SOLVED

Implemented partial success handling for bulk operations
Prevented duplicate student records
Efficient array manipulation for data management

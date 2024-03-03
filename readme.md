# API Documentation

## Base URL
All endpoints should be appended to the base URL:
http://localhost:3000

## Students
http://localhost:3000/students

### Get Students
Retrieve a list of all students.

**Endpoint: GET /students**
http://localhost:3000/students


### Post Students
Create a new student

**Request Body:**
{
  "name": "Mike Smith",
  "age": 26,
  "average": 78.3
}

**Endpoint: Post /students**
http://localhost:3000/students


### Update Students
Update a specific student by ID.

**Request Body:**
{
  "name": "Updated Name",
  "age": 35,
  "average": 78.3
}

**Endpoint: Put /students**
http://localhost:3000/students/:id


### Patch Students
Partially update a specific student by ID.

**Request Body:**
{
  "age": 35
}

**Endpoint: Patch /students**
http://localhost:3000/students/:id

### Delete Student
Remove a specific student by ID.

**Endpoint: Delete /student**
http://localhost:3000/students/:id
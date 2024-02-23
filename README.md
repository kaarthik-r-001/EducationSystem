# Educational Institution Database
This is a backend database for a school or university that handles student enrollment and course scheduling. The project was built using Maven, Spring, Spring Boot, MySQL, and Spring Controller.

## Team 3
The project was built by Team 3: Ben George Netto, Gopal S, Kaarthik R, Jogi Lokesh Kumar, Sreelekshmi R.

## Implemented Features
The following features have been implemented in this project:
- Student enrollment management.
- Course scheduling and management.
- CRUD operations for all entities.
## Entities
The following entities have been included in this project:

#### Student
- contains information about the students in the institution.

#### Course
- contains information about the courses offered by the institution.
## Backend Endpoints List
The following is a list of backend endpoints that have been implemented in this project:

#### GET /students
- gets a list of all students.

#### GET /students/{id}
- gets the details of a specific student.

#### POST /students
- creates a new student.

#### PUT /students/{id}
- updates the details of a specific student.

#### DELETE /students/{id}
- deletes a specific student.

#### GET /courses
- gets a list of all courses.

#### GET /courses/{id}
- gets the details of a specific course.

#### POST /courses
- creates a new course

#### PUT /courses/{id}
- updates the details of a specific course.

#### DELETE /courses/{id}
- deletes a specific course.
## ER Diagram
The following is an ER diagram for the Educational Institution Database:
[Insert ER Diagram here]
## How to Install and Run
To install and run this project, follow these steps:
1. Clone the repository onto your local machine.
2. Ensure that you have Maven and MySQL installed.
3. Create a new MySQL database called: user_reg.
4. Update the: application.yaml file with your MySQL database credentials.
5. Navigate to the project directory and run mvn spring-boot:run to start the server.
6. The server will be running at http://localhost:8080.

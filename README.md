Student Management API
The Student Management API is a RESTful web service built using Spring Boot that enables efficient management of student records.
It provides endpoints to perform CRUD operations (Create, Read, Update, Delete) and integrates seamlessly with a relational database using Spring Data JPA.

Features :
Create a new student record
Retrieve all students
Get student details by ID
Update existing student information
Delete student records
RESTful API design with JSON responses
Basic validation and error handling

Tech Stack:
Java
Spring Boot
Spring Data JPA (Hibernate)
MySQL
Lombok

Architecture:
The application follows a layered architecture:
Controller Layer – Handles HTTP requests and responses
Service Layer – Contains business logic
Repository Layer – Manages database operations
Entity Layer – Maps Java objects to database tables

API Endpoints:
Method	Endpoint	Description
POST	/students:	Create a new student
GET	/students	: Get all students
GET	/students/{id}:	Get student by ID
PUT	/students/{id}:	Update student
DELETE	/students/{id}:	Delete student

Database Schema:
Table: student
id (Primary Key)
name
email
age

Workflow:
Client → Controller → Service → Repository → Database → Response (JSON)

Purpose:
This project demonstrates the implementation of REST APIs using Spring Boot and serves as a foundational backend project for learning and practice.

Experiment 9 – Student Records Management System API

This project is a Spring Boot–based REST API for managing student records. It supports full CRUD operations and uses an in-memory H2 database.

Features

-Add new students

-View all students

-View student by ID

-Update student details

-Delete student

In-memory H2 database with auto table creation

Tested using Postman

Tech Stack

-Spring Boot

-Spring Web

-Spring Data JPA

-H2 Database

-Maven

-Postman

Run the Application
mvn spring-boot:run


H2 Console:
http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:studentdb

API Endpoints
Method  	Endpoint	         Description
GET	     /api/students     	Get all students
GET	    /api/students/{id}	Get student by ID
POST	  /api/students	      Add new student
PUT	   /api/students/{id}	  Update student
DELETE /api/students/{id}	  Delete student

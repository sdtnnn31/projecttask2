Spring Framework – Task 1 & Task 2
Description

This repository contains two Spring Boot applications created using the Spring Framework.

Task 1 – Spring MVC web application

Task 2 – Spring Boot REST API application

Both applications are fully functional and tested.

🔹 Task 1 – Spring MVC Application

Task 1 demonstrates:

Spring MVC

Controllers

Thymeleaf templates

Static resources

How to run
http://localhost:8080/greeting


The application displays a greeting page with text and an image.

🔹 Task 2 – Spring Boot REST API

Task 2 demonstrates:

REST controllers

CRUD operations

Spring Data JPA

H2 in-memory database

Swagger UI

Endpoints

POST /users – create user

GET /users – get all users

GET /users/{id} – get user by id

DELETE /users/{id} – delete user

Example JSON
{
  "name": "Dastan",
  "email": "dastan@mail.com"
}

Swagger
http://localhost:8080/swagger-ui/index.html


Swagger is used to test all REST endpoints.

Database

H2 in-memory database is used.

H2 Console:

http://localhost:8080/h2-console


Example query:

SELECT * FROM USERS;

Repository

Projects are stored on GitHub

.gitignore is included

Only required files are committed

Summary

✔ Spring MVC application
✔ REST API with CRUD
✔ Swagger testing
✔ Database queries
✔ GitHub repository

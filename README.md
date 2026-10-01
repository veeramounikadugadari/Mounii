# Java Full Stack Student Management System

## Technologies
- Java 17
- Spring Boot
- Spring MVC / REST
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- HTML, CSS, JavaScript

## Setup

1. Install Java 17+, Maven, and MySQL.
2. Create the database:
   CREATE DATABASE studentdb;
3. Open `src/main/resources/application.properties`.
4. Replace `YOUR_MYSQL_PASSWORD` with your MySQL password.
5. Run:
   `mvn spring-boot:run`
6. Open:
   `http://localhost:8080`

The application automatically creates the `students` table using JPA.

## API
GET    /api/students
GET    /api/students/{id}
POST   /api/students
PUT    /api/students/{id}
DELETE /api/students/{id}

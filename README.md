# Student REST API

A Spring Boot REST API for managing student records (CRUD).

## Tech Stack
- Java 17 (check your pom.xml)
- Spring Boot 4.1.1
- Spring Data JPA / Hibernate
- MySQL 8.0
- Maven
- Lombok

## API Endpoints
| Method | URL | Description |
|---|---|---|
| GET | /students | Get all students |
| POST | /students | Add a student |
| PUT | /students/{id} | Update a student |
| DELETE | /students/{id} | Delete a student |

## How to Run
1. Install JDK and MySQL.
2. Create the database: `CREATE DATABASE studentdb;`
3. In `src/main/resources/application.properties`, set your MySQL username and password.
4. Run `StudentApiApplication` from your IDE, or use `mvnw spring-boot:run`.
5. Test the APIs with Postman at `http://localhost:8080/students`.

# Product Service - Spring Boot Microservice

##  Module
SE4010 – Current Trends in Software Engineering  
SLIIT – Faculty of Computing

## Project Description
This project is a Spring Boot microservice that provides RESTful APIs for managing products.  
It uses:

- Spring Boot
- Spring Web
- Spring Data JPA
- H2 In-Memory Database
- Swagger (OpenAPI)

---

##  Technologies Used

- Java 17
- Spring Boot
- Maven
- H2 Database
- Springdoc OpenAPI (Swagger)

---

## Project Structure

- `model` → Contains Product entity
- `repository` → Contains JpaRepository interface
- `controller` → Contains REST API endpoints

---

## REST API Endpoints

| Method | Endpoint | Description |
|--------|----------|------------|
| POST   | /products | Create new product |
| GET    | /products | Get all products |
| GET    | /products/{id} | Get product by ID |
| DELETE | /products/{id} | Delete product by ID |

---

##  H2 Database

H2 is configured as an in-memory database.

### Access H2 Console:
http://localhost:8080/h2-console


JDBC URL:
jdbc:h2:mem:testdb


---

## Swagger API Documentation

Swagger UI is enabled using Springdoc OpenAPI.

### Access Swagger:
http://localhost:8080/swagger-ui.html


OR

http://localhost:8080/swagger-ui/index.html


---

## How to Run the Project

1. Clone the repository
2. Open in IntelliJ / Eclipse
3. Run `ProductServiceApplication.java`
4. Access APIs using Swagger UI

---



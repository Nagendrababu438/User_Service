# User Service - Spring Boot Microservice

This project is a **User Service** built using **Java Spring Boot**, part of a microservices-based architecture. It provides RESTful APIs for managing user-related operations such as registration, authentication, profile management, and more.

---

## 🔧 Tech Stack

- Java 17+
- Spring Boot
- Spring Web
- Spring Data JPA
- Hibernate
- MySQL 
- Spring Security (Optional JWT-based)
- Maven
---
📬 API Endpoints
Method	Endpoint	Description
POST	/api/users/register	Register a new user
POST	/api/users/login	Authenticate user
GET	/api/users/{id}	Get user by ID
PUT	/api/users/{id}	Update user details
DELETE	/api/users/{id}	Delete a use
--------
🧪 Testing
mvn test
-------
Run the Application
mvn clean install
mvn spring-boot:run

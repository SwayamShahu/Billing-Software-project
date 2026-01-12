# Spring Boot RESTful API Application

## Overview
This project is a Spring Boot–based RESTful API application designed to manage core business entities such as Customers, Products, Orders, and Invoices. It follows a layered architecture and implements standard REST principles for scalable backend development.

## Features
- Customer management (Create, Update, View)
- Product management with search and filter
- Order creation and status updates
- Invoice generation
- RESTful API implementation using Spring Boot
- In-memory data storage using Java collections
- API testing using Postman

## Technologies Used
Java, Spring Boot, Spring MVC, RESTful APIs, Maven, Jackson, Apache Tomcat, and Postman.

## Architecture
The application follows a layered architecture:
- Controller Layer – Handles HTTP requests and responses
- Service Layer – Contains business logic
- Repository Layer – Manages in-memory data storage

## API Modules
Customer  - /customer  
Product   - /products  
Order     - /order  
Invoice   - /invoice  

Supports HTTP methods: GET, POST, PUT, DELETE

## How to Run
1. Clone the repository
2. Open the project in Eclipse or IntelliJ
3. Ensure Java and Maven are installed
4. Run the application as a Spring Boot Application
5. Access APIs at http://localhost:8080

## Testing
All REST APIs were tested using Postman by validating requests, responses, and status codes.

## Challenges Faced
Handling JSON request validation and managing null values for primitive data types.

## Future Enhancements
- Database integration using Spring Data JPA and MySQL
- Input validation using Hibernate Validator
- Global exception handling
- Swagger API documentation
- Authentication and authorization

## Conclusion
This project demonstrates a clean implementation of RESTful web services using Spring Boot with proper architectural design and testing practices.

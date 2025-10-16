# ShowSeats – Movie Ticket Booking System

**ShowSeats** is a backend RESTful API for managing **movie/show ticket bookings** with **seat allocation**. Built with **Spring Boot, MySQL, and JWT**, it demonstrates **secure authentication, clean DTO-based API design, custom exception handling**, and best practices in Spring Boot application development.

---

## Features
- **User Registration & Authentication** – Users can register, log in, and manage their profiles using **JWT-based authentication**.
- **Movie Management** – Admins can add, edit, and remove movies.
- **Theater Management** – Admins can add theaters, manage seats, and update theater information.
- **Ticket Booking** – Users can browse movies, select a show, and book tickets.
- **Seat Selection** – Users can select preferred seats for a show, ensuring real-time availability.
- **Booking History** – Users can view their past bookings and ticket details.
- **Robust Exception Handling** – Custom exceptions ensure maintainable error responses.
- **DTO-Based API** – Clean separation between entities and API responses.

---

## Technologies Used
- **Language:** Java 17+  
- **Framework:** Spring Boot 3.3  
- **Database:** MySQL  
- **Security:** Spring Security + JWT  
- **Build Tool:** Maven  
- **Testing:** JUnit, Mockito  
- **Other:** Swagger UI for API documentation  

---

## Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DipanshuSehgal270/ShowSeats.git
   cd ShowSeats

Create a MySQL database:
Name it moviesystemdatabase.

Update database properties:
Edit src/main/resources/application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/moviesystemdatabase
spring.datasource.username=YOUR_DB_USERNAME
spring.datasource.password=YOUR_DB_PASSWORD


Build the project:

mvn clean install


Run the application:

mvn spring-boot:run


Access the APIs:
http://localhost:8080

API Documentation

Swagger UI: http://localhost:8080/swagger-ui/index.html

Provides request/response examples for all endpoints including user, movie, theater, and ticket management.

Project Highlights

Implements JWT authentication for secure access.

Uses DTOs to separate database entities from API responses.

Features custom exception handling for clean error messages.

Follows Spring Boot best practices, including layered architecture and service-repository separation.

Future Improvements

Add payment gateway integration for ticket purchases.

Implement email notifications for booking confirmation.

Expand to multi-city theater management.

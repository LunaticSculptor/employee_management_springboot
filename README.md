# Review Management System - Spring Boot Microservices

A simple Review Management System built using Spring Boot microservices architecture. Users can register, log in, and give reviews (ratings + comments) for employees.

## 🛠 Tech Stack

- Spring Boot
- Spring Cloud (Eureka, Gateway)
- Spring Security (JWT)
- Spring Data JPA
- MySQL / H2
- Docker (Project can be run using docker images of each service)

## 🧩 Microservices

- **API Gateway** – Routes requests to services
- **Eureka Server** – Service discovery
- **User Service** – Handles registration, login (with JWT), and user data
- **Employee Service** – Manages employee records
- **Review Service** – Manages reviews by users for employees

## 🔐 Security

- JWT-based authentication
- Role-based access (Admin/User/HR)


> All services register with Eureka and are accessed via API Gateway.

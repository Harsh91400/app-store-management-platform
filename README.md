<h1 align="center">🚀 App Store Management Platform</h1>

<p align="center">
A Microservices-Based App Store Management Platform developed using <b>Java</b>, <b>Spring Boot</b>, <b>Spring Security</b>, <b>JWT Authentication</b>, <b>Spring Data JPA</b>, <b>Eureka Server</b>, and <b>MySQL</b>.
</p>

<p align="center">

![Java](https://img.shields.io/badge/Java-21-orange)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-Framework-brightgreen)
![Spring Security](https://img.shields.io/badge/Spring_Security-JWT-success)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue)
![Maven](https://img.shields.io/badge/Maven-Build-red)
![Git](https://img.shields.io/badge/Git-Version_Control-orange)

</p>

---

# 📖 Project Overview

The **App Store Management Platform** is a microservices-based backend application that simulates an enterprise application marketplace. The platform enables users to securely register, log in, browse and download applications, while application owners can manage their applications and administrators can manage the overall platform.

The project follows a layered architecture using **Spring Boot**, **Spring Security**, **JWT Authentication**, **Spring Data JPA**, and **Spring Cloud Eureka** for service discovery.

---

# ✨ Features

- Secure User Registration & Login
- JWT-Based Authentication
- Role-Based Authorization (RBAC)
- Admin Module
- App Owner Module
- User Dashboard
- Application Management
- Download Management
- RESTful APIs
- Spring Data JPA Integration
- Service Discovery using Eureka Server
- Maven Build Management

---

# 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Programming Language | Java |
| Framework | Spring Boot |
| Security | Spring Security, JWT Authentication |
| Database | MySQL |
| ORM | Spring Data JPA |
| Service Discovery | Spring Cloud Eureka |
| Build Tool | Maven |
| Version Control | Git & GitHub |

---

# 🏗 System Architecture

```text
                    Client
                       │
                HTTP Requests
                       │
              Spring Security
               JWT Authentication
                       │
               Controller Layer
                       │
                Service Layer
                       │
              Repository Layer
                       │
                  MySQL Database
                       │
                 Eureka Server
```

---

# 📦 Project Structure

```text
spring-eureka-project
│
├── app-service
├── frontend-service
├── notification-service
└── eureka-server
```

---

# 📁 Backend Structure

```text
src
└── main
    ├── java
    │
    ├── controller
    ├── service
    ├── repository
    ├── entity
    ├── dto
    ├── security
    ├── config
    ├── exception
    └── util
    │
    └── resources
        └── application.properties
```

---

# 👥 User Roles

## 👤 User

- Register
- Login
- Browse Applications
- Download Applications
- View Dashboard

---

## 👨‍💼 App Owner

- Manage Applications
- Update Applications
- View Dashboard

---

## 👨‍💻 Administrator

- Manage Users
- Manage App Owners
- Manage Applications
- Monitor Platform

---

# 🔐 Security

The application uses:

- Spring Security
- JWT Authentication
- Role-Based Access Control (RBAC)
- Secure REST APIs

---

# 📂 Modules

- Authentication Module
- User Module
- Admin Module
- App Owner Module
- Dashboard Module
- Download Module

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/Harsh91400/app-store-management-platform.git
```

---

## Open Project

Import the project into Eclipse as an **Existing Maven Project**.

---

## Build Project

```bash
mvn clean install
```

---

## Run Eureka Server

Start the **Eureka Server** before running the application services.

---

## Run Application

```bash
mvn spring-boot:run
```

---

# 📚 What I Learned

Through this project I gained hands-on experience with:

- Java Backend Development
- Spring Boot
- Spring Security
- JWT Authentication
- REST API Development
- Spring Data JPA
- Microservices Architecture
- Service Discovery using Eureka
- Maven
- Git & GitHub
- Layered Architecture
- Role-Based Authorization

---

# 🎯 Future Enhancements

- Swagger / OpenAPI Documentation
- Docker Support
- API Gateway
- Config Server
- Unit Testing using JUnit & Mockito
- CI/CD Pipeline
- Email Notification Service
- Redis Caching

---

# 📸 Screenshots



<img width="1919" height="860" alt="Screenshot 2025-12-18 194927" src="https://github.com/user-attachments/assets/2c49afdc-a5c0-423a-aa2a-c49a0a3b2bc6" />
<img width="1903" height="893" alt="Screenshot 2025-12-18 195006" src="https://github.com/user-attachments/assets/dfc59b43-f642-4d6d-a058-aa7406fba4fa" />
<img width="1919" height="898" alt="Screenshot 2025-12-18 195019" src="https://github.com/user-attachments/assets/fee308cc-5206-46b3-af2d-1c15dd68bf56" />
<img width="1919" height="918" alt="Screenshot 2025-12-18 201544" src="https://github.com/user-attachments/assets/4e9b93ca-d3e1-4afa-87be-1bd1db365673" />
<img width="1917" height="899" alt="Screenshot 2025-12-18 201553" src="https://github.com/user-attachments/assets/f082456f-4e24-4fe3-ad7d-6b1d75728607" />





---

# 👨‍💻 Author

**Harshit Tripathi**

📧 Email  
**harshit91400@gmail.com**

🔗 LinkedIn  
https://www.linkedin.com/in/harshit-tripathi-0a1432269/

💻 GitHub  
https://github.com/Harsh91400

---

# ⭐ If you found this project helpful, please consider giving it a Star.

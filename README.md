# Rideshare Backend API

A Spring Boot RESTful backend application for a ride-sharing platform with JWT-based authentication, user management, and ride booking functionality.

## 🚀 Tech Stack

- **Framework:** Spring Boot 3.2.0
- **Database:** MongoDB
- **Security:** Spring Security with JWT Authentication
- **Build Tool:** Maven
- **Java Version:** 17

## 📁 Project Structure

```
src/main/java/org/example/rideshare/
├── config/          # Security & MongoDB configurations
├── controller/      # REST API endpoints (Auth, Driver, Ride, User)
├── dto/             # Data Transfer Objects
├── exception/       # Custom exception handlers
├── model/           # Entity models (User, Ride, RideStatus)
├── repository/      # MongoDB repositories
├── security/        # JWT authentication & user details
└── service/         # Business logic layer
```

## ✨ Features

- **User Authentication** - Register, login with JWT token-based security
- **Ride Management** - Create, track, and manage ride requests
- **Driver API** - Dedicated driver endpoints
- **User Profiles** - User management and profile operations
- **Global Exception Handling** - Consistent error responses

## 🛠️ Getting Started

1. Clone the repository
2. Configure MongoDB connection in `application.properties`
3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

## 📌 API Endpoints

| Endpoint | Description |
|----------|-------------|
| `/api/auth/*` | Authentication (login/register) |
| `/api/v1/users/*` | User operations |
| `/api/v1/drivers/*` | Driver operations |
| `/api/v1/rides/*` | Ride management |

---

*Built with Spring Boot & MongoDB*

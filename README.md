# 🏦 Digital Banking Platform

A production-ready full-stack **Digital Banking Platform** developed using **Java, Spring Boot, Angular, and MySQL**. The application enables customers to securely manage their bank accounts, perform banking transactions, and monitor their financial activities through a modern web interface.

---

## 🚀 Features

### 🔐 Authentication & Authorization
- User Registration & Login
- JWT Authentication
- Role-Based Access Control (Admin & Customer)
- BCrypt Password Encryption
- Secure Session Management

### 👤 Customer Module
- Customer Registration
- Profile Management
- Account Dashboard
- Update Personal Information

### 💳 Account Management
- Create Savings & Current Accounts
- View Account Details
- Balance Inquiry
- Account Summary

### 💰 Banking Operations
- Deposit Money
- Withdraw Money
- Transfer Funds Between Accounts
- Beneficiary Management
- Transaction History
- Mini Statement

### 👨‍💼 Admin Module
- Manage Customers
- View All Accounts
- Monitor Transactions
- Freeze/Unfreeze Accounts
- Dashboard & Reports

### 📄 Additional Features
- Global Exception Handling
- Request Validation
- Pagination & Sorting
- RESTful APIs
- Swagger API Documentation
- Docker Support
- Unit Testing (JUnit & Mockito)
- Logging using SLF4J

---

# 🛠️ Tech Stack

## Backend
- Java 17
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- Maven
- JWT Authentication

## Frontend
- Angular
- TypeScript
- HTML5
- CSS3
- Bootstrap

## Database
- MySQL

## Tools
- Git
- GitHub
- Postman
- Swagger UI
- Docker
- IntelliJ IDEA
- VS Code

---

# 📂 Project Structure

```
Bank-Management-System
│
├── angular-frontend
│   ├── src
│   ├── package.json
│   └── angular.json
│
├── SpringBoot-Backend
│   ├── src
│   ├── pom.xml
│   ├── controller
│   ├── service
│   ├── repository
│   ├── entity
│   ├── dto
│   ├── security
│   ├── config
│   └── exception
│
└── README.md
```

---

# 🏗️ Architecture

```
Angular Frontend
        │
 REST API (HTTP)
        │
Spring Boot Backend
        │
 Service Layer
        │
 Repository Layer
        │
      MySQL
```

---

# 📌 REST API Endpoints

## Authentication

| Method | Endpoint |
|---------|----------|
| POST | /api/auth/register |
| POST | /api/auth/login |

---

## Customer APIs

| Method | Endpoint |
|---------|----------|
| GET | /api/customers |
| GET | /api/customers/{id} |
| PUT | /api/customers/{id} |

---

## Account APIs

| Method | Endpoint |
|---------|----------|
| POST | /api/accounts |
| GET | /api/accounts |
| GET | /api/accounts/{id} |

---

## Transaction APIs

| Method | Endpoint |
|---------|----------|
| POST | /api/transactions/deposit |
| POST | /api/transactions/withdraw |
| POST | /api/transactions/transfer |
| GET | /api/transactions/history |

---

# 🗄️ Database Entities

- User
- Role
- Customer
- Account
- Transaction
- Beneficiary
- Loan
- Card

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/techie11manisha/Bank-Management-System.git
```

---

## Backend Setup

```bash
cd SpringBoot-Backend
mvn clean install
mvn spring-boot:run
```

Backend runs on

```
http://localhost:8080
```

---

## Frontend Setup

```bash
cd angular-frontend
npm install
ng serve
```

Frontend runs on

```
http://localhost:4200
```

---

# 🧪 API Documentation

Swagger UI

```
http://localhost:8080/swagger-ui/index.html
```

---

# 📈 Future Enhancements

- Redis Caching
- Refresh Token Authentication
- Email Notifications
- SMS Notifications
- PDF Bank Statements
- Loan Management
- Fixed Deposit Module
- Credit Card Module
- Docker Compose
- GitHub Actions CI/CD
- AWS Deployment
- Microservices Architecture

---

# 📸 Screenshots

- Login Page
- Customer Dashboard
- Admin Dashboard
- Account Summary
- Fund Transfer
- Transaction History

---

# 💡 Key Highlights

- Developed a production-ready Digital Banking Platform using Java, Spring Boot, Angular, and MySQL.
- Implemented secure authentication and authorization using Spring Security and JWT.
- Designed RESTful APIs following layered architecture principles.
- Implemented fund transfer, deposits, withdrawals, and transaction history.
- Integrated validation, centralized exception handling, pagination, and Swagger documentation.
- Built responsive Angular UI for customer and admin operations.

---

# 👩‍💻 Author

**Manisha Jaishwal**

GitHub: https://github.com/techie11manisha

LinkedIn: *(Add your LinkedIn profile here)*

---

## ⭐ If you like this project, don't forget to give it a star!
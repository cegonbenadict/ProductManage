# Product Management System

A full-stack web application using **React (frontend)**, **Spring Boot (backend)**, and **MySQL (database)**.

## Features
- View, add, edit, delete products
- REST API with Spring Boot
- Responsive UI with React
- Data persisted in MySQL

## Technologies
- Frontend: React, Axios, React Router
- Backend: Spring Boot, Spring Data JPA
- Database: MySQL

## Getting Started

### Prerequisites
- Node.js, npm
- Java 17+
- MySQL
- (Optional) Docker

### Database Setup (MySQL)
Run the following SQL to create the database:

```sql
CREATE DATABASE productdb;
```

Or use the included file: `init.sql`.

### Running Locally

#### Backend
1. Update `application.properties` with your DB credentials
2. Run: `mvn spring-boot:run`

#### Frontend
1. Navigate to `product-management-frontend`
2. Run: `npm install && npm start`

### Docker Setup

Use Docker Compose to start everything (backend, frontend, db):
```bash
docker-compose up --build
```
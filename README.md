# 🔐 Secure Notes Tracker

A full-stack secure notes management application built with **Spring Boot** (backend) and **React** (frontend).

This application allows users to securely create, manage, and store personal notes with authentication and role-based authorization.

---

## 🚀 Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- JWT Authentication
- OAuth2 Login
- RESTful API
- JPA / Hibernate
- MySQL 

### Frontend
- React
- Context API
- Tailwind CSS
- Axios

---

## 🔐 Features

### Authentication & Authorization
- User registration and login
- JWT-based authentication
- OAuth2 login integration
- Password reset functionality
- Role-based access control (USER / ADMIN)

### Notes Management
- Create notes
- View notes
- Update notes
- Delete notes
- Users can only access their own notes

### Admin Features
- View all users
- Access audit logs
- Manage user accounts

---

## 🛡 Security Highlights

- Spring Security configuration
- JWT token validation & filtering
- Protected frontend routes
- Role-based authorization
- CSRF protection
- Audit logging system

---

## 📂 Project Structure

```
Notes/
 ├── backend/   # Spring Boot REST API
 ├── frontend/  # React application
```

---

## ▶️ How to Run the Project

### 1️⃣ Backend

```bash
cd backend
mvn spring-boot:run
```

Make sure your database configuration is set correctly in:

```
backend/src/main/resources/application.properties
```

---

### 2️⃣ Frontend

```bash
cd frontend
npm install
npm start
```

The React app will run on:

```
http://localhost:3000
```

---

## 🎯 Purpose

This project was built to practice and demonstrate:

- Secure authentication systems
- JWT implementation
- OAuth2 integration
- Role-based authorization
- Full-stack application architecture
- RESTful API development

---

## 📌 Future Improvements

- Docker containerization
- Deployment (Render / Vercel / AWS)
- Email verification
- Two-factor authentication (2FA)

---

## 👨‍💻 Author

Seb

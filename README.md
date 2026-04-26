# 🗂️ Task Management Tool

A full-stack web-based Task Management System built with ASP.NET Core and React.js. This application enables users to efficiently manage, track, and organize tasks with role-based access, logging, and robust backend architecture.

---

## 🚀 Project Overview

The Task Management Tool is designed to help individuals and teams manage their daily tasks effectively. It includes authentication, role-based authorization, CRUD operations for tasks, logging, and testing support.

---

## 🛠️ Tech Stack

### Backend
- ASP.NET Core Web API
- Entity Framework Core
- SQL Server
- Serilog (Logging)
- xUnit (Unit Testing)

### Frontend
- React.js
- Axios
- React Router

### DevOps & Tools
- Git (Version Control)
- SonarQube (Code Quality Analysis)

---

## ✨ Features

### 🔐 Authentication & Authorization
- User Registration & Login
- Role-based access (Admin / User)
- Secure API endpoints using JWT

### 📋 Task Management
- Create, Read, Update, Delete (CRUD) tasks
- Assign tasks to users
- Task priorities and due dates
- Task categorization

### 📊 Dashboard
- View task statistics:
  - Completed
  - In Progress
  - Pending
- Admin can view all users' tasks

### 🧾 Logging
- Integrated Serilog for:
  - Application events
  - Error tracking
  - User activity logs

### 🗄️ Database
- SQL Server with Entity Framework Core
- Structured schema for users and tasks

### ⚠️ Exception Handling
- Global error handling middleware
- User-friendly error responses

### 🧪 Unit Testing
- xUnit testing for:
  - Controllers
  - Services
  - Data access layer

### 📈 Code Quality
- SonarQube integration for static analysis

---

## 🖥️ Application Screens

- Sign Up / Login
- Dashboard
- Task List
- Task Detail
- Create / Update Task
- User Profile

---

## 📂 Project Structure
TaskManagementTool/
│
├── backend/
│ ├── Controllers/
│ ├── Services/
│ ├── Models/
│ ├── Data/
│ ├── Middleware/
│ └── Tests/
│
├── frontend/
│ ├── components/
│ ├── pages/
│ ├── services/
│ └── routes/
│
└── README.md

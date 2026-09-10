# Expense Management System

A full-stack web application designed to help users manage personal finances by tracking income, expenses, budgets, categories, and financial insights.

> 🚧 This project is currently under development.

## 📌 Overview

The Expense Management System provides a centralized platform for recording and managing financial transactions.

The application is being developed with a Java Spring Boot backend, React frontend, and MySQL database, following a layered architecture and RESTful API design.

## ✨ Features

### 👤 User Management
- User registration
- Secure login
- User profile management
- Authentication and authorization

### 💰 Expense Management
- Add expenses
- View expense history
- Update expenses
- Delete expenses
- Categorize expenses
- Search and filter expenses

### 💵 Income Management
- Record income
- View income history
- Update income
- Delete income
- Categorize income

### 🎯 Budget Management
- Create budgets
- Track budget usage
- Monitor remaining budget
- Budget alerts

### 📊 Dashboard & Analytics
- Total income
- Total expenses
- Current balance
- Monthly spending
- Category-wise expense analysis
- Income vs. expense analysis
- Spending trends

### 📈 Reports
- Monthly financial reports
- Category-based reports
- Income and expense summaries

## 🛠️ Technology Stack

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- Hibernate
- REST APIs
- Maven

### Frontend
- React
- JavaScript
- HTML5
- CSS3

### Database
- MySQL

### Testing
- JUnit
- Mockito
- Postman

### Development & Tools
- Git
- GitHub
- IntelliJ IDEA
- Maven

### Deployment
- Docker
- CI/CD
- Cloud deployment

## 🏗️ System Architecture

```text
                    React Frontend
                          │
                          │ HTTP / JSON
                          ↓
                   Spring Boot API
                          │
              ┌───────────┴───────────┐
              ↓                       ↓
        Controller Layer        Spring Security
              │
              ↓
         Service Layer
              │
              ↓
       Repository Layer
              │
              ↓
        JPA / Hibernate
              │
              ↓
            MySQL

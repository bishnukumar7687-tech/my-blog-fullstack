# 📝 MyBlog – Full Stack Blogging Platform

MyBlog is a full-stack blogging platform that allows users to register, authenticate, create, view, update and manage blog posts.

The project was developed to gain practical experience in full-stack web development using **React.js, Java, Spring Boot, MySQL, REST APIs and JWT authentication**.

## 🚀 Features

* User Registration
* User Login
* JWT Authentication
* Protected Routes
* Create Blog
* View All Blogs
* View Blog Details
* Edit Existing Blog
* My Blogs Dashboard
* Blog Image URL Support
* Forgot Password
* REST API Integration
* Responsive User Interface

## 🛠️ Technology Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Axios
* React Router

### Backend

* Java
* Spring Boot
* Spring Security
* JWT
* Maven
* REST APIs

### Database

* MySQL
* Spring Data JPA / Hibernate

## 🏗️ Project Structure

```text
my-blog-fullstack/
│
├── blog-frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── blog-backend/
│   ├── src/
│   ├── pom.xml
│   └── ...
│
├── .gitignore
└── README.md
```

## 🔐 Authentication

The application uses JWT-based authentication.

Basic authentication flow:

```text
User
  ↓
Login
  ↓
Spring Boot Authentication
  ↓
JWT Token
  ↓
React Frontend
  ↓
Authorization Header
  ↓
Protected API
```

## 🔄 Blog Workflow

```text
User Login
    ↓
JWT Token
    ↓
Dashboard
    ↓
Create / Edit Blog
    ↓
Spring Boot REST API
    ↓
MySQL Database
```

## 🌐 API Endpoints

### Authentication

```text
POST /api/auth/register
POST /api/auth/login
POST /api/auth/forgot-password
```

### Blogs

```text
GET    /api/blogs
GET    /api/blogs/{id}
GET    /api/blogs/my
POST   /api/blogs
PUT    /api/blogs/{id}
DELETE /api/blogs/{id}
```

## ⚙️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/my-blog-fullstack.git
```

```bash
cd my-blog-fullstack
```

### 2. Start the Backend

Open:

```text
blog-backend
```

Configure your MySQL database and application properties.

Then run:

```bash
mvn spring-boot:run
```

Backend:

```text
http://localhost:8080
```

### 3. Start the Frontend

Open another terminal:

```bash
cd blog-frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Frontend:

```text
http://localhost:5173
```

## 📸 Screenshots

Add screenshots of:

* Home Page
* Login Page
* Register Page
* Blogs Page
* Blog Details
* Create Blog
* My Blogs
* Edit Blog
* Dashboard

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* React component development
* React Router
* API integration using Axios
* JWT authentication
* Spring Security
* REST API development
* CRUD operations
* MySQL database integration
* JPA/Hibernate
* Frontend-backend integration
* Protected routes
* Full-stack application architecture

## 🔮 Future Improvements

* Comments and replies
* Like and bookmark functionality
* Rich text editor
* User profile
* Blog categories and search
* Pagination
* Cloud image storage
* Email-based password reset
* Deployment using cloud services

## 👨‍💻 Developer

**Bishnu Kumar**

Java Full Stack / Frontend Developer

---

⭐ If you find this project useful, consider giving the repository a star!

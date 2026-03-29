# 🍽️ Smart Canteen Ordering System

A scalable full-stack system designed to eliminate long queues in university cafeterias by enabling digital ordering and efficient order management.

## 🚀 Overview

This project was built to solve a real, everyday problem: long waiting times and inefficient ordering processes in university cafeterias.

Instead of standing in queues, students and professors can now:

- browse the menu
- place orders in advance
- pick up food at a scheduled time

The system is designed with scalability, performance, and real-world usability in mind.

## 🔗 Project Structure

This system is split into separate repositories:

### 🔙 Backend (Laravel API):
- https://github.com/val-tri00/project_cantina_backend
### 🎨 Frontend (React):
- https://github.com/val-tri00/project_cantina_frontent

## ✨ Key Features

### 👤 User Experience
- Secure authentication (email & Google login)
- Browse categorized daily menus
- Add products to cart
- Place orders with scheduled pickup
- Track order status and history

### 🛠️ Admin Dashboard
- Full order management (approve / reject / monitor)
- Product management (CRUD operations)
- User management
- Real-time statistics and sales overview


## 🖼️ Application Preview

### 🔐 Authentication
![Login](./screenshots/auth-login.png)
![Register](./screenshots/auth-register.png)

---

### 👤 User Dashboard
![User Dashboard](./screenshots/user-dashboard.png)

---

### 🛒 Cart & Checkout
![Cart](./screenshots/cart.png)
![Order Success](./screenshots/order-success.png)

---

### 📦 Order History
![Orders History](./screenshots/orders-history.png)

---

### 🧑‍💼 Admin Dashboard
![Admin Dashboard](./screenshots/admin-dashboard.png)

---

### 📋 Admin Order Management
![Admin Orders](./screenshots/admin-orders.png)

---

### 🍽️ Admin Product Management
![Admin Products](./screenshots/admin-products.png)

---

### 👥 Admin User Management
![Admin Users](./screenshots/admin-users.png)



## 🏛️ System Architecture

![System Architecture](./screenshots/system-architecture.png)

This diagram shows the main system components and how the frontend, backend, database, cache, storage, and reverse proxy interact inside the application.


## 🏗️ Architecture & Tech Stack

### ⚙️ Core Technologies
1. Frontend: React
2. Backend: Laravel (REST API)
3. Database: PostgreSQL
4. Cache Layer: Redis
5. Reverse Proxy: NGINX
6. Storage: Cloudflare R2
7. Containerization: Docker & Docker Compose

### 🔄 Scalability & Design
1. Decoupled frontend and backend
2. Designed for high concurrency environments
3. Supports horizontal and vertical scaling
4. Optimized using caching (Redis)
5. Ready for event-driven architecture (Kafka planned)


## ⚙️ Getting Started

### 🐳 Run the full system using Docker
docker-compose up --build

### 🌐 Access
Frontend: http://localhost:3000
Backend API: http://localhost/api

### 📈 Engineering Decisions
Redis used to reduce database load and improve performance
Docker ensures environment consistency and scalability
NGINX acts as a reverse proxy for efficient request handling
Modular architecture allows easy scaling and future extensions

## 🎯 Problem Solved

University cafeterias often struggle with:

long queues
inefficient order flow
lack of digital systems

This system:

reduces waiting time
improves order organization
enhances user experience
supports high-traffic scenarios

## 🧠 What I Learned
Designing scalable full-stack systems
Working with containerized environments (Docker)
Backend optimization using caching (Redis)
Structuring real-world admin dashboards
Building systems with scalability in mind

## 🚀 Future Improvements
Kafka integration for asynchronous processing
Real-time notifications (WebSockets)
Online payments integration
Mobile application version

## 👨‍💻 Author
Developed as a Bachelor's Thesis project with a strong focus on real-world applicability, scalability, and system design.

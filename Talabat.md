<div align="center">

# 🍔 Talabat Clone
### Full-Stack Food Delivery Platform

A production-ready food delivery application built with **ASP.NET Core**, **Angular**, **SQL Server**, and **Redis**, featuring secure authentication, online payments, advanced product filtering, and a scalable Clean Architecture backend.

![.NET](https://img.shields.io/badge/.NET-8-purple)
![Angular](https://img.shields.io/badge/Angular-19-red)
![SQL Server](https://img.shields.io/badge/SQL%20Server-Database-blue)
![Redis](https://img.shields.io/badge/Redis-Caching-red)
![Stripe](https://img.shields.io/badge/Stripe-Payments-635BFF)

</div>

---

# 🌐 Live Demo

## 🖥️ Web Application

**https://talabatt.vercel.app/**

## 📚 API Documentation (Swagger)

**https://talabatpub-api.runasp.net/swagger**

## 💻 Source Code

**https://github.com/A7medM7md/Talabat**

---

# 🔑 Demo Access

No demo credentials are required.

Simply register a new account and start exploring the application.

✅ Create Account

✅ Browse Products

✅ Add to Cart

✅ Checkout

✅ Place Orders

---

# 📖 Overview

Talabat Clone is a modern full-stack food delivery platform inspired by enterprise e-commerce applications.

The project demonstrates how to build scalable backend services using ASP.NET Core while delivering a responsive Angular frontend.

It implements several enterprise software engineering patterns including Repository, Unit of Work, and Specification Pattern to provide clean, maintainable, and extensible business logic.

Redis caching is integrated to improve performance, while Stripe powers secure online payment processing.

---

# ✨ Features

## 👤 Authentication

- JWT Authentication
- User Registration
- Login / Logout
- Refresh Tokens
- Role-Based Authorization

---

## 🍕 Product Catalog

- Browse Products
- Categories
- Brands
- Product Details
- Search
- Sorting
- Pagination

---

## 🛒 Shopping Cart

- Add / Remove Products
- Update Quantity
- Persistent Shopping Cart
- Price Calculation

---

## 💳 Checkout & Payments

- Stripe Payment Integration
- Secure Checkout
- Order Confirmation
- Payment Status Tracking

---

## 📦 Orders

- Create Orders
- Order History
- Delivery Information
- Order Summary

---

## ⚡ Performance

- Redis Distributed Cache
- Optimized Database Queries
- Efficient API Responses

---

# 🏛 Architecture

The backend follows **Clean Architecture** principles.

```
Talabat

├── Talabat.API
│
├── Talabat.Core
│   ├── Entities
│   ├── Specifications
│   ├── Interfaces
│   └── Services
│
├── Talabat.Repository
│   ├── Repositories
│   ├── Unit Of Work
│   └── Data
│
└── Talabat.Services
```

---

# 🔥 Design Patterns

This project implements several enterprise-level design patterns:

- Repository Pattern
- Unit of Work Pattern
- Specification Pattern
- Generic Repository
- Dependency Injection
- Clean Architecture

---

# 🛠 Technology Stack

| Category | Technology |
|-----------|------------|
| Backend | ASP.NET Core |
| Frontend | Angular |
| Database | SQL Server |
| ORM | Entity Framework Core |
| Authentication | JWT |
| Caching | Redis |
| Payments | Stripe |
| Documentation | Swagger |
| Deployment | Vercel + IIS Hosting |

---

# ⚡ Request Flow

```
Angular Client
        │
        ▼
 ASP.NET Core API
        │
        ├────────► Authentication
        │
        ├────────► Product Catalog
        │
        ├────────► Orders
        │
        ├────────► Stripe Payments
        │
        ▼
Redis Cache
        │
        ▼
SQL Server
```

---

# 🔒 Security

- JWT Authentication
- Password Hashing
- Authorization Policies
- Secure Payment Processing
- Input Validation

---

# 📈 Highlights

- Enterprise Architecture
- Repository Pattern
- Specification Pattern
- Unit of Work
- Redis Caching
- Stripe Payments
- RESTful APIs
- Responsive Angular UI

---

# 🚀 Getting Started

## Clone

```bash
git clone https://github.com/A7medM7md/Talabat.git
```

## Backend

```bash
cd Talabat
dotnet restore
dotnet ef database update
dotnet run
```

## Frontend

```bash
cd client
npm install
ng serve
```

---

# 📷 Screenshots

> Add screenshots of:

- Home Page
- Product Details
- Shopping Cart
- Checkout
- Orders
- Payment Flow

---

# 👨‍💻 Author

**Ahmed Mohamed Elgebaly**

.NET Full-Stack Developer

- GitHub: https://github.com/A7medM7md
- LinkedIn: https://linkedin.com/in/ahmad-elgebaly

---

<div align="center">

⭐ If you like this project, consider giving it a star!

</div>

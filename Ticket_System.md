<div align="center">

# 🎫 Ticket Management System
### Enterprise Multi-Tenant Help Desk & Customer Support Platform

Production-grade ticket management platform built with **ASP.NET Core**, **Angular**, **SignalR**, **SQL Server**, and **Clean Architecture**, designed for enterprise customer support with real-time collaboration, advanced reporting, and multi-tenant isolation.

---

## 🌐 Live Demo

🔗 Frontend:
https://aldahayan-ticket.vercel.app

🔗 Backend API:
https://dahayanticket.runasp.net/swagger

---

## 🔑 Demo Credentials

Admin (Full Access):
admin@dt.com | Admin123#

Manager (Read Only):
manager@dt.com | Manager123#

Support (Internal User: Technical Support):
support@dt.com | 123

Client (Company-based):
client@dt.com | Client123#

---

![.NET](https://img.shields.io/badge/.NET-9-purple)
![Angular](https://img.shields.io/badge/Angular-22-red)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-WebAPI-blue)
![SignalR](https://img.shields.io/badge/SignalR-Realtime-green)
![SQL Server](https://img.shields.io/badge/SQL%20Server-Database-red)
![CQRS](https://img.shields.io/badge/CQRS-MediatR-blueviolet)
![Clean Architecture](https://img.shields.io/badge/Architecture-Clean-success)
![MultiTenant](https://img.shields.io/badge/Multi--Tenant-SaaS-orange)

</div>

---

# 📖 Overview

The Ticket Management System is an enterprise SaaS platform designed to streamline customer support operations for organizations with multiple companies (tenants).

The platform enables customers to create and track support tickets while allowing internal support teams to collaborate in real time, manage workflows, monitor performance, and generate business reports.

Built with scalability and maintainability in mind, it follows **Clean Architecture**, **CQRS**, and modern enterprise development practices.

---

# 🚀 Key Features

## 🎫 Ticket Management

- Create and manage tickets
- Ticket assignment
- Priority & status workflow
- Department routing
- Categories & tags
- Attachments
- Ticket history

---

## 💬 Real-Time Collaboration

Powered by SignalR.

Features include:

- Live chat
- Typing indicators
- Read receipts
- Instant notifications
- Online/offline presence
- Real-time ticket updates

---

## 🏢 Multi-Tenant SaaS

Designed for enterprise environments.

Features:

- Company isolation
- Tenant-aware authorization
- Secure data segregation
- Company-specific users
- Shared platform infrastructure

---

## 👥 User & Role Management

Supports multiple system roles:

- System Administrator
- Company Administrator
- Support Agents
- Customers

Includes:

- Role-based permissions
- Claims-based authorization
- Company-level access control

---

## 📊 Reporting & Analytics

Interactive dashboards with:

- Ticket status distribution
- Priority analysis
- Creation trends
- Top active companies
- Resolution statistics
- PDF reports
- Excel export

---

## 🌍 Localization

- English
- Arabic (RTL)
- Dynamic language switching

---

## 📝 Audit Logging

Tracks every important system action including:

- Ticket changes
- User management
- Status updates
- Permission changes
- Authentication events

---

# ⚡ System Workflow

```
Customer
     │
     ▼
Create Ticket
     │
     ▼
Assignment Engine
     │
     ▼
Support Team
     │
     ├────────► SignalR Notifications
     │
     ├────────► Live Chat
     │
     ├────────► Audit Logs
     │
     ▼
Resolution
     │
     ▼
Reports & Analytics
```

---

# 🏛 System Architecture

```
Ticket Management System

├── API
│
├── Core
│
├── Application
│
├── Infrastructure
│
├── Domain
│
└── Angular Frontend
```

---

# 🛠 Tech Stack

| Category | Technology |
|-----------|------------|
| Backend | ASP.NET Core (.NET 9) |
| Frontend | Angular 22 |
| Architecture | Clean Architecture + CQRS |
| Database | SQL Server |
| ORM | Entity Framework Core |
| Authentication | JWT + Refresh Tokens |
| Authorization | Roles & Permissions |
| Real-Time | SignalR |
| Validation | FluentValidation |
| Mapping | Mapster |
| Logging | Serilog |
| Documentation | Swagger/OpenAPI |
| Reporting | PDF + Excel |
| Localization | English / Arabic |
| DevOps | Docker |

---

# 🔒 Security

- JWT Authentication
- Refresh Tokens
- Role-Based Authorization
- Claims-Based Permissions
- Multi-Tenant Isolation
- Audit Logging
- Secure API Endpoints

---

# 📈 Scalability

Designed to support:

- Multiple companies
- Thousands of users
- High-volume ticket processing
- Real-time communication
- Enterprise reporting
- Horizontal API scaling

---

# ⭐ Highlights

- Multi-Tenant SaaS
- Enterprise Help Desk
- Clean Architecture
- CQRS
- SignalR
- Real-Time Chat
- Role & Permission Management
- Audit Logging
- PDF & Excel Reporting
- Localization (EN/AR)
- Dashboard & Analytics
- Responsive Angular UI

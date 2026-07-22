<div align="center">

# 🐄 FarmIQ
### Intelligent IoT Platform for Smart Livestock Monitoring

Production-grade livestock monitoring platform built with **ASP.NET Core**, **Kafka**, **MQTT**, **SignalR**, **SQL Server**, and **TimescaleDB** to process thousands of real-time telemetry events and provide AI-powered health monitoring.

---

## 🌐 Live Demo

📱 Mobile APK: 
https://github.com/GraduationProject-FCITU/frontend-mobile/releases/tag/v1.0.15

🔗 Backend API: 
https://farmiq.runasp.net

---

## 🔑 Demo Credentials

demo@gmail.com | Demo@123 

---

![.NET](https://img.shields.io/badge/.NET-9-purple)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-WebAPI-blue)
![Kafka](https://img.shields.io/badge/Kafka-Streaming-black)
![MQTT](https://img.shields.io/badge/MQTT-IoT-orange)
![SignalR](https://img.shields.io/badge/SignalR-Realtime-green)
![SQL Server](https://img.shields.io/badge/SQL%20Server-Database-red)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-TimeSeries-blue)
![Firebase](https://img.shields.io/badge/Firebase-PushNotifications-yellow)

</div>

---

# 📖 Overview

FarmIQ is a scalable IoT platform that enables livestock farms to monitor animal health in real time.

Smart collars continuously transmit telemetry such as:

- Body temperature
- Motion & activity
- Battery status

The backend processes thousands of telemetry events through an event-driven architecture, analyzes them using an intelligent rule engine, stores transactional and time-series data separately, and instantly notifies farmers whenever abnormal behavior is detected.

---

# 🚀 Key Features

## 🐄 Real-Time Telemetry

- MQTT-based device communication
- Kafka event streaming
- High-throughput telemetry processing
- SignalR live updates
- Automatic device health monitoring

---

## 🧠 Intelligent Rule Engine

Production-grade rule engine featuring:

- Thread-safe singleton architecture
- Device state caching
- Cooldown mechanism
- Alert deduplication
- Priority-based evaluation
- Statistical anomaly detection
- Health status inference

Supported detections:

- Fever
- Low activity
- Sudden collapse
- Battery issues
- Missing telemetry
- Sensor anomalies

---

## ❤️ Health Monitoring

Every telemetry event contributes to an automatically generated health state.

Current health states:

- Healthy
- Fever
- Low Activity

Future roadmap:

- AI Health Score
- Predictive Disease Detection
- Behavioral Analysis

---

## 🚨 Smart Alerts

- Instant critical alerts
- Firebase Push Notifications
- Alert aggregation
- Persistent alert history
- Priority ordering
- Spam prevention

---

## 🤖 AI Automation

FarmIQ integrates **n8n** workflows to automate:

- Daily reports
- Health summaries
- Critical alert notifications
- AI-powered analytics
- Scheduled workflows

---

## 🏢 Multi-Tenant Architecture

- Farm isolation
- Tenant-aware JWT
- Secure authorization
- Scalable SaaS architecture

---

# ⚡ Telemetry Pipeline

```
Smart Collar
      │
      ▼
    MQTT Broker
      │
      ▼
Kafka Event Stream
      │
      ▼
Telemetry Processor
      │
      ▼
 Intelligent Rule Engine
      │
      ├────────► Alerts
      │
      ├────────► Health Status
      │
      ├────────► SignalR
      │
      ▼
SQL Server

      +

TimescaleDB
(Time-Series Telemetry)
```

---

# 🏛 System Architecture

```
FarmIQ

├── API
│
├── Core
│
├── Application
│
├── Infrastructure
│
├── Services
│     ├── Rule Engine
│     ├── Telemetry Analyzer
│     ├── Alert Aggregator
│     └── Notification Service
│
└── Workers
```

---

# 💾 Data Storage

FarmIQ separates operational data from telemetry.

## SQL Server

Stores:

- Users
- Farms
- Animals
- Alerts
- Authentication
- Permissions
- Notifications

---

## TimescaleDB

Stores:

- Temperature history
- Accelerometer history
- Telemetry events
- Device statistics

This architecture allows millions of telemetry records without impacting transactional performance.

---

# 🛠 Tech Stack

| Category | Technology |
|-----------|------------|
| Backend | ASP.NET Core (.NET 9) |
| Architecture | Clean Architecture + CQRS |
| Database | SQL Server |
| Time-Series | TimescaleDB (PostgreSQL) |
| Streaming | Kafka |
| IoT Communication | MQTT |
| Real-Time | SignalR |
| Authentication | JWT + Refresh Tokens + API Key Authentication |
| Push Notifications | Firebase Cloud Messaging |
| AI Automation | n8n |
| Caching | In-Memory Device State |

---

# 🔒 Security

- JWT Authentication
- Refresh Tokens
- Role-Based Authorization
- Tenant Isolation
- Secure API Endpoints

---

# 📊 Scalability

Designed to support:

- Thousands of connected IoT devices
- Millions of telemetry records
- Horizontal API scaling
- Event-driven processing
- High-frequency telemetry ingestion

---

# 📡 Example Telemetry

```json
{
  "deviceId": "esp-01",
  "temperature": 39.8,
  "battery": 82,
  "accX": 0.12,
  "accY": 0.47,
  "accZ": 0.89
}
```

---

# 📷 Some Screenshots

<img width="659" height="504" alt="image" src="https://github.com/user-attachments/assets/3c44e54c-4eb5-47d3-b9d3-4c52940bbbaf" />
<img width="297" height="511" alt="image" src="https://github.com/user-attachments/assets/1bb6d868-ef1e-49e2-bfb4-8566dc6d8f2b" />
<img width="291" height="534" alt="image" src="https://github.com/user-attachments/assets/79bf26df-e531-40b1-8a2d-97aaf6c336e9" />

<img width="559" height="782" alt="image" src="https://github.com/user-attachments/assets/3e010c50-e3d1-45a6-85fd-0fed24891763" />

---

# 👨‍💻 Team

Graduation Project — Faculty of Computers & Artificial Intelligence

Tanta University

2026

---

# ⭐ Highlights

- Event-Driven Architecture
- IoT Platform
- Kafka Streaming
- MQTT Communication
- AI Workflow Automation
- Real-Time Monitoring
- SignalR
- Clean Architecture
- Multi-Tenant Design
- Time-Series Database

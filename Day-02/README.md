# 🚀 Day 2 - <App Architecture & Tech Stack>

## 📚 What I Learned

## What is App Architecture?

App architecture is the **way an application is organized and built**.

Think of it like building a house:

* The **rooms** = different parts of the app
* The **wiring and plumbing** = how parts communicate
* The **blueprint** = architecture

It decides:

* Where the frontend goes
* Where the backend works
* How data is stored
* How users connect to the app

---

## What is a Tech Stack?

A tech stack is the collection of technologies used to build an app.

It usually includes:

| Part          | Purpose             | Example          |
| ------------- | ------------------- | ---------------- |
| Frontend      | What users see      | HTML, CSS, React |
| Backend       | Logic behind app    | Java, Node.js    |
| Database      | Stores data         | MySQL, MongoDB   |
| Hosting/Cloud | Runs the app online | AWS              |

---

## Simple Real-World Example

Imagine a **food delivery app**.

### Frontend

The mobile app where users:

* Browse food
* Add items
* Track delivery

### Backend

Handles:

* Orders
* Payments
* Delivery tracking

### Database

Stores:

* User accounts
* Restaurant menus
* Orders

### Cloud

AWS keeps the app running online 24/7.

---

# Beginner Architecture Flow

User → Mobile App → Backend Server → Database

Now let’s go deeper.

---

Apps are usually divided into layers.

---

## Common 3-Tier Architecture

Presentation Layer → Application Layer → Data Layer

### 1. Presentation Layer

Frontend/UI
Examples:

* React
* Angular
* Flutter

### 2. Application Layer

Business logic
Examples:

* Java Spring Boot
* Node.js
* Python Django

### 3. Data Layer

Databases and storage
Examples:

* PostgreSQL
* MongoDB
* Redis

---

## What is a Modern Tech Stack?

A modern stack combines:

* Frontend framework
* Backend APIs
* Databases
* Cloud infrastructure
* DevOps tools

---

## Example Stack

| Area           | Technology        |
| -------------- | ----------------- |
| Frontend       | React             |
| Backend        | Node.js + Express |
| Database       | MongoDB           |
| Authentication | JWT               |
| Cloud          | AWS               |
| CI/CD          | GitHub Actions    |
| Containers     | Docker            |

---

## Real-World Example 

### Example: Netflix-like Streaming App

### Frontend

React web app or mobile app

### Backend APIs

Serve:

* Movies
* Recommendations
* User profiles

### Database

Stores:

* Watch history
* Accounts
* Preferences

### CDN

Videos are delivered faster globally.

### DevOps

Docker + CI/CD automatically deploy updates.

---

Large companies use:

* Distributed systems
* Microservices
* Cloud-native architecture
* Containers
* Kubernetes
* Load balancing
* Monitoring
* CI/CD pipelines

---

# Monolithic vs Microservices

## Monolithic Architecture

* Everything is inside one application.

* One Big App
├── Login
├── Payments
├── Orders
└── Notifications


### Problems

* Hard to scale
* One bug can affect whole app
* Slow deployments

---

## Microservices Architecture

 * Each service works independently.

 * User Service
 * Order Service
 * Payment Service
 * Notification Service

Each can:

* Scale separately
* Deploy independently
* Use different databases

# Real-World Example 

## Example: Amazon-like E-commerce Platform

### Architecture

Users
   ↓
Load Balancer
   ↓
API Gateway
   ↓
Microservices
   ├── Auth Service
   ├── Product Service
   ├── Payment Service
   ├── Cart Service
   └── Delivery Service
   ↓
Databases + Cache
   ↓
Monitoring & Logging

---

# How DevOps Fits In

DevOps helps:

* Automate deployments
* Monitor systems
* Scale infrastructure
* Reduce downtime
* Improve reliability

---

# Example DevOps Workflow

Developer pushes code → GitHub → CI/CD Pipeline → Docker Build → Kubernetes Deployment → AWS Cloud

---

## 🧠 My Understanding 

After learning this, i how  understood the concept  *App Arcitecture * is an important to learn .also understood an types of an application arcitecture . (two - tier , three - tier ,microservice )
Once you understand app architecture, DevOps concepts become much easier because you’ll know:

* what you are deploying,
* where it runs,
* how users access it,
* and how to scale it properly.

---

## 🛠️ Tools Mentioned
- 

## ⚡ Challenges Faced
- 
    At the time of my learning it was hard to learn some concepts specially Microservice Architecture and its flow as i haven't learn some concepts that are going to use later in my learing journey .
    Note - Try to Revise topics that i didnt understand .
---

## 🎯 Next Plan

- # Application Port 

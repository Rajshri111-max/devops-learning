# 🚀 Day 2 - Appication Ports

## 📚 What I Learned 

   * What is a Port?
   * How Applications Use Ports
   * Importance of Application Ports in Devops.

## 🧠 My Understanding

# 1. Beginner Level 🌱

## What is a Port?

A port is like a **door** through which applications communicate over a network.

Think of your computer like an apartment building:

* **IP Address** = Building address
* **Port Number** = Apartment number

The IP tells data which computer to go to.
The port tells data which application inside that computer should receive it.

---

## Simple Example

When you open a website:

https://google.com

Your browser talks to Google’s web server using:

* Port **443** → HTTPS
* Port **80** → HTTP

---

## Common Ports

| Port | Service    |
| ---- | ---------- |
| 80   | HTTP       |
| 443  | HTTPS      |
| 22   | SSH        |
| 3306 | MySQL      |
| 5432 | PostgreSQL |

---


## Beginner Flow

User Browser → Server IP → Port 443 → Website Application

---

Now how ports work in real systems.

---

# How Applications Use Ports

When an application starts, it “listens” on a specific port.

Example:

Node.js app listening on port 3000

This means:

* The app waits for requests on port 3000
* Incoming traffic to that port reaches the app

---

## Intermediate Flow


Browser → Port 3000 (Frontend)
              ↓
         Backend API → Port 5000
              ↓
         Database → Port 27017

---
# Important Networking Concepts

## Open Port

A port accepting traffic.

## Closed Port

No application is listening.

## Firewall

Controls which ports are allowed.

Example:

* Allow port 443
* Block port 22 publicly

---

# Real-World Example 

## Example: Company Website

A company server may use:

| Port | Purpose              |
| ---- | -------------------- |
| 80   | Redirect HTTP        |
| 443  | Secure HTTPS traffic |
| 22   | Admin SSH access     |
| 3306 | Internal database    |

Database ports are usually private for security.
----

# Ports in Modern Infrastructure

Ports are critical for:

* Microservices
* Containers
* Kubernetes
* Load balancers
* Cloud networking


# Port Security 

## Best Practices

### Expose only required ports

Public:

* 80
* 443

Private:

* Databases
* Internal services

---

## Use Security Groups / Firewalls

In AWS:

* Security Groups control port access.

Example:

* Allow 443 from internet
* Allow 22 only from admin IP

---



# Important DevOps Concepts Related to Ports

| Concept             | Role                            |
| ------------------- | ------------------------------- |
| Load Balancer       | Routes traffic between servers  |
| Reverse Proxy       | Handles requests before backend |
| Docker Port Mapping | Connects host and container     |
| Kubernetes Services | Exposes applications            |
| Firewall Rules      | Controls access                 |
| Security Groups     | Cloud-level port filtering      |

---

# Simple Way to Remember 💡

## IP Address

Which computer?

## Port

Which application on that computer?

---


Whenever you deploy an application, always ask:

1. Which port does the app run on?
2. Is the port open?
3. Is it public or private?
4. Is a firewall blocking it?
5. Is traffic encrypted (HTTPS/443)?

Understanding ports is one of the most important networking skills in DevOps, cloud engineering, and system administration.


## ⚡ Challenges Faced
- Some words are difficult to understand 
How Application uses Ports was little difficult ,Specially to understand how the flow works in it 

Note-- Give little bit more Attention on how applications use an ports 

---

## 🎯 Next Plan
- Domain And DNS

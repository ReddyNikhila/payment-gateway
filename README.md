# 💳 Payment Gateway with Multi-Method Processing & Hosted Checkout

A **fully dockerized payment gateway system** inspired by platforms like Razorpay and Stripe.  
This project demonstrates **end-to-end payment processing**, **merchant workflows**, and **hosted checkout integration** with a scalable backend architecture.

---

## 📌 Overview

This payment gateway system supports:

- Merchant authentication & onboarding  
- Secure order creation and management  
- Multi-method payments (UPI & Cards)  
- Hosted checkout page for customers  
- Merchant dashboard with real-time transaction insights  

The project focuses on **backend API design**, **payment validation**, **transaction lifecycle management**, and **frontend integration**.

---

## ✨ Features

### 🔐 Merchant Features
- Login & authentication
- View API credentials
- Track total transactions
- Monitor successful payments
- Calculate payment success rate
- View complete transaction history

### 💰 Payment Features
- UPI payments with VPA validation
- Card payment processing
- Order-based payment flow
- Transaction status handling (success / failure)

### 🧾 Checkout Experience
- Hosted checkout page
- Clean UI for payment selection
- Secure order-to-payment mapping

---

## 🧱 Tech Stack

| Layer | Technology |
|------|------------|
| Backend | Node.js, Express |
| Database | PostgreSQL |
| Dashboard | HTML, CSS, JavaScript |
| Checkout Page | HTML, CSS, JavaScript |
| Containerization | Docker, Docker Compose |

---

## 🐳 Dockerized Architecture

All services are containerized and can be started using a **single Docker Compose command**.

### 🔌 Services & Ports

| Service | Port |
|-------|------|
| API | 8000 |
| Merchant Dashboard | 3000 |
| Checkout Page | 3001 |
| PostgreSQL | 5432 |

---

## 🗄️ Database Schema

The system uses a relational PostgreSQL database with the following tables:

- **Merchants**
- **Orders**
- **Payments**

### Database Design Highlights
- Proper foreign key relationships
- Indexed columns for performance
- Automatic timestamps for auditing
- Transaction-safe payment records

---

## 🧪 Test Merchant (Auto-Seeded)

A test merchant is automatically created on startup for quick testing.

### 🔑 Dashboard Login
- URL: http://localhost:3000/login.html
- Email: test@example.com
- Password: any value


---

## ▶️ Running the Project

### Prerequisites
- Docker
- Docker Compose

### Start All Services
bash
docker-co## 🧪 Testing

You can test the project using the following methods:

### 🌐 Browser
- Merchant Dashboard  
- Hosted Checkout Page  

### 🔌 API Testing
- Postman  
- curl  

All endpoints, validations, and payment flows are fully implemented as per the given specification.

---

## ✅ Project Status

✔ All mandatory requirements implemented  
✔ Backend APIs verified  
✔ Frontend pages fully functional  
✔ Docker setup validated  
✔ Ready for evaluation and submission  

---
   ## 👤 Author
   **Nikhila Reddy**
   [GitHub](https://github.com/ReddyNikhila) | [LinkedIn](https://www.linkedin.com/in/nikhila-reddy-b64b60290/)

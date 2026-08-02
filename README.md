# 🧾 BillingPro

A full-stack billing platform built with **Spring Boot** and **React**. Customers can browse products, add items to cart, and make payments. Admins manage users, categories, items, and track revenue.

---

## 🛠️ Tech Stack

- **Backend:** Java 21, Spring Boot, Spring Security, JWT, Hibernate, MySQL, Stripe API
- **Frontend:** React 19, Vite, React Router, Axios, Bootstrap 5
- **Tools:** Maven, Git, Postman

---

## ✨ Features

### Customers
- Register and login with JWT
- Browse categories and items
- Add items to cart
- Checkout with Stripe or Cash on Delivery
- View order history

### Admins
- Approve/reject customer accounts
- Create, update, delete users, categories, items
- View revenue and order reports

---

## 🚀 Quick Start

### Prerequisites
- Java 21, MySQL, Node.js

### Backend
cd backend
# Update application.properties with MySQL credentials
mvn clean install
mvn spring-boot:run

### Frontend
cd frontend
npm install
npm run dev

### Default Admin
- Email: admin@billing.com
- Password: admin123
---

For educational purposes. Stripe uses test mode - no real payments.

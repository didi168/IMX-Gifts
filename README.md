# 🎁 IMX Gift Store — Smart E-Commerce Solution

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=for-the-badge&logo=capacitor&logoColor=white)](https://capacitorjs.com/)

**IMX Gifts** is a premium, full-stack e-commerce platform designed for the personalized gifting market. Built with a focus on seamless user experience across web and mobile, it integrates complex business logic including wallet systems, automated OTP verification, and deep product customization.

---

## 🚀 Key Features

### 🛍️ Shopping Experience
- **Smart Product Catalog**: Advanced filtering by category, price, and stock status.
- **Deep Personalization**: Gift customization engine allowing users to add custom messages, photos, and select templates for special occasions.
- **Interactive Reviews**: Modern 5-star rating system with real-time average score calculation.
- **Dynamic Wishlist**: Save favorite items and move them to cart with a single click.

### 💳 Financial & Security
- **Virtual Wallet**: Integrated Monnify wallet system for secure funding and instant checkout.
- **Automated OTP**: Secure user verification via Gmail SMTP and Twilio (SMS).
- **Protected Routes**: Secure authentication flow using JWT (JSON Web Tokens).

### 📱 Connectivity
- **Cross-Platform**: Powered by Capacitor for high-performance Android and iOS native builds.
- **Network Resilient**: Custom API client with interceptors for handling timeouts and session expiration gracefully.

---

## 🛠️ Technical Stack

### Frontend
- **Framework**: React.js 19
- **Icons**: FontAwesome 7
- **Native**: Capacitor (Android/iOS)
- **Styling**: Vanilla CSS (Premium Glassmorphism & Modern UI)
- **State Management**: Context API

### Backend
- **Engine**: Node.js & Express
- **Database**: PostgreSQL with Sequelize ORM (Supabase)
- **Logging**: Winston Production Logging
- **Caching**: Redis
- **Security**: Helmet, CORS, Express-rate-limit

---

## 📦 Physical & Database Architecture

The application uses a **Hybrid Architecture** combining the speed of a Node.js backend with the reliability of **Supabase** (Postgres). 

- **Primary DB**: PostgreSQL for Users, Products, Orders, and Reviews.
- **Storage**: Local/Cloudinary (Configurable).
- **Messaging**: Nodemailer for transactional emails and Twilio for SMS.

---

## 🧪 Quick Test Credentials

To preview the application without creating a new account, you can use the following live testing credentials:

- **Email**: `livetest@IMX.com`
- **Password**: `LiveTest2026!`

---

## 🔒 Security & Performance
- **Production-Ready Logging**: Centralized error tracking with Winston.
- **Secure Headers**: Implemented Helmet.js for protection against common web vulnerabilities.
- **API Optimization**: Centralized Axios client with automatic `Authorization` header injection and standardized error handling.

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

---

## 👨‍💻 Authors

### Divine Okorie
*Frontend Developer*
- LinkedIn: [Divine Okorie](https://www.linkedin.com/in/dues-soft-designs/)

### Prosper Maxwell
*Backend Developer*
- LinkedIn: [Prosper Maxwell](https://www.linkedin.com/in/prozymax901/)

---

> [!TIP]
> This project was audited for production readiness, ensuring all API endpoints are optimized and security headers are strictly enforced.

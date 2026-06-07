# MERN Event Management Platform
### Full-Stack Production System with Admin Dashboard

🌐 Live Site: https://alaalacollections.site  
🔒 Repository Type: Production Case Study (Source Code Private)

---

## 📌 Overview

This project is a full-stack Event Management Platform developed for a professional event management team to digitize their service presentation, booking workflow, media showcasing, and administrative operations.

The system replaces manual coordination with a centralized, scalable web platform built using the MERN stack and a TypeScript-based backend.

It includes a secure admin dashboard for operational control and content management.

---

## 🎯 Business Objectives

- Provide clients with structured event service listings
- Enable seamless online booking & reservation submission
- Centralize event content management
- Showcase completed events through a media gallery
- Collect and manage client reviews
- Improve operational efficiency through an admin dashboard

---

## 🛠 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- React Router
- Axios

### Backend
- Node.js
- Express.js
- TypeScript
- MongoDB (Mongoose ODM)
- JWT Authentication

## 📁 Project Structure

### Backend (TypeScript + Express)
server/
└── src/
├── config/
│ ├── db.ts
│ └── cloudinary.ts
│
├── controllers/
│ ├── authController.ts
│ ├── reservationController.ts
│ ├── serviceController.ts
│ ├── reviewController.ts
│ └── galleryController.ts
│
├── middleware/
│ ├── authMiddleware.ts
│ └── uploadMiddleware.ts
│
├── models/
│ ├── User.ts
│ ├── Reservation.ts
│ ├── Service.ts
│ ├── Review.ts
│ └── Gallery.ts
│
├── routes/
│ ├── authRoutes.ts
│ ├── reservationRoutes.ts
│ ├── serviceRoutes.ts
│ ├── reviewRoutes.ts
│ └── galleryRoutes.ts
│
├── utils/
│ └── uploadToCloudinary.ts
│
└── app.ts


### Frontend (React + Tailwind)
client/
└── src/
├── components/
├── pages/
├── routes/
├── services/ # API calls
├── context/ # Auth / global state
├── hooks/
├── assets/
└── App.jsx

### Cloud & Media
- Cloudinary (image storage & optimization)

### Deployment
- Production-ready environment configuration
- Secure environment variable management

---

## 🚀 Core Features

### 🔐 Authentication & Authorization
- JWT-based authentication
- Protected routes
- Role-based access control
- Secure password hashing

---

### 📅 Reservation & Booking System
- Client event reservation submission
- Backend validation logic
- Persistent booking storage (MongoDB)
- Admin-side booking management

---

### 🛎 Service Management
- Dynamic event service listings
- Full CRUD operations
- Structured data modeling

---

### 🖼 Event Gallery System
- Secure image upload via middleware
- Cloudinary cloud storage integration
- Optimized media delivery
- Admin-controlled gallery updates

---

### ⭐ Reviews & Feedback System
- Client-submitted reviews
- Service-linked review association
- Admin moderation capability

---

## 🖥 Admin Dashboard Capabilities

The platform includes a secure admin dashboard that allows:

- Managing services (Create / Update / Delete)
- Viewing and handling reservations
- Uploading and organizing gallery content
- Managing user-generated reviews
- Controlling protected application routes

This transforms the platform from a static website into a fully operational business management system.

---

### Architectural Highlights

- Clear separation of concerns
- Middleware-driven request lifecycle
- Type-safe backend implementation
- RESTful API design
- Scalable database schema structure
- Cloud-integrated asset handling

---

## 🧠 Engineering Challenges & Solutions

### Secure Media Upload Handling
Implemented middleware-based upload processing integrated with Cloudinary to prevent server overload and ensure scalable storage.

### Route Protection & Role Control
Designed JWT authentication with middleware-based authorization to secure administrative operations.

### Structured Reservation Workflow
Built backend validation and data modeling to ensure reliable booking management and data integrity.

---

## 📈 Operational Impact

- Digitized event booking workflow
- Reduced manual coordination
- Centralized content & service management
- Improved online brand presence
- Built scalable infrastructure for future growth

---

## 🔒 Confidentiality Notice

This platform was developed for a client under a private agreement.  
The production source code is not publicly available.

A technical walkthrough and architectural discussion are available upon request.

---

## 👨‍💻 Developer Focus

This project demonstrates:

- Full-stack MERN development
- TypeScript backend engineering
- Secure authentication systems
- Role-based access control
- Cloud-based media management
- RESTful API architecture
- Real-world production deployment
- Business-oriented system design

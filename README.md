# Alaala Collections Event Management Platform

### Full-Stack MERN Web Application with Administrative Dashboard

🌐 **Live Website:** https://alaalacollections.site

> A production-ready event management platform developed to streamline client reservations, service presentation, content management, and business operations for a professional events company.

---

## Overview

Alaala Collections is a full-stack web application designed to modernize the event planning and booking experience. The platform enables clients to explore services, submit reservations, browse event galleries, and provide reviews, while administrators manage content and operations through a secure dashboard.

The system was developed using the MERN stack with a TypeScript-powered backend, emphasizing scalability, maintainability, and real-world business requirements.

---

## Key Features

### Client-Facing Features

- Browse event services and packages
- Submit event reservations online
- View event galleries and media showcases
- Read and submit customer reviews
- Responsive experience across devices

### Administrative Features

- Secure administrator authentication
- Reservation management dashboard
- Service management (Create, Read, Update, Delete)
- Gallery content management
- Review moderation and approval
- Protected administrative routes

---

## Technology Stack

### Frontend

- React
- TypeScript
- Tailwind CSS
- React Router
- Axios

### Backend

- Node.js
- Express.js
- TypeScript
- MongoDB
- Mongoose
- JSON Web Tokens (JWT)

### Cloud Services

- Cloudinary
  - Image storage
  - Media optimization
  - Asset delivery

### Deployment

- Production environment configuration
- Environment variable management
- Secure API integration

---

## Project Structure

### Backend

```text
server/
└── src/
    ├── config/
    ├── controllers/
    ├── middleware/
    ├── models/
    ├── routes/
    ├── utils/
    └── app.ts
```

### Frontend

```text
client/
└── src/
    ├── assets/
    ├── components/
    ├── context/
    ├── hooks/
    ├── pages/
    ├── routes/
    ├── services/
    └── App.tsx
```

---

## System Modules

### Authentication & Authorization

- JWT-based authentication
- Password hashing
- Protected routes
- Role-based access control

### Reservation Management

- Online reservation submission
- Form validation
- Reservation tracking
- Administrative booking management

### Service Management

- Dynamic service listings
- Full CRUD operations
- Structured service data models

### Gallery Management

- Secure image uploads
- Cloudinary integration
- Optimized media delivery
- Administrative content control

### Reviews & Feedback

- Customer review submission
- Review moderation
- Public review display

---

## Architectural Highlights

- RESTful API architecture
- Type-safe backend implementation
- Separation of concerns
- Middleware-driven request handling
- Scalable MongoDB schema design
- Cloud-based asset management

---

## Challenges Solved

### Media Storage & Upload Management

Implemented middleware-based upload processing integrated with Cloudinary to ensure efficient storage, optimized delivery, and reduced server load.

### Secure Administrative Access

Designed JWT authentication and authorization middleware to protect administrative functionality and sensitive operations.

### Reservation Workflow Management

Developed structured validation and data modeling to ensure reliable booking management and maintain data integrity.

---

## Business Impact

- Digitized the reservation process
- Reduced manual administrative workload
- Centralized service and content management
- Improved customer accessibility and engagement
- Established a scalable foundation for future expansion

---

## Skills Demonstrated

- Full-Stack MERN Development
- TypeScript Backend Development
- REST API Design
- Authentication & Authorization
- MongoDB Database Design
- Cloudinary Media Management
- Responsive UI Development
- Production Deployment
- Business Process Automation
- Software Architecture & System Design

---

## Confidentiality

This project was developed for a real client and is currently deployed in production.

Due to client confidentiality and security considerations, the source code is not publicly available.

---

## Developer

**jvecina.dev**

- Full-Stack Developer
- UI/UX Designer
- MERN Stack Engineer
- TypeScript Backend Developer

For technical discussions, architecture reviews, or project inquiries, feel free to connect.

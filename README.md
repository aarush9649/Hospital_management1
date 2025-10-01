# MERN Stack Hospital Management System

## Overview
A full-stack web application built using **MERN stack (MongoDB, Express, React, Node.js)** for efficient management of hospitals.  
The system allows **Admins** to manage **Doctors** and **Patients**, provides secure authentication, and features a responsive dashboard.

---

## Features

### Admin
- Create and manage doctor and admin accounts
- View all registered doctors and patients
- Dashboard overview for hospital management
- Secure login/logout with JWT authentication

### Doctor
- View assigned patients (future scope: appointments & schedules)
- Profile management

### Patient
- Register online with personal details
- Login/logout securely

---

## Tech Stack
- **Frontend:** React.js, Tailwind CSS / Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Token)
- **Others:** Cloudinary for doctor avatars, Error handling middleware

---

## Project Structure
Hospital-Management-System/
├── backend/ # Node.js + Express API
├── dashboard/ # Admin Dashboard React app
├── frontend/ # React.js user-facing UI
├── .gitignore
├── README.md
└── package.json


---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/HospitalManagementSystem.git

cd backend
npm install

cd ../frontend
npm install

cd ../dashboard
npm install

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET_KEY=your_jwt_secret
JWT_EXPIRES=7d

cd backend
npm run dev

cd ../frontend
npm start

cd ../dashboard
npm start




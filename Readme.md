# BlogApp

A full-stack Blog Application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js).  
This application allows users to create, read, update, and delete blog posts with secure authentication.

---

# Features

- User Authentication (Signup/Login)
- JWT Authentication & Authorization
- Create, Edit, Delete Blogs
- Responsive User Interface
- Admin/User Dashboard
- REST API Integration
- MongoDB Database
- Protected Routes
- Image Upload Support

---

# Tech Stack

## Frontend
- React.js
- Vite
- Tailwind CSS
- Axios
- React Router DOM

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- multer

---

# Project Structure

```bash
BlogApp/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── uploads/
│   └── package.json
│
└── README.md
```

---

# Installation

## 1. Clone Repository

```bash
git clone <your-repository-link>
```

---

# Backend Setup

## Navigate to Backend Folder

```bash
cd backend
```

## Install Dependencies

```bash
npm install
```

## Create `.env` File

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Run Backend Server

```bash
npm run dev
```

Backend runs on:

```bash
http://localhost:5000
```

---

# Frontend Setup

## Navigate to Frontend Folder

```bash
cd frontend
```

## Install Dependencies

```bash
npm install
```

## Start Frontend

```bash
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

# API Endpoints

## Authentication

| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | /api/auth/signup | Register User |
| POST | /api/auth/login | Login User |

---

## Blogs

| Method | Endpoint | Description |
|--------|-----------|-------------|
| GET | /api/blogs | Get All Blogs |
| GET | /api/blogs/:id | Get Single Blog |
| POST | /api/blogs | Create Blog |
| PUT | /api/blogs/:id | Update Blog |
| DELETE | /api/blogs/:id | Delete Blog |

---


# Future Improvements

- Comment System
- Dark Mode
- Blog Categories
- Like & Save Feature
- Rich Text Editor
- Email Verification

---

# Learning Outcomes

This project helped in understanding:
- MERN Stack Development
- REST APIs
- Authentication & Authorization
- MongoDB Integration
- Frontend-Backend Communication
- Full Stack Deployment

---

# Author

Developed by Deekshitha
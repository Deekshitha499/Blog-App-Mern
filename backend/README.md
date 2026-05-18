### Backend development ###

    1. Create git repo
        git init
    2. Add .gitignore file

    3. Create .env file for environment variables & Read data from .env with "dotenv" module

    4. Generate package.json

    5. Create express app

    6. Connect to Database

    7. Add middleware(body parser,err handeling )

    8. Design Schemas and create models

    9. Design REST APIs for all resources

    10. Registration & login in common

    # BlogApp Backend

Backend API for the BlogApp built using Node.js, Express.js, and MongoDB.

## Features

- User Authentication using JWT
- User Registration & Login
- Create, Read, Update, Delete Blogs
- Protected Routes
- MongoDB Database Integration
- REST API Architecture
- Error Handling Middleware
- Image Upload Support
- Admin/User Access Management

---

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcryptjs
- dotenv
- multer
- cors

---

## Project Structure

```bash
backend/
│
├── controllers/
├── models/
├── routes/
├── middleware/
├── uploads/
├── config/
├── server.js
├── package.json
├── .env
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone <your-repository-link>
```

### Navigate to Backend Folder

```bash
cd backend
```

### Install Dependencies

```bash
npm install
```

---

## Environment Variables

Create a `.env` file inside the backend folder.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## Run the Server

### Development Mode

```bash
npm run dev
```

### Production Mode

```bash
npm start
```

---

## API Endpoints

### Authentication Routes

| Method | Endpoint         | Description       |
|--------|------------------|-------------------|
| POST   | /api/auth/signup | Register User     |
| POST   | /api/auth/login  | Login User        |

---

### Blog Routes

| Method | Endpoint         | Description        |
|--------|------------------|--------------------|
| GET    | /api/blogs       | Get All Blogs      |
| GET    | /api/blogs/:id   | Get Single Blog    |
| POST   | /api/blogs       | Create Blog        |
| PUT    | /api/blogs/:id   | Update Blog        |
| DELETE | /api/blogs/:id   | Delete Blog        |

---

## Database

Uses MongoDB Atlas or Local MongoDB.

Example Local Connection:

```env
MONGO_URI=mongodb://127.0.0.1:27017/blogapp
```

---

## Dependencies Installation

Example:

```bash
npm install express mongoose cors dotenv bcryptjs jsonwebtoken multer
```

---

## Future Improvements

- Comment System
- Blog Categories
- Like & Save Blogs
- Admin Dashboard
- Cloud Image Upload
- Email Verification

---

## Author

Developed by Deekshitha
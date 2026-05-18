# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# BlogApp Frontend

Frontend of the BlogApp built using React, Vite, and Tailwind CSS.

## Features

- User Authentication (Login & Signup)
- Create, Edit, and Delete Blogs
- Responsive UI
- Blog Listing Page
- Individual Blog View
- Admin/User Dashboard
- API Integration with Backend
- Modern UI with Tailwind CSS

---

## Tech Stack

- React
- Vite
- Tailwind CSS
- Axios
- React Router DOM

---

## Project Structure

```bash
frontend/
│
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── vite.config.js
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone <your-repository-link>
```

### Navigate to Frontend Folder

```bash
cd frontend
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

---

## Environment Variables

Create a `.env` file in the frontend folder.

Example:

```env
VITE_API_URL=http://localhost:5173
```

---

## Available Scripts

### Run Development Server

```bash
npm run dev
```

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

---

## Backend Connection

Make sure the backend server is running before starting the frontend.

Backend default URL:

```bash
http://localhost:5173
```


## Future Improvements

- Dark Mode
- Comment System
- Like & Save Feature
- Rich Text Editor
- Profile Management

---

## Author

Developed by Deekshitha
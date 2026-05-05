# 🚀 Team Task Manager - MERN Stack

A full-stack **Team Task Manager** application built using the **MERN stack**.
This app allows teams to manage projects, assign tasks, and track progress efficiently.

---

## 🌍 Live Demo

* 🔗 **Frontend**:
  https://vibrant-purpose-production.up.railway.app/

* 🔗 **Backend API**:
  https://task-managner-production-81c3.up.railway.app/api

* 🔗 **Health Check**:
  https://task-managner-production-81c3.up.railway.app/api/health

---

## 🛠️ Tech Stack

### Frontend

* React.js (Vite)
* Axios
* React Hot Toast
* Lucide Icons

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas (Mongoose)

### Authentication

* JWT (JSON Web Tokens)
* bcrypt

### Validation

* express-validator
* Mongoose schema validation

---

## 📂 Project Structure

```bash
Team-Task-Manager/
│
├── frontend/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── server.js
```

---

## ⚙️ Environment Configuration

### 📌 Frontend (`frontend/.env`)

```env
VITE_API_URL=https://task-managner-production-81c3.up.railway.app/api
```

---

### 📌 Backend (`backend/.env`)

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLIENT_URL=https://vibrant-purpose-production.up.railway.app
```

---

## 🖥️ Local Setup

### 🔹 Backend Setup

```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

---

### 🔹 Frontend Setup

```bash
cd frontend
npm install
cp .env.example .env
npm run dev
```

---

### 🌐 Local URLs

* Frontend: http://localhost:5173
* Backend: http://localhost:5000/api

---

## ✨ Features

* 🔐 User Authentication (Signup/Login with JWT)
* 🔑 Secure Password Hashing (bcrypt)
* 📁 Create and Manage Projects
* 👥 Add/Remove Project Members
* ✅ Task Assignment and Tracking
* 🧑‍💼 Role-based Access (Admin & Members)
* 📊 Dashboard Analytics (status, counts, overdue tasks)
* 🔄 REST API with proper status codes
* 🔔 Toast Notifications in UI
* 🌍 Production Deployment (Railway)

---

## 📡 API Endpoints

### 🔐 Auth

* `POST /api/auth/signup`
* `POST /api/auth/login`
* `GET /api/auth/me`

### 📁 Projects

* `GET /api/projects`
* `POST /api/projects`
* `GET /api/projects/:projectId`
* `POST /api/projects/:projectId/members`
* `DELETE /api/projects/:projectId/members/:userId`

### ✅ Tasks

* `GET /api/tasks`
* `POST /api/tasks`
* `PATCH /api/tasks/:taskId`
* `DELETE /api/tasks/:taskId`

### 📊 Dashboard

* `GET /api/dashboard`

---

## 💡 Highlights

* Production-ready full-stack app
* Clean and modular architecture
* Centralized API configuration
* Proper CORS handling
* Environment-based configuration
* Real-world deployment experience

---

## 📚 What I Learned

* Full-stack development with MERN
* Authentication using JWT
* API integration with Axios
* Deployment using Railway
* Handling real-world issues (CORS, env variables, build errors)

---

## 🤝 Contributing

Feel free to fork the repo and improve the project!

---

## 📌 Author

**Suhana Chaudhary**

---

⭐ If you like this project, give it a star!

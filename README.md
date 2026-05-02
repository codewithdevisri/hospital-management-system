# 🏥 Hospital Patient Management System

A full-stack web application to manage patients, authentication, and hospital operations.

Built using:

* ⚛️ React (Frontend)
* 🌐 Node.js + Express (Backend)
* 🗄️ MongoDB / MySQL
* 🔐 JWT Authentication

---

## 🚀 Features

### 🔐 Authentication

* User Login
* JWT-based authentication
* Protected routes

### 🧑‍⚕️ Patient Management

* Add new patients
* View patient list
* API integration with backend
* Form validation

### 📊 Dashboard

* Clean UI dashboard
* Sidebar navigation
* Patient overview

---

## 📁 Project Structure

```
hospital-management-system/

├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json

├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── api/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── public/
│   └── package.json

└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/hospital-management-system.git
cd hospital-management-system
```

---

### 2️⃣ Backend Setup

```
cd backend
npm install
```

Create a `.env` file in backend folder:

```
PORT=5000
JWT_SECRET=your_secret_key
DB_URL=your_database_url
```

Run backend:

```
npm start
```

---

### 3️⃣ Frontend Setup

```
cd frontend
npm install
npm run dev
```

---

## 🌐 API Endpoints

### 🔑 Auth Routes

```
POST /api/auth/login
POST /api/auth/register
```

### 🧑 Patient Routes

```
GET  /api/patients
POST /api/patients
```

---

## 🧪 Common Issues & Fixes

### ❌ 400 Bad Request

* Check request body format
* Ensure all required fields are sent

### ❌ No Token Error

Make sure token is sent in headers:

```
Authorization: Bearer <token>
```

---

## 🚀 Deployment

### Frontend

* Vercel / Netlify/ vercel

### Backend

* Render
* Railway
* Cyclic

⚠️ After deployment, update API base URL in frontend.

---

## 🔗 Example API Configuration

```js
import axios from "axios";

const API = axios.create({
  baseURL: "https://your-backend-url/api",
});

export default API;
```

---

## 📸 Screenshots (Optional)

* Login Page
* Dashboard
* Add Patient Form

---

## 👨‍💻 Author

Devi Sri Chekka

---

## 📄 License

This project is open-source and free to use.

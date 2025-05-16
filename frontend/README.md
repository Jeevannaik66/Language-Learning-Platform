
# 🌐 AI Language Learning Platform (MERN Stack + Auth0 + Bootstrap)

An AI-powered full-stack language learning platform built with the **MERN stack**, **Auth0**, **Bootstrap**, and integrated with OpenAI for chatbot features and **Web Speech API** for voice practice.

---

## 📦 Features

✅ User Authentication (Google OAuth + Email/Password via Auth0)  
✅ Structured Lessons, Quizzes  
✅ AI Chatbot (GPT  API)  
✅ Voice-Based Practice (Web Speech API)  
✅ Fully Responsive UI (Bootstrap)  
✅ RESTful API (Node.js + Express + MongoDB)

---

## 📁 Project Structure

```
Language-Learning-Platform/
├── frontend/         # React + Bootstrap frontend
└── backend/          # Express + MongoDB + Auth0 backend
```

---

## 🔧 Prerequisites

- Node.js v16+ installed
- MongoDB installed and running locally
- Internet connection (for Auth0, AI APIs)

---

## 🚀 Installation Guide (Step-by-Step)

---

### 🔹 1. Start from the `frontend/` folder

```bash
cd frontend
```

### 📥 Install frontend dependencies

```bash
npm install
```

### 🔹 2. Open the `backend/` folder

```bash
cd ../backend
```

### 📥 Install backend dependencies

```bash
npm install
```

If you want to install manually:

```bash
npm install express mongoose dotenv cors passport passport-google-oauth20 express-session
```

Optional (for dev auto-reload):

```bash
npm install --save-dev nodemon
```

---

## 📲 How to Run the Project

---

### ✅ Start MongoDB

Make sure MongoDB is running locally.


### ✅ Start Backend Server

```bash
cd backend
npm start
# OR if using nodemon
 nodemon server.js

Backend will run on `http://localhost:5000`

---

### ✅ Start Frontend React App

```bash
cd ../frontend
npm start
```

Frontend will run on `http://localhost:3000`

---

## 💬 API Endpoints Overview (Backend)

| Endpoint                  | Description                            |
|---------------------------|----------------------------------------|
| `/api/auth/*`            | Auth0 / Google login                   |
| `/api/lessons`           | Get lessons, complete lesson           |
| `/api/quizzes`           | Get quizzes, submit answers            |
| `/api/chatbot`           | AI-powered GPT/HuggingFace chatbot     |

---

## 🎨 Frontend Tech Used

- React
- React Router
- Bootstrap + React-Bootstrap
- Axios
- Web Speech API
- Auth0 SDK

---

## 🛠 Backend Tech Used

- Node.js
- Express
- MongoDB + Mongoose
- Passport.js (Google OAuth)
- Auth0 (JWT)
- OpenRouter API (for GPT)
- Nodemailer (email)
- dotenv, cors


## 📌 Final Notes

Make sure:

- All keys in `.env` are filled correctly
- MongoDB is running before starting backend
- CORS settings match your frontend URL

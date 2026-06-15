# 🚀 DevFlow AI

An AI-powered developer productivity platform built using the MERN Stack and Gemini AI.

## 📌 Overview

DevFlow AI helps developers and freshers:

- Understand programming errors
- Review code quality
- Break down development tasks
- Analyze repository architecture
- Track productivity

---

## ✨ Features

### 🔐 Authentication

- Register User
- Login User
- JWT Authentication
- Protected Routes

### 🤖 AI Error Explainer

Input:

```txt
TypeError: Cannot read properties of undefined
```

Output:

- Error Explanation
- Root Cause
- Fix Suggestions
- Example Solution

### 📝 Code Review Assistant

Analyze code for:

- Bugs
- Best Practices
- Performance Issues
- Code Quality

### 📋 Task Breakdown Generator

Input:

```txt
Build authentication module
```

Output:

```txt
1. Create User Model
2. Create Register API
3. Create Login API
4. Add JWT Authentication
5. Protect Routes
```

### 📂 Repository Architecture Explainer

Analyze GitHub repositories and explain:

- Frontend Structure
- Backend Structure
- Authentication Flow
- Database Design
- Folder Structure

### 📊 Productivity Analytics

Track:

- Errors Solved
- AI Requests
- Tasks Completed
- Learning Progress

---

## 🏗️ System Architecture

```text
User
  |
  v
React Frontend
  |
  v
Express Backend
  |
  +------ MongoDB Atlas
  |
  +------ Gemini API
```

---

## 🛠️ Tech Stack

### Frontend

- React.js
- React Router DOM
- Axios
- Tailwind CSS

### Backend

- Node.js
- Express.js

### Database

- MongoDB Atlas
- Mongoose

### Authentication

- JWT
- bcryptjs

### AI

- Gemini API

### Deployment

- Vercel
- Render

---

## 📁 Folder Structure

```text
devflow-ai
│
├── client
│   ├── src
│   ├── pages
│   ├── components
│   └── services
│
└── server
    ├── config
    ├── controllers
    ├── middleware
    ├── models
    ├── routes
    ├── .env
    ├── index.js
    └── package.json
```

---

## 🔄 User Flow

```text
User
 ↓
Register/Login
 ↓
JWT Generated
 ↓
Dashboard
 ↓
Select Feature
 ↓
Frontend API Request
 ↓
Backend Processing
 ↓
Gemini AI
 ↓
MongoDB Save
 ↓
Response Displayed
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/devflow-ai.git
```

### Backend Setup

```bash
cd server

npm install
```

Create `.env`

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_api_key
```

Run Server

```bash
npm run dev
```

### Frontend Setup

```bash
cd client

npm install

npm start
```

---

## 🎯 Learning Outcomes

This project demonstrates:

- Full Stack Development
- REST APIs
- Authentication & Authorization
- MongoDB Database Design
- AI Integration
- Cloud Deployment
- Real-world Problem Solving

---

## 🔮 Future Improvements

- GitHub Repository Scanner
- AI Documentation Generator
- Team Collaboration
- Coding Interview Assistant
- Learning Recommendations

---

## 👨‍💻 Author

**Payal Sawant**

Aspiring Software Developer | MERN Stack Developer | AI Enthusiast

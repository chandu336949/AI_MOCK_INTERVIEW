# 🚀 AI-Powered Mock Interview Platform

An intelligent full-stack AI-powered mock interview platform that simulates real technical interviews with voice interaction, coding challenges, AI evaluation, and personalized feedback.

---

# 📌 Problem Statement

Many students and developers know concepts well but struggle during real interviews because of:

- Nervousness
- Lack of communication practice
- No real interview simulation
- Limited mock interview opportunities
- Expensive coaching sessions

Traditional preparation methods like:
- Watching YouTube videos
- Reading interview questions
- Practicing silently
- Asking friends for mock interviews

do not fully prepare candidates for real interview pressure.

---

# 💡 Solution

This platform provides an AI interviewer available 24/7 that:

✅ Generates personalized interview questions  
✅ Conducts voice-based interviews  
✅ Supports live coding challenges  
✅ Evaluates answers using AI  
✅ Provides detailed performance feedback  
✅ Stores interview history and analytics  

---

# ✨ Features

| Feature | Description |
|---|---|
| Resume-Based Questions | AI analyzes resume and generates personalized questions |
| Voice Interviews | AI asks questions using realistic voice |
| Speech-to-Text | Converts spoken answers into text |
| Live Coding | Monaco Editor for coding interviews |
| AI Feedback | AI-generated detailed performance evaluation |
| Multi-Role Support | Frontend, Backend, Full Stack, DevOps, Data Analyst etc |
| Interview History | Stores previous interviews and feedback |
| Authentication | JWT-based login and signup system |

---

# 🛠️ Tech Stack

## Frontend
- React.js
- React Router DOM
- Axios
- Monaco Editor
- CSS / Bootstrap / Tailwind

## Backend
- Node.js
- Express.js
- MongoDB Atlas
- JWT Authentication

## AI APIs
- Google Gemini AI
- Murf AI (Text-to-Speech)
- AssemblyAI (Speech-to-Text)

---

# 📂 Project Structure

```bash
project/
│
├── client/      # React Frontend
│
├── server/      # Node.js Backend
│
└── README.md
```

---

# ⚙️ Prerequisites

Before running this project, make sure you have:

- VS Code
- Node.js Installed
- MongoDB Atlas Account
- Google Gemini API Key
- Murf AI API Key
- AssemblyAI API Key

---

# 🔑 Environment Variables

Create a `.env` file inside the `server` folder and add the following:

```env
PORT=5000
NODE_ENV=development

MONGODB_URI=YOUR_MONGODB_URI

JWT_SECRET=YOUR_SECRET_KEY
JWT_EXPIRES_IN=7d

GEMINI_API_KEY=YOUR_GEMINI_API_KEY
MURF_API_KEY=YOUR_MURF_API_KEY
ASSEMBLYAI_API_KEY=YOUR_ASSEMBLYAI_API_KEY

```

---

# ⚠️ Important Security Note

❌ Never push your real API keys or MongoDB credentials to GitHub.

Add `.env` to `.gitignore`.

Example:

```gitignore
.env
node_modules
```

---

# 📦 Installation

## 1️⃣ Clone Repository

```

---

## 2️⃣ Install Backend Dependencies

```bash
cd server
npm install
```

---

## 3️⃣ Install Frontend Dependencies

```bash
cd client
npm install
```

---

# ▶️ Running the Project

## Start Backend Server

```bash
cd server
node server.js
```

---

## Start Frontend Client

Open a new terminal:

```bash
cd client
npm run dev
```

---

# 🌐 Local Development URLs

Frontend:

```bash
http://localhost:5173
```

Backend:

```bash
http://localhost:5000
```

---
## 🚀 Live Demo

You can explore the live deployment here:

* **Live Web Application:** [https://interviewgen-ai.vercel.app](https://interviewgen-ai.vercel.app)

> 💡 **Note for Reviewers:** The frontend is hosted on Vercel and connects to a backend hosted on Render's free tier. If you are logging in or signing up for the first time, the backend server may take about **50-60 seconds** to wake up from its sleep cycle. Thank you for your patience!

# 🧠 Functionalities Implemented

## ✅ Functionality 1: Resume Upload & Interview Setup

### Steps Implemented
1. Gemini AI integration and prompt templates
2. Resume model and PDF parsing
3. Interview setup service
4. Multi-step setup wizard UI

### Features
- Resume upload
- Resume parsing
- Personalized question generation
- Role selection

---

## ✅ Functionality 2: AI Interview System

### Steps Implemented
5. Voice-to-text transcription
6. Text-to-speech integration
7. AI evaluation routes
8. Interview page state management

### Features
- AI voice interviewer
- Speech recognition
- Real-time interview flow
- Coding interview support
- Monaco code editor

---

## ✅ Functionality 3: Feedback & History

### Steps Implemented
9. Feedback generation logic
10. Interview history APIs
11. Feedback and history pages

### Features
- AI-generated feedback
- Performance scoring
- Interview analytics
- Previous interview tracking

---

# 🏗️ System Architecture

```text
React Frontend
       ↓
Axios API Layer
       ↓
Node.js + Express Backend
       ↓
MongoDB Atlas Database
       ↓
AI Services
(Gemini AI + Murf AI + AssemblyAI)
```

---

# 📸 Future Enhancements

- Webcam-based interview analysis
- Emotion detection
- AI improvement roadmap
- Company-specific interview rounds
- Leaderboards
- Real-time collaboration
- Advanced analytics dashboard

---

# 🌍 Real World Platforms Inspiration

- Pramp
- InterviewBuddy
- Google Interview Warmup

---

# 👩‍💻 Author

## Chandu Sri
BTech CSE Student  
AI & Full Stack Developer  

---

# 🤝 Collaborator

- Lohit Ganugula


# 📜 License

This project is developed for educational and learning purposes.

 # AI Habit Tracker

An AI-powered full-stack habit tracking application built using the MERN stack that helps users build consistency, monitor progress, visualize analytics, and receive intelligent AI-generated insights and recommendations.

---

# 🚀 Features

## 🔐 Authentication & Security

- User Registration & Login
- JWT-based Authentication
- Protected Routes
- Persistent User Sessions
- Secure API Access

---

## 📌 Habit Management

- Create, Update, and Delete Habits
- Daily Habit Tracking
- Habit Categories
- Streak Management
- Weekly Habit Planning
- Progress Monitoring

---

## 🤖 AI-Powered Features

- AI Habit Insights
- AI Chat Assistant
- AI Weekly Reports
- Personalized Habit Suggestions
- Motivational Recommendations
- Intelligent Progress Analysis

---

## 📊 Analytics & Visualization

- Heatmap Activity Tracking
- Weekly Progress Charts
- Monthly Analytics
- Category-wise Pie Charts
- Progress Rings
- Summary Statistics Cards
- Habit Performance Dashboard

---

## 🎨 User Experience

- Responsive UI
- Dark/Light Theme Support
- Interactive Dashboard
- Reusable Component Architecture
- Clean Modern Interface
- Real-time Feedback

---

# 🛠️ Tech Stack

## Frontend

- React.js
- Vite
- Axios
- Context API
- CSS
- Chart Libraries

---

## Backend

- Node.js
- Express.js
- REST APIs
- JWT Authentication
- Middleware Architecture

---

## Database

- MongoDB
- Mongoose

---

## AI Integration

- AI Service Integration
- Smart Habit Analysis
- AI Recommendation System

---

# 📁 Project Structure

## Backend Structure

```bash
backend/
│
├── config/
├── controllers/
├── middleware/
├── models/
├── routes/
├── scripts/
├── utils/
├── package.json
└── .env
```

---

## Frontend Structure

```bash
frontend/
│
├── public/
├── src/
│   ├── api/
│   ├── assets/
│   ├── components/
│   ├── context/
│   ├── pages/
│   ├── utils/
│   ├── App.jsx
│   └── main.jsx
│
├── package.json
└── .env
```

---

# ⚙️ Installation & Setup

## Clone Repository

```bash
git clone https://github.com/HarishBirla/AI-Habit-Tracker
```

---

## Backend Setup

```bash
cd backend
npm install
npm run dev
```

---

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

# 🔑 Environment Variables

## Backend `.env`

```env
PORT=

MONGO_URI=

JWT_SECRET=

GEMINI_API_KEY=

GEMINI_MODEL=
```

---

## Frontend `.env`

```env
VITE_API_BASE_URL=
```

---

# 📊 Core Functionalities

## Habit Tracking System

Users can:

- Track daily habits
- Maintain streaks
- View completion statistics
- Analyze productivity patterns

---

## AI Insight Engine

The AI module analyzes:

- Habit consistency
- Completion trends
- Productivity behavior
- Weekly performance

and generates:

- Personalized recommendations
- Motivational suggestions
- Smart improvement insights

---

## Analytics Dashboard

The dashboard provides:

- Visual charts
- Heatmaps
- Weekly reports
- Monthly statistics
- Category distribution
- Progress tracking

---

# 🧠 System Architecture

```text
Frontend (React)
        ↓
REST API Calls (Axios)
        ↓
Backend Server (Express.js)
        ↓
Controllers & Middleware
        ↓
MongoDB Database
        ↓
AI Service Integration
```

---

# 🔒 Security Features

- JWT Token Authentication
- Protected API Routes
- Middleware-based Authorization
- Secure Environment Variables
- Error Handling Middleware

---

# 📈 Challenges Faced

- Managing dynamic streak calculations
- Designing reusable chart components
- Handling AI-generated responses efficiently
- Building scalable frontend architecture
- Managing state across multiple pages
- Integrating analytics visualizations

---

# 🔮 Future Improvements

- Mobile Application
- Push Notifications
- Social Habit Sharing
- AI Prediction System
- Gamification Features
- Cloud Deployment
- Advanced Analytics
- Improved AI Recommendation Engine

---

 

# 📌 API Endpoints

## Authentication Routes

```text
POST   /api/auth/register
POST   /api/auth/login
GET    /api/auth/profile
```

---

## Habit Routes

```text
GET    /api/habits
POST   /api/habits
PUT    /api/habits/:id
DELETE /api/habits/:id
```

---

## AI Routes

```text
POST   /api/ai/insights
POST   /api/ai/chat
POST   /api/ai/report
```

---

# 👨‍💻 Author

## Harish Birla

B.Tech CSE Student  
Full Stack & AI Enthusiast

---

# ⭐ Project Highlights

- Full-stack MERN Architecture
- AI-powered Analytics
- Interactive Data Visualization
- Production-style Folder Structure
- Reusable Component Architecture
- Real-world Productivity Use Case
- Scalable Backend Design

---

# 📄 License

This project is licensed under the MIT License.

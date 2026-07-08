# 🚀 LearnBridge+ V2.0


LearnBridge+ is a next-generation AI-powered educational platform designed to bridge the gap between students and their career goals. It provides personalized learning paths, community engagement, gamification, and advanced AI tools to enhance the learning experience.

## ✨ Key Features

- **🤖 AI-Powered Tools**: Resume Analyzer, Skill Gap Analysis, Learning Path Generator, and a smart chatbot (LearnBuddy).
- **🎯 Custom Goal Engine**: Set predefined goals (e.g., Crack FAANG) or custom goals with 3-12 month AI-generated action plans.
- **🤝 Peer Learning & Community**: Leaderboards, 4 challenge types, XP/badges, and discoverable Community Groups with real-time chat and resource sharing.
- **🎮 Gamification**: Experience points (XP), ranks, streaks, badges, and achievements to keep learners motivated.
- **📚 Course & Internship Hub**: Enroll in courses, take quizzes, and apply for relevant internships.
- **🛡️ Role-Based Access**: Specialized dashboards for Students, Faculty, and Admins.
- **👤 Enhanced Profiles**: Visualize learning hours, problems solved, skills progress, and recent activity.

## 🛠️ Technology Stack

- **Frontend**: React (Vite), Tailwind CSS, Framer Motion
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **AI Integrations**: OpenAI, Gemini, Mistral APIs
- **Authentication**: JWT & OTP verification

## 🚀 Quick Start

### Prerequisites

- Node.js (v20.19.0+ recommended)
- MongoDB (local or Atlas)
- Git

### 1. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` directory:
```env
PORT=5000
CLIENT_URL=http://localhost:5173
MONGO_URI=mongodb://localhost:27017/learnbridge-plus
JWT_SECRET=your-super-secret-jwt-key
# AI APIs (Add keys as needed)
OPENAI_API_KEY=your-openai-api-key
GEMINI_API_KEY=your-gemini-api-key
```

Start the backend server:
```bash
npm run dev
```

### 2. Setup Frontend

```bash
cd ../frontend
npm install
```

Create a `.env` file in the `frontend` directory:
```env
VITE_API_URL=http://localhost:5000/api
```

Start the frontend server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`.

## 📂 Project Structure

```
learnbridge-plus-v2/
├── backend/          # Express API, MongoDB models, Controllers, Services
└── frontend/         # React application, Vite config, UI Components
```

## 📖 Complete Documentation

For detailed installation instructions, API endpoints, troubleshooting, and deployment guidelines, please refer to the [SETUP_GUIDE.md](./SETUP_GUIDE.md).

For a deep dive into the specific features implemented in V2 (Custom Goals, Peer Learning, Groups, etc.), see the [FINAL_COMPLETION_SUMMARY.md](./FINAL_COMPLETION_SUMMARY.md).



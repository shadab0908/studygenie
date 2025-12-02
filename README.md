# StudyGenie

AI-powered study companion that generates summaries, notes, quizzes, flashcards, and helps students prepare smarter.

## 🚀 Vision
StudyGenie aims to become the **AI-powered personal tutor** for every student. It converts any study material (PDF, image, text, lecture notes) into:
- Summaries
- Notes
- Flashcards
- MCQs & quizzes
- Concept maps
- Doubt-solving chats

## 🧠 Core Features (MVP)
- **Upload PDF/Image/Text**
- **AI Summary Generator**
- **AI Flashcard Generator**
- **AI Quiz Generator**
- **Smart Doubt Chatbot** (context-aware)
- **History + Save Notes**

## 🏗️ Tech Stack
**Frontend:** React + Tailwind + Vite  
**Backend:** Node.js (Express)  
**Database:** MongoDB Atlas  
**Storage:** Firebase Storage  
**Auth:** Firebase Auth  
**AI:** OpenAI GPT / Gemini  

## 📁 Project Structure
```
studygenie/
  ├── backend/
  │   ├── src/
  │   ├── routes/
  │   ├── controllers/
  │   ├── models/
  │   └── utils/
  ├── frontend/
  │   ├── src/
  │   ├── components/
  │   ├── pages/
  │   └── hooks/
  └── README.md
```

## 🧩 API Endpoints (MVP)
```
POST /api/upload  → Upload PDF/Image
POST /api/summarize → Generate summary
POST /api/flashcards → Generate flashcards
POST /api/quiz → Generate MCQs
POST /api/chat → Ask doubts
```

## 🔑 Environment Variables
Create `.env` inside backend:
```
MONGO_URI=
OPENAI_API_KEY=
FIREBASE_STORAGE_BUCKET=
FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

## ▶️ Local Setup
### Backend
```
cd backend
npm install
npm run dev
```

### Frontend
```
cd frontend
npm install
npm run dev
```

## 📌 Roadmap
- Add user dashboard
- Topic-wise study planner
- AI personalized learning paths
- Export notes as PDF
- Voice-based Q&A

## 🤝 Contributing
This project is under rapid development. PRs are welcome!

## 📜 License
MIT License

---
Built with ❤️ by Shadab & ChatGPT (Co-founder Mode)

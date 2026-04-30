# Synapto-Learn

Synapto-Learn is a MERN-based AI learning assistant that helps users upload study PDFs and convert them into interactive learning resources like summaries, flashcards, quizzes, and document-based AI chat.


## Features

- User authentication with JWT
- Upload and manage PDF documents
- View uploaded PDFs in browser
- AI-powered document summaries
- Generate flashcards from PDFs
- Generate quizzes from study material
- Chat with uploaded documents
- Track learning progress
- Responsive dashboard UI

## Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- React Router
- Axios
- React Hot Toast
- Lucide React

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Multer
- Google Gemini API

## Folder Structure

```txt
Synapto-Learn/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   └── ai-learning-assistant/
│       ├── public/
│       ├── src/
│       ├── index.html
│       ├── vite.config.js
│       └── package.json
│
└── README.md

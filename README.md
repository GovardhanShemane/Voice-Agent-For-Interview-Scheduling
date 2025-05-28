🎙️ Voice Agent Interview Scheduler
An end-to-end voice-driven interview scheduling system built with Node.js, Express, MySQL, React.js, and integrated with voice technologies like Vosk, Mozilla TTS, and Rasa/Mycroft.

🚀 Features
✅ Add, update, and delete job postings

✅ Add and manage candidate data

✅ Automatically schedule interviews using available time slots

✅ Voice agent integration for call-based data collection (demo-based)

✅ Candidate-conversation and appointment management

✅ RESTful API with proper error handling and validation

🛠️ Tech Stack
🔹 Backend:
Node.js

Express.js

MySQL

Axios

CORS & dotenv

🔹 Frontend:
React.js

Axios

React Router

🔹 Voice Technologies (Concept Demo):
Vosk (Voice recognition)

Mozilla TTS (Text to Speech)

Rasa / Mycroft (NLP/Dialog system)

📁 Folder Structure
arduino
Copy
Edit
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── routes/
│   ├── server.js
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.js
🧪 How to Run Locally
🔧 Backend
bash
Copy
Edit
cd backend
npm install
node server.js
Make sure your MySQL database is running and configured properly.

🌐 Frontend
bash
Copy
Edit
cd frontend
npm install
npm run dev
Visit http://localhost:5173 to use the app.

🗄️ Database Schema (MySQL)
jobs: id, title, description, requirements, created_at

candidates: id, name, email, phone, etc.

appointments: id, candidateId, jobId, time

conversations: id, candidateId, transcript, created_at

📽️ Demo Video
👉 Watch the Demo (Replace with actual link)


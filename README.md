PingMe 💬

PingMe is a real-time chat application built with the MERN stack. It supports one-to-one and group messaging, user authentication, and live updates via WebSockets.

🚀 Features

🔐 User Authentication – Secure signup/login using JWT & bcrypt.

👥 One-to-One & Group Chat – Send direct messages or chat in groups.

⚡ Real-Time Messaging – Powered by Socket.io for instant delivery.

📩 Message APIs – REST APIs for creating, fetching, and managing chats.

🎨 Frontend – Built with React + Chakra UI for a clean UI.

🗄️ Backend – Node.js + Express + MongoDB with Mongoose models.

🛠️ Tech Stack

Frontend: React, Chakra UI

Backend: Node.js, Express.js

Database: MongoDB (Mongoose ODM)

Real-time: Socket.io

Authentication: JWT, bcrypt

📂 Project Structure
PingMe/
│
├── backend/        # Express + MongoDB API
│   ├── models/     # User, Chat, Message schemas
│   ├── routes/     # Authentication, Chat, Message APIs
│   └── server.js   # Entry point
│
├── frontend/       # React UI
│   ├── src/
│   └── public/
│
└── README.md

⚡ Getting Started
Backend Setup
cd backend
npm install
npm run dev

Frontend Setup
cd frontend
npm install
npm start

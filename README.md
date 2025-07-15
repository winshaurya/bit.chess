
# ♟️ Bit.Chess – Real-Time Online Chess Game

[![Socket.IO](https://img.shields.io/badge/WebSocket-Socket.IO-black?logo=socket.io)](https://socket.io/)
[![Node.js](https://img.shields.io/badge/Backend-Node.js-green?logo=node.js)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/API-Express.js-black?logo=express)](https://expressjs.com/)
[![React](https://img.shields.io/badge/Frontend-React-blue?logo=react)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Style-Tailwind_CSS-06B6D4?logo=tailwindcss)](https://tailwindcss.com/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-4EA94B?logo=mongodb)](https://mongodb.com/)
[![JWT](https://img.shields.io/badge/Auth-JWT-yellow?logo=jsonwebtokens)](https://jwt.io/)
[![Vite](https://img.shields.io/badge/Bundler-Vite-purple?logo=vite)](https://vitejs.dev/)

---

<p align="center">
  <img src="assets/bitchess_demo.gif" alt="bit.chess demo" width="700"/>
</p>

---

## 🧠 Project Overview

Hi, I’m [Shaurya Mishra](https://www.linkedin.com/in/shaurya-mishra-0b4751204/) — a web and AI enthusiast. I built **Bit.Chess** as a fun project to play real-time chess with my friend.  
In the process, I learned how to build multiplayer, real-time applications using **WebSockets** and **Socket.IO**.

This app supports:
- 🎮 Real-time 2-player chess matches
- ♻️ Move synchronization via Socket.IO
- 🔐 Secure authentication via JWT
- 🎨 Sleek responsive UI with Tailwind and React
- 🧠 Backend with Node.js + Express
- 📦 MongoDB for user and game data storage

---

## ✨ Features

- ♟️ Play live chess against friends
- 👥 Multiplayer lobby system
- 🔒 Auth system with JWT tokens
- 📡 WebSocket-powered move synchronization
- 🌐 Fully responsive UI
- 🚀 Vite for fast React builds

---

## 🛠 Tech Stack

| Layer        | Tech                             |
|--------------|----------------------------------|
| **Frontend** | ![React](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg) React, ![Tailwind](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg) Tailwind CSS, Vite |
| **Backend**  | ![Node.js](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg) Node.js, ![Express](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg) Express |
| **Real-time**| ![Socket.IO](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/socketio/socketio-original.svg) Socket.IO |
| **Database** | ![MongoDB](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg) MongoDB |
| **Auth**     | JWT (JSON Web Token) |
| **Other**    | Chessboard rendering logic, chess.js, REST APIs |

---

## 📷 Screenshots

> 🎥 Demo preview or game in action:

| Gameplay Preview |
|------------------|
| ![Game Demo](assets/bitchess_demo.gif) |

---

## 📁 Project Structure

```
bit.chess/
├── client/                 # React + Tailwind Frontend
│   └── ...
├── server/                 # Node.js + Express Backend
│   └── ...
├── socket/                 # Socket.IO logic
├── assets/                 # Screenshots, demo GIFs
└── README.md
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/winshaurya1/bit.chess.git
cd bit.chess

# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install

# Run backend
npm start

# In another terminal, run frontend
cd ../client
npm run dev
```

Make sure MongoDB is running locally or use a cloud MongoDB URI.

---

## 📌 What I Learned

- Real-time bidirectional communication using **WebSockets**
- How **Socket.IO** handles events and rooms
- Managing frontend and backend sockets
- Using **JWT** for secure user authentication
- Chessboard rendering logic and multiplayer synchronization
- Organizing full-stack projects with **MongoDB**, **Node.js**, and **React**

---

## 📬 Connect with Me

I'm always open to feedback or collaborations on exciting real-time projects or AI systems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shaurya%20Mishra-blue?logo=linkedin)](https://www.linkedin.com/in/shaurya-mishra-0b4751204/)  
[![GitHub](https://img.shields.io/badge/GitHub-winshaurya1-black?logo=github)](https://github.com/winshaurya1)

---

## 📄 License

MIT License — use, remix, and share with credit.

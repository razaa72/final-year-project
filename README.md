--> Final Year Project

This repository contains a **Full-Stack Web Application** built with:

- Frontend: React (Vite)
- Backend: Node.js + Express

Both parts work together to provide a complete system.

---

--> Project Structure

frontend/ → React client (UI)
backend/ → Node.js server (API & Authentication)

yaml
Copy code

---

--> Getting Started

rerequisites
Install the following before running the project:

Node.js (LTS recommended)
npm (comes with Node)

---

--> To Run Backend


npm install
npm start       # or: npm run dev
Backend will start on:
http://localhost:4000 (or your configured port)

--> Run Frontend

cd frontend
npm install
npm run dev
Frontend will start on:
http://localhost:5173 (default Vite port)

--> Environment Variables
Create .env files locally

backend/.env.example

PORT=4000
MONGO_URI=your_mongo_uri
JWT_SECRET=your_secret
frontend/.env.example

VITE_API_URL=http://localhost:4000
📦 Scripts Quick Reference
Location	Command	Description
Backend	npm start	Start backend server
Backend	npm run dev	Run backend in dev mode
Frontend	npm run dev	Run React development server
Frontend	npm run build	Build for production

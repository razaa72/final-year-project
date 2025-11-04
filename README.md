# Final Year Project

This repository contains a Full-Stack Web Application built with:

- Frontend: React (Vite)
- Backend: Node.js and Express

Both parts work together to provide a complete system.

---

## Project Structure

Frontend and backend are separated into two folders:

frontend/ - React client (User Interface)
backend/ - Node.js server (API & Authentication)

---

## Getting Started

### Prerequisites

Install the following before running the project:

- Node.js (LTS recommended)
- npm (comes with Node.js)

---

### Running the Backend

cd backend
npm install
npm start # or: npm run dev


Backend will by default run on:

http://localhost:4000

---

### Running the Frontend

cd frontend
npm install
npm run dev


Frontend will run on:

http://localhost:5173

---

## Environment Variables

Create `.env` files locally (do not upload real secrets to GitHub).

### backend/.env.example

PORT=4000
MONGO_URI=your_mongo_uri
JWT_SECRET=your_secret


### frontend/.env.example

VITE_API_URL=http://localhost:4000

---

## Scripts Reference

| Location  | Command         | Description                   |
|-----------|-----------------|-------------------------------|
| Backend   | npm start       | Start backend server          |
| Backend   | npm run dev     | Run backend in development    |
| Frontend  | npm run dev     | Run React development server  |
| Frontend  | npm run build   | Build for production          |

---

## Notes

- `node_modules` is ignored via `.gitignore`
- Never commit real `.env` files to GitHub
- Environment variables must be set on the server when deploying

# CampusSync (Starter Project)

This is a modular full-stack starter for your CampusSync project with separate folders:

- `backend` (Node.js + Express + MongoDB + JWT)
- `frontend` (React + Vite)

## Implemented Starter Modules

- Authentication (register, login, profile, role support)
- Q&A module (post question, list questions, answer as mentor/admin)
- Squad Finder (skills update, team create/join)
- Events (create events, list events, register with seat checks)
- Notifications (list notifications, admin broadcast, mark read)

## 1) Open in VS Code / Cursor

Open folder:

`/home/aman/Downloads/CampusSync`

## 2) Backend Setup

```bash
cd backend
cp .env.example .env
npm install
npm run dev
```

Backend runs on: `http://localhost:5000`

## 3) Frontend Setup

Open a second terminal:

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on: `http://localhost:5173`

## Important

- Ensure MongoDB is running locally (`MONGO_URI` in `.env`).
- Institutional email check currently accepts addresses ending with `.edu` or containing `@geu.ac.in`.
- You can now edit each module in separate files inside `backend/src/routes` and `backend/src/models`.

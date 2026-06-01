# OctoFit Tracker

This workspace contains the OctoFit Tracker multi-tier application scaffold.

Ports used:
- Frontend (Vite): 5173
- Backend (Express): 8000
- MongoDB: 27017

Quick start (run these commands from workspace root):

Install frontend dependencies and start dev server:

```bash
npm install --prefix octofit-tracker/frontend
npm run dev --prefix octofit-tracker/frontend
```

Install backend dependencies and start dev server:

```bash
npm install --prefix octofit-tracker/backend
npm run dev --prefix octofit-tracker/backend
```

Set MongoDB connection with `MONGO_URI` if needed. The backend defaults to `mongodb://localhost:27017/octofit`.

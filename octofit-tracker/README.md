# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js/Express, and MongoDB.

## Architecture

- **Frontend**: React 19 + Vite (Port: 5173)
- **Backend**: Node.js + Express + TypeScript (Port: 8000)
- **Database**: MongoDB (Port: 27017)

## Project Structure

```
octofit-tracker/
├── frontend/          # React 19 application
│   ├── src/
│   ├── package.json
│   ├── vite.config.ts
│   └── index.html
└── backend/           # Express API server
    ├── src/
    ├── package.json
    └── tsconfig.json
```

## Setup Instructions

### Frontend

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

The frontend will be available at `http://localhost:5173`

### Backend

```bash
cd octofit-tracker/backend
npm install
npm run dev
```

The backend API will be available at `http://localhost:8000`

### MongoDB

Ensure MongoDB is running on `localhost:27017`

## Development

- Frontend: Hot module reload with Vite
- Backend: TypeScript with ts-node for development
- Database: Mongoose for MongoDB data access

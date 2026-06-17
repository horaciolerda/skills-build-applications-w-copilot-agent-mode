# 🐙 OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js/Express, and MongoDB.

## 🏗️ Architecture

- **Frontend**: React 19 + Vite (Port: **5173**)
- **Backend**: Node.js + Express + TypeScript (Port: **8000**)
- **Database**: MongoDB (Port: **27017**)

## 📁 Project Structure

```
octofit-tracker/
├── frontend/                 # React 19 application
│   ├── src/
│   │   ├── App.tsx          # Main App component
│   │   ├── App.css          # App styles
│   │   ├── main.tsx         # React entry point
│   │   └── index.css        # Global styles
│   ├── package.json         # Frontend dependencies
│   ├── vite.config.ts       # Vite configuration
│   ├── tsconfig.json        # TypeScript config
│   ├── index.html           # HTML entry point
│   └── tsconfig.node.json
│
├── backend/                  # Express API server
│   ├── src/
│   │   └── index.ts         # Express server with MongoDB
│   ├── package.json         # Backend dependencies
│   └── tsconfig.json        # TypeScript config
│
├── README.md                # This file
└── .gitignore
```

## 🚀 Quick Start

### Prerequisites
- Node.js (v18 or higher)
- MongoDB running on localhost:27017

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

Frontend will be available at: `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
npm run dev
```

Backend will be available at: `http://localhost:8000`

API Health Check: `http://localhost:8000/api/health`

## 🔧 Development

- **Frontend**: Hot module reload with Vite
- **Backend**: TypeScript with ts-node for development
- **Database**: Mongoose for MongoDB data access

## 📦 Dependencies

### Frontend
- React 19
- React DOM 19
- Vite 5
- TypeScript

### Backend
- Express 4.18
- Mongoose 7.0
- TypeScript
- ts-node

## 📝 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/health` | Health check endpoint |

## 🎯 Next Steps

1. Define MongoDB models in `backend/src/models/`
2. Create API routes in `backend/src/routes/`
3. Build React components in `frontend/src/components/`
4. Set up state management (if needed)
5. Add authentication (JWT/OAuth)

---

**Port Configuration:**
- Frontend (Vite): `5173`
- Backend (Express): `8000`
- Database (MongoDB): `27017`
# OctoFit Tracker

A modern multi-tier fitness tracking application built with React, Node.js, Express, TypeScript, and MongoDB.

## Architecture

- **Frontend**: React 19 with Vite (Port: 5173)
- **Backend**: Node.js + Express + TypeScript (Port: 8000)
- **Database**: MongoDB (Port: 27017)

## Getting Started

### Prerequisites
- Node.js v18+
- MongoDB running locally or remote connection string

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

The frontend will be available at `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```

The backend API will be available at `http://localhost:8000`

## API Endpoints

- `GET /api/health` - Health check endpoint

## Database

MongoDB connection:
- Local: `mongodb://localhost:27017/octofit`
- Remote: Update `MONGODB_URI` in `.env`

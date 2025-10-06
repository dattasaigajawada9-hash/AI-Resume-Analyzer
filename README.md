# AI-Resume-Analyzer

This repository contains an initial minimal backend implementation located in the `backend/` folder.

Quick start (Windows PowerShell):

```powershell
cd backend
npm install
npm start
```

Endpoints:
- GET / -> health check
- POST /analyze -> accepts JSON `{ "text": "...resume text..." }` and returns a small placeholder analysis

The backend is intentionally minimal. It's a good starting point for wiring up an AI-powered resume parser or hooking into an LLM inference service.

License: MIT
# AI-Resume-Analyzer
i
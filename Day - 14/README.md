# 🚀 Day 14 - Services Workflow

## 📌 Overview
This workflow demonstrates how to use service containers (like Redis) in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-14.yml
└── Day-14/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Starts a Redis service container
- Connects to the service from workflow
- Verifies service availability

## 📂 Files
- `.github/workflows/day-14.yml` → Workflow definition  
- `Day-14/README.md` → Documentation  

## ▶️ Key Steps
1. Define service container (`redis`)  
2. Expose service port  
3. Connect from workflow runner  
4. Validate service using network check  

## 🎯 Purpose
To understand:
- Service containers in GitHub Actions  
- Running dependencies (DB, cache) in CI  
- Container-based testing  

---
✅ Day 14 completed
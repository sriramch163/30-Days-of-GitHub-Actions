# 🚀 Day 29 - CI/CD with Rollback

## 📌 Overview
This workflow demonstrates a complete CI/CD pipeline with rollback handling in case of failure.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-29.yml
└── Day-29/
    └── README.md
```

## ⚙️ What it does
- Runs build, test, and deploy stages
- Simulates deployment failure
- Triggers rollback when deployment fails
- Demonstrates failure recovery

## 📂 Files
- `.github/workflows/day-29.yml` → Workflow definition  
- `Day-29/README.md` → Documentation  

## ▶️ Key Steps
1. Build application  
2. Run tests  
3. Deploy application  
4. Detect failure  
5. Trigger rollback  

## 🎯 Purpose
To understand:
- CI/CD pipeline with rollback  
- Failure handling strategies  
- Reliable deployment design  

---
✅ Day 29 completed
# 🚀 Day 18 - Job Outputs Workflow

## 📌 Overview
This workflow demonstrates how to pass data between jobs using outputs in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-18.yml
└── Day-18/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Sets output in one job
- Passes output to another job
- Displays shared data

## 📂 Files
- `.github/workflows/day-18.yml` → Workflow definition  
- `Day-18/README.md` → Documentation  

## ▶️ Key Steps
1. Define job outputs  
2. Set output using `$GITHUB_OUTPUT`  
3. Use `needs` to access previous job  
4. Read output in next job  

## 🎯 Purpose
To understand:
- Job outputs  
- Data sharing between jobs  
- Pipeline communication  

---
✅ Day 18 completed
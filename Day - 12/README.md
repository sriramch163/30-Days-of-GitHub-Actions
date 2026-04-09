# 🚀 Day 12 - Manual Input Workflow

## 📌 Overview
This workflow demonstrates how to trigger workflows manually with user-defined inputs in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-12.yml
└── Day-12/
    └── README.md
```

## ⚙️ What it does
- Allows manual trigger using GitHub UI
- Accepts user inputs (environment, version)
- Uses inputs inside workflow steps
- Simulates deployment process

## 📂 Files
- `.github/workflows/day-12.yml` → Workflow definition  
- `Day-12/README.md` → Documentation  

## ▶️ Key Steps
1. Define inputs using `workflow_dispatch`  
2. Accept user input at runtime  
3. Access inputs using GitHub context  
4. Execute steps based on inputs  

## 🎯 Purpose
To understand:
- Manual workflow triggers  
- Passing inputs to workflows  
- Dynamic pipeline execution  

---
✅ Day 12 completed
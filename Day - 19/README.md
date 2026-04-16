# 🚀 Day 19 - Failure Handling Workflow

## 📌 Overview
This workflow demonstrates how to handle failures and control execution flow in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-19.yml
└── Day-19/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Simulates a failing step
- Uses conditions to continue execution
- Demonstrates error handling strategies

## 📂 Files
- `.github/workflows/day-19.yml` → Workflow definition  
- `Day-19/README.md` → Documentation  

## ▶️ Key Steps
1. Execute a successful step  
2. Simulate failure using `exit 1`  
3. Use `if: always()` to run steps after failure  
4. Use `continue-on-error` to avoid stopping workflow  
5. Complete workflow execution  

## 🎯 Purpose
To understand:
- Failure handling in CI/CD  
- Conditional execution after failure  
- `continue-on-error` usage  

---
✅ Day 19 completed
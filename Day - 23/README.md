# 🚀 Day 23 - Concurrency Workflow

## 📌 Overview
This workflow demonstrates how to control concurrent executions in GitHub Actions to avoid conflicts.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-23.yml
└── Day-23/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Groups workflow runs using concurrency
- Cancels previous runs if a new one starts
- Simulates deployment process

## 📂 Files
- `.github/workflows/day-23.yml` → Workflow definition  
- `Day-23/README.md` → Documentation  

## ▶️ Key Steps
1. Define concurrency group  
2. Prevent parallel executions  
3. Cancel in-progress runs  
4. Execute controlled deployment  

## 🎯 Purpose
To understand:
- Concurrency control  
- Avoiding duplicate deployments  
- Managing workflow execution  

---
✅ Day 23 completed
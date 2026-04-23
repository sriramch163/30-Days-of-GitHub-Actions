# 🚀 Day 26 - Matrix with Environment Workflow

## 📌 Overview
This workflow demonstrates how to use matrix strategy with multiple environments in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-26.yml
└── Day-26/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Uses matrix strategy for multiple environments
- Runs deployment for dev, staging, and production
- Simulates multi-environment deployment

## 📂 Files
- `.github/workflows/day-26.yml` → Workflow definition  
- `Day-26/README.md` → Documentation  

## ▶️ Key Steps
1. Define matrix with environments  
2. Run job for each environment  
3. Assign environment dynamically  
4. Execute deployment steps  

## 🎯 Purpose
To understand:
- Matrix + environment combination  
- Multi-environment deployments  
- Parallel execution across environments  

---
✅ Day 26 completed
# 🚀 Day 22 - Multi Environment Workflow

## 📌 Overview
This workflow demonstrates how to manage multiple environments (dev, staging, production) based on branch conditions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-22.yml
└── Day-22/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `dev`, `staging`, and `main`
- Detects branch name
- Deploys to corresponding environment
- Simulates multi-stage deployment

## 📂 Files
- `.github/workflows/day-22.yml` → Workflow definition  
- `Day-22/README.md` → Documentation  

## ▶️ Key Steps
1. Detect branch  
2. Apply conditional logic  
3. Deploy to appropriate environment  
4. Execute environment-specific steps  

## 🎯 Purpose
To understand:
- Multi-environment deployments  
- Branch-based environment mapping  
- CI/CD environment flow  

---
✅ Day 22 completed
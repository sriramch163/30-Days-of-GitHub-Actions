# 🚀 Day 27 - Reusable Matrix Workflow

## 📌 Overview
This workflow demonstrates combining reusable workflows, matrix strategy, and secrets in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       ├── reusable-matrix.yml
│       └── day-27.yml
└── Day-27/
    └── README.md
```

## ⚙️ What it does
- Uses matrix strategy for multiple environments
- Calls reusable workflow for each environment
- Passes inputs and secrets securely
- Simulates deployment pipeline

## 📂 Files
- `.github/workflows/reusable-matrix.yml` → Reusable workflow  
- `.github/workflows/day-27.yml` → Caller workflow  
- `Day-27/README.md` → Documentation  

## ▶️ Key Steps
1. Define reusable workflow  
2. Use matrix to run multiple environments  
3. Call reusable workflow with inputs  
4. Pass secrets securely  

## 🎯 Purpose
To understand:
- Combining matrix and reusable workflows  
- Secure pipeline design  
- Advanced CI/CD structure  

---
✅ Day 27 completed
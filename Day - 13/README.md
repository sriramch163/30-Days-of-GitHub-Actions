# 🚀 Day 13 - Reusable Workflow

## 📌 Overview
This workflow demonstrates how to create and use reusable workflows in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       ├── reusable.yml
│       └── day-13.yml
└── Day-13/
    └── README.md
```

## ⚙️ What it does
- Defines a reusable workflow
- Calls the reusable workflow from another workflow
- Passes input values between workflows

## 📂 Files
- `.github/workflows/reusable.yml` → Reusable workflow  
- `.github/workflows/day-13.yml` → Caller workflow  
- `Day-13/README.md` → Documentation  

## ▶️ Key Steps
1. Define reusable workflow using `workflow_call`  
2. Accept inputs in reusable workflow  
3. Call reusable workflow using `uses`  
4. Pass values using `with`  

## 🎯 Purpose
To understand:
- Reusable workflows  
- Avoiding duplication in CI/CD  
- Modular pipeline design  

---
✅ Day 13 completed
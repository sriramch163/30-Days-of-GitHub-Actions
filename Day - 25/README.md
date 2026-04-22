# 🚀 Day 25 - Reusable Workflow with Secrets

## 📌 Overview
This workflow demonstrates how to use reusable workflows with inputs and secrets in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       ├── reusable-secure.yml
│       └── day-25.yml
└── Day-25/
    └── README.md
```

## ⚙️ What it does
- Defines a reusable workflow with inputs and secrets
- Calls the reusable workflow from another workflow
- Passes data securely using GitHub Secrets
- Simulates secure pipeline execution

## 📂 Files
- `.github/workflows/reusable-secure.yml` → Reusable workflow  
- `.github/workflows/day-25.yml` → Caller workflow  
- `Day-25/README.md` → Documentation  

## ▶️ Key Steps
1. Define reusable workflow with inputs and secrets  
2. Call reusable workflow using `uses`  
3. Pass inputs using `with`  
4. Pass secrets securely  

## 🎯 Purpose
To understand:
- Secure reusable workflows  
- Passing secrets between workflows  
- Modular CI/CD pipelines  

---
✅ Day 25 completed
# 🚀 Day 07 - Secrets and Environment Workflow

## 📌 Overview
This workflow demonstrates how to use environment variables and secrets in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-07.yml
└── Day-07/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Uses environment variables
- Accesses GitHub Secrets securely
- Simulates secure operations

## 📂 Files
- `.github/workflows/day-07.yml` → Workflow definition  
- `Day-07/README.md` → Documentation  

## ▶️ Key Steps
1. Define environment variables  
2. Access secrets using `${{ secrets.* }}`  
3. Use secrets in workflow steps  
4. Execute secure operations  

## 🎯 Purpose
To understand:
- Secrets management in GitHub Actions  
- Secure handling of sensitive data  
- Combining `env` and `secrets`  

---
✅ Day 07 completed
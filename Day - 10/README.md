# 🚀 Day 10 - Caching Dependencies Workflow

## 📌 Overview
This workflow demonstrates how to cache dependencies to improve performance in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-10.yml
└── Day-10/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Uses caching for dependencies
- Speeds up workflow execution
- Simulates install and build steps

## 📂 Files
- `.github/workflows/day-10.yml` → Workflow definition  
- `Day-10/README.md` → Documentation  

## ▶️ Key Steps
1. Checkout repository  
2. Cache dependencies using `actions/cache`  
3. Restore cache if available  
4. Simulate install and build  

## 🎯 Purpose
To understand:
- Caching in CI/CD  
- Reducing build time  
- Using `actions/cache`  

---
✅ Day 10 completed
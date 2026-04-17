# 🚀 Day 20 - Full CI Pipeline

## 📌 Overview
This workflow demonstrates a complete CI pipeline with build, test, and deploy stages in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-20.yml
└── Day-20/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Runs build, test, and deploy stages
- Shares artifacts between jobs
- Simulates a complete CI pipeline

## 📂 Files
- `.github/workflows/day-20.yml` → Workflow definition  
- `Day-20/README.md` → Documentation  

## ▶️ Key Steps
1. Build stage (install + build)  
2. Upload build artifacts  
3. Test stage (download + test)  
4. Deploy stage (final step)  

## 🎯 Purpose
To understand:
- Multi-stage pipelines  
- Job dependencies  
- Artifact sharing  
- CI workflow structure  

---
✅ Day 20 completed
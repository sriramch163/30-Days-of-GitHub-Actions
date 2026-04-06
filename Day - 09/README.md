# 🚀 Day 09 - Download Artifacts Workflow

## 📌 Overview
This workflow demonstrates how to share files between jobs using artifacts in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-09.yml
└── Day-09/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Creates a file in one job
- Uploads it as an artifact
- Downloads and uses it in another job

## 📂 Files
- `.github/workflows/day-09.yml` → Workflow definition  
- `Day-09/README.md` → Documentation  

## ▶️ Key Steps
1. Create file in first job  
2. Upload artifact  
3. Use `needs` to control job order  
4. Download artifact in second job  
5. Read file content  

## 🎯 Purpose
To understand:
- Sharing data between jobs  
- Artifact download usage  
- Multi-job pipeline flow  

---
✅ Day 09 completed
# 🚀 Day 08 - Artifacts Workflow

## 📌 Overview
This workflow demonstrates how to create and upload artifacts in GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-08.yml
└── Day-08/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Creates a sample file
- Uploads the file as an artifact
- Confirms upload

## 📂 Files
- `.github/workflows/day-08.yml` → Workflow definition  
- `Day-08/README.md` → Documentation  

## ▶️ Key Steps
1. Create a file inside workflow  
2. Upload file using artifact action  
3. Store artifact for later use  

## 🎯 Purpose
To understand:
- Artifacts in CI/CD  
- File sharing between jobs  
- Using `actions/upload-artifact`  

---
✅ Day 08 completed
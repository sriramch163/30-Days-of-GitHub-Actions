# 🚀 Day 04 - Multiple Jobs Workflow

## 📌 Overview
This workflow demonstrates how to run multiple jobs and control execution order using dependencies.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-04.yml
└── Day-04/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Runs multiple jobs in a workflow
- Uses dependency between jobs
- Executes jobs in sequence

## 📂 Files
- `.github/workflows/day-04.yml` → Workflow definition  
- `Day-04/README.md` → Documentation  

## ▶️ Key Steps
1. Define multiple jobs  
2. Execute first job independently  
3. Use `needs` to control execution order  
4. Run dependent job after completion  

## 🎯 Purpose
To understand:
- Multiple jobs in workflows
- Job dependencies (`needs`)
- Sequential execution of pipelines

---
✅ Day 04 completed
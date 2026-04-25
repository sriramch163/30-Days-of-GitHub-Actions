# 🚀 Day 28 - Dynamic Output Workflow

## 📌 Overview
This workflow demonstrates how to make dynamic decisions in a pipeline using outputs from previous jobs.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-28.yml
└── Day-28/
    └── README.md
```

## ⚙️ What it does
- Decides deployment environment dynamically
- Passes decision between jobs
- Executes deployment based on output
- Simulates dynamic pipeline behavior

## 📂 Files
- `.github/workflows/day-28.yml` → Workflow definition  
- `Day-28/README.md` → Documentation  

## ▶️ Key Steps
1. Decide environment in first job  
2. Set output using `$GITHUB_OUTPUT`  
3. Pass output to next job  
4. Use output in deployment  

## 🎯 Purpose
To understand:
- Dynamic pipelines  
- Job outputs for decision making  
- Flexible deployment strategies  

---
✅ Day 28 completed
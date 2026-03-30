# 🚀 Day 02 - Pull Request Workflow

## 📌 Overview
This workflow runs when a pull request is created or updated against the `main` branch.  
It demonstrates how CI pipelines can validate changes before merging.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-02.yml
└── Day-02/
    └── README.md
```

## ⚙️ What it does
- Triggers on pull request to `main`
- Runs on an Ubuntu runner
- Prints repository details
- Displays custom messages

## 📂 Files
- `.github/workflows/day-02.yml` → Workflow definition  
- `Day-02/README.md` → Documentation  

## ▶️ Key Steps
1. Detect pull request event  
2. Print trigger message  
3. Display repository info  
4. Print custom message  

## 🎯 Purpose
To understand:
- `pull_request` trigger
- CI validation before merge
- GitHub context variables

---
✅ Day 02 completed
# 🚀 Day 01 - Basic GitHub Actions Workflow

## 📌 Overview
This workflow runs automatically when code is pushed to the `main` branch.  
It demonstrates a simple CI pipeline with multiple steps.

## 📂 Directory Structure
```bash
.github/
└── workflows/
    └── day-01.yml

Day-01/
└── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Runs on an Ubuntu runner
- Executes basic shell commands
- Prints messages and system date

## 📂 Files
- `.github/workflows/main.yml` → Workflow definition  

## ▶️ Key Steps
1. Print a start message  
2. Display current date  
3. Print a custom message  

## 🎯 Purpose
To understand:
- Workflow triggers (`on`)
- Jobs and steps
- Basic pipeline execution

---
✅ Day 01 completed
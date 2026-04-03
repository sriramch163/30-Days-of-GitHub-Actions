# 🚀 Day 06 - Matrix Build Workflow

## 📌 Overview
This workflow demonstrates how to run the same job multiple times with different configurations using a matrix strategy.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-06.yml
└── Day-06/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Runs the same job with multiple configurations
- Simulates builds for different Node.js versions

## 📂 Files
- `.github/workflows/day-06.yml` → Workflow definition  
- `Day-06/README.md` → Documentation  

## ▶️ Key Steps
1. Define matrix strategy  
2. Run jobs for multiple versions  
3. Access matrix variables in steps  
4. Simulate build process  

## 🎯 Purpose
To understand:
- Matrix builds (`strategy.matrix`)
- Running parallel jobs
- Handling multiple environments in CI

---
✅ Day 06 completed
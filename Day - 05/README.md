# 🚀 Day 05 - Conditional Workflow

## 📌 Overview
This workflow demonstrates how to use conditional execution in GitHub Actions based on branch names.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-05.yml
└── Day-05/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main` and `dev` branches
- Executes steps conditionally based on branch
- Prints branch-specific messages
- Includes always-running steps

## 📂 Files
- `.github/workflows/day-05.yml` → Workflow definition  
- `Day-05/README.md` → Documentation  

## ▶️ Key Steps
1. Detect branch using GitHub context  
2. Apply conditional logic using `if`  
3. Run branch-specific steps  
4. Execute common steps  

## 🎯 Purpose
To understand:
- Conditional execution (`if`)
- Branch-based workflows
- GitHub context (`github.ref_name`)

---
✅ Day 05 completed
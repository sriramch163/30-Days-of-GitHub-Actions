# 🚀 Day 15 - Docker Build Workflow

## 📌 Overview
This workflow demonstrates how to build a Docker image using GitHub Actions.

## 📂 Directory Structure
```bash
30-Days-of-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── day-15.yml
└── Day-15/
    └── README.md
```

## ⚙️ What it does
- Triggers on push to `main`
- Creates a simple Dockerfile
- Builds a Docker image
- Lists available Docker images

## 📂 Files
- `.github/workflows/day-15.yml` → Workflow definition  
- `Day-15/README.md` → Documentation  

## ▶️ Key Steps
1. Checkout repository  
2. Create Dockerfile dynamically  
3. Build Docker image  
4. Verify image creation  

## 🎯 Purpose
To understand:
- Docker integration in CI/CD  
- Image building in pipelines  
- Basic container workflow  

---
✅ Day 15 completed
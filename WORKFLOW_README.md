# ⚙️ GitHub Action: Maven Build & SonarQube (PR Only)

This README describes the **GitHub Actions workflow** that runs on pull requests to build the project with Maven and decorate the PR with build and SonarQube analysis results.

---

## 📌 Workflow Overview

- **Trigger**: Pull Requests targeting the `main` branch  
- **Build Tool**: Maven with JDK 17 (`temurin`)  
- **PR Decoration**:
  - ✅ Build status (success or failure)  
  - 🛡️ SonarQube Quality Gate (dummy for now)  
  - 🔎 SonarQube issue summary (dummy for now)  

---

## 📂 File Location

The workflow file is located at:

```text
.github/workflows/maven-pr-sonar.yml

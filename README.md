# DevSecOps-Project


# 🛡️ DevSecOps Project — CI/CD Security Pipeline

This project demonstrates a **DevSecOps CI/CD pipeline** built using **Jenkins**, integrating multiple security and quality tools such as **SonarQube**, **OWASP Dependency Check**, and **Trivy** for automated scanning and deployment using **Docker Compose**.

---

## 🚀 Overview

The Jenkins pipeline automates the following stages:
1. **Code Checkout** — Clones the source code from GitHub.
2. **Code Quality Analysis** — Runs static code analysis using SonarQube.
3. **Dependency Vulnerability Scan** — Scans project dependencies using OWASP Dependency Check.
4. **Quality Gate Validation** — Verifies SonarQube quality gate status.
5. **Container Image & Filesystem Scan** — Scans filesystem vulnerabilities using Trivy.
6. **Application Deployment** — Deploys services using Docker Compose.

---

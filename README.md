# 🚀 CI Pipeline Demo (GitHub Actions)

This project demonstrates a **complete CI workflow** using **GitHub Actions**.

### 🧩 Includes:
- ✅ Code Checkout
- ⚡ Dependency Caching
- 🧪 Unit Testing
- 🏗️ Build Step
- 📦 Artifact Upload
- 🐳 Docker Build & Push
- 🔍 Trivy Security Scan
- 📊 SonarQube Code Quality Analysis

### ⚙️ Secrets Required
| Secret Name | Purpose |
|--------------|----------|
| `DOCKERHUB_USERNAME` | Login to DockerHub |
| `DOCKERHUB_PASSWORD` | Push Docker image |
| `SONAR_TOKEN` | Authenticate with SonarQube |
| `SONAR_HOST_URL` | SonarQube server URL |

---

🧠 **Learning Goal:**  
Understand real-world CI pipelines used in production — caching, artifacts, testing, scanning, and Docker deployment.

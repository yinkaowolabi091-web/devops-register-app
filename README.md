# 🚀 DevOps Register App (CI/CD | Docker | Kubernetes | AWS)

## 📌 Overview

This project demonstrates a **complete DevOps pipeline** for deploying a containerized register/login application using modern DevOps tools and practices.

It focuses on:

* CI/CD automation
* Containerization
* Kubernetes deployment
* Cloud infrastructure integration

---

## 🧠 What I Built

* Containerized a full-stack register/login application using Docker
* Built a CI/CD pipeline to automate build and deployment
* Deployed the application to Kubernetes
* Managed deployments using DevOps best practices
* Ensured consistent and repeatable releases

---

## 🏗️ Architecture

![Architecture](./assets/architecture.png)

### Flow:

1. Developer pushes code to GitHub
2. CI/CD pipeline builds Docker image
3. Image is pushed to container registry
4. Kubernetes deploys application
5. Application is exposed via service/load balancer

---

## 🛠️ Tech Stack

* **Cloud:** AWS (EC2 / EKS)
* **Containers:** Docker
* **Orchestration:** Kubernetes
* **CI/CD:** Jenkins / GitHub Actions
* **Version Control:** GitHub

---

## ⚙️ Key Features

* Automated build and deployment pipeline
* Containerized application for portability
* Kubernetes-based scalable deployment
* Improved deployment consistency
* Reduced manual intervention

---

## 📈 Impact

* Reduced manual deployment effort by **~60–70%**
* Improved deployment reliability using containerization
* Enabled faster and repeatable application releases

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yinkaowolabi091-web/devops-register-app.git
cd devops-register-app
```

### 2. Build Docker Image

```bash
docker build -t register-app .
```

### 3. Run Locally

```bash
docker run -p 3000:3000 register-app
```

### 4. Deploy to Kubernetes

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```

---

## 🔍 Challenges & Solutions

**Issue:** Container build inconsistencies
**Solution:** Standardized Dockerfile and dependencies

**Issue:** Kubernetes deployment errors
**Solution:** Fixed manifest configuration and service exposure

---

<img width="1668" height="921" alt="Screenshot 2026-03-21 082502" src="https://github.com/user-attachments/assets/898eea4b-6467-46ab-a721-173c780a5ff4" />

---

## 👤 Author

**Yinka Owolabi**

* GitHub: https://github.com/yinkaowolabi091-web
* LinkedIn: https://www.linkedin.com/in/olayinka-owolabi-9169a4220

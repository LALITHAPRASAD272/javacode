# 🚀 DevSecOps Pipeline Project (CloudShield Hackathon 2026)

## 🏆 Achievement
Secured **3rd Place** in CloudShield DevSecOps Hackathon 2026

## 📌 Overview
This project demonstrates a complete end-to-end DevSecOps pipeline using Azure, Terraform, Kubernetes, and modern security tools.

## 🏗️ Architecture

Developer → CI/CD Pipeline → Docker → ACR → AKS → Monitoring

## ⚙️ Tech Stack

- Azure (VM, ACR, AKS)
- Terraform (Infrastructure as Code)
- Azure DevOps (CI/CD)
- Docker (Containerization)
- Kubernetes (AKS)
- SonarQube (Code Analysis)
- Trivy (Security Scanning)
- Prometheus & Grafana (Monitoring)

## 🔄 Pipeline Workflow

1. Build Java Application (Maven)
2. Static Code Analysis (SonarQube)
3. Docker Image Build
4. Security Scan (Trivy)
5. Push Image to Azure Container Registry
6. Deploy to Azure Kubernetes Service
7. Monitor using Prometheus & Grafana

## 📂 Project Structure

```
board/
 ├── src/
 ├── Dockerfile
 ├── k8s/
 │    ├── deployment.yaml
 │    └── service.yaml
 └── azure-pipelines.yml
```

## 📊 Monitoring

- Prometheus for metrics collection
- Grafana dashboards for visualization

## 🚀 Key Features

- Infrastructure automation using Terraform
- Secure CI/CD pipeline implementation
- Container vulnerability scanning
- Kubernetes-based deployment
- Real-time monitoring and observability

## 📸 Screenshots

(Add pipeline, Grafana, and deployment screenshots here)

## 👨‍💻 Author

Team Cloud Guardians  
Team Lead: Lalitha Prasad Palnati

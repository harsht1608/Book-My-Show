
# 🎬 Book-My-Show Clone – CI/CD DevOps Project

A full-scale DevOps project that simulates the **deployment of a BookMyShow clone** using Docker, Jenkins, Kubernetes (EKS), and AWS services — integrated with security scans and real-time monitoring.

## 🔥 Why I Built This

To gain hands-on experience with real-world DevOps workflows — from code analysis to containerized deployment on Kubernetes with end-to-end automation. This project consolidates my learnings across CI/CD, Infrastructure-as-Code, Security, and Observability.

---

## 🧱 Tech Stack

| Category         | Tools & Services                                 |
|------------------|--------------------------------------------------|
| CI/CD Pipeline   | Jenkins, Docker, GitHub                          |
| Containerization | Docker, DockerHub                                |
| Orchestration    | Kubernetes (EKS), kubectl, eksctl                |
| Security         | SonarQube, Trivy, OWASP Dependency Check         |
| Monitoring       | Prometheus, Grafana, Node Exporter               |
| Cloud            | AWS (EC2, IAM, EKS, CloudFormation)              |
| Alerts           | Gmail SMTP-based Email Notifications             |

---

## 🏗️ Architecture

📌 [View Architecture Diagram](https://app.eraser.io/workspace/1c4GoEhL04FHeGJzi90b?elements=C2jhFLppgg4qS_OSYaJjXA)
- ![image](https://github.com/user-attachments/assets/4e8c145f-c3a8-4483-aa3d-0bba6e4d46e7)


---

## 🚀 Key Features

- Jenkins-based **CI/CD pipeline** with GitHub integration  
- Static & dynamic code analysis via **SonarQube + Trivy**  
- Dockerized deployment with automated **image build & push**  
- **Kubernetes deployment** via `deployment.yml` and `service.yml`  
- Real-time monitoring using **Prometheus + Grafana**  
- **Email notifications** for every pipeline outcome  
- Infrastructure setup using **AWS CLI, IAM Roles, and eksctl**

---

## ⚙️ Pipeline Stages

### Part I: Docker Deployment
- Git clone from GitHub
- Code quality scan (SonarQube)
- Trivy filesystem scan
- Docker image build and push to DockerHub
- Deployment on EC2 using Docker
- ![Screenshot (354)](https://github.com/user-attachments/assets/d9736e99-8030-4d40-bfb3-451e90361c9e)

### Part II: Kubernetes + Monitoring

- Kubernetes manifests (`deployment.yml`, `service.yml`)
- EKS deployment via Jenkins pipeline
- Jenkins user permission setup
- Monitoring with:
  - Prometheus (target scraping from Jenkins & Node Exporter)
  - Grafana dashboards (Node Exporter + Jenkins performance)
  - ![image](https://github.com/user-attachments/assets/5eaf930a-f1a1-4fb6-a5dd-cbac3ddf05be)


---

## 📁 Project Structure

├── Jenkinsfile1 # CI/CD pipeline (Docker-based)
├── Jenkinsfile2 # CI/CD pipeline (K8s-based)
├── deployment.yml # K8s deployment file
├── service.yml # K8s service file
├── BMS-Document.txt # Detailed implementation steps

---

## 🛠️ Setup & Configuration

> All setup scripts for Jenkins, Docker, Trivy, and SonarQube installation are included in the documentation file.

### ✅ Prerequisites
- Ubuntu 24.04 (for CI server)
- Ubuntu 22.04 (for monitoring server)
- Open necessary ports in AWS Security Groups (22, 80, 443, 8080, 3000, 6443, 9000, 9090, 9100)
- ![image](https://github.com/user-attachments/assets/e1be9500-3c42-4bbc-9978-5d1e52e4b68a)


---

## 📊 Monitoring Dashboards

- **Grafana Dashboards Added:**
  - Node Exporter Full: [Grafana #1860](https://grafana.com/grafana/dashboards/1860)
  - ![Screenshot (348)](https://github.com/user-attachments/assets/a3bd8e8d-f706-4561-81a5-2f3642c9fd9b)
    
  - Jenkins Health Overview: [Grafana #9964](https://grafana.com/grafana/dashboards/9964)
  - ![Screenshot (349)](https://github.com/user-attachments/assets/018b0ed1-067d-4c13-a798-da61a79151fb)

---

## 📬 Email Notification Integration

- Configured via Gmail SMTP using Jenkins credentials  
- Notifications triggered on **build success/failure** with logs attached
- ![image](https://github.com/user-attachments/assets/70a79eae-7a2a-4a9b-9b5b-08fcb9645c26)


---

## 🧹 Cleanup

All AWS resources (EKS, EC2, IAM roles) are deleted post-deployment to optimize cost and resource usage.

---

## 🙌 Acknowledgements

Thanks to open-source contributors and AWS Free Tier for enabling this hands-on DevOps learning experience.

---

## 📎 Links

- 🔗 [GitHub Repo]([https://github.com/K/Book-My-Show](https://github.com/harsht1608/Book-My-Show/)
- 📖 [Blog Writeup on Medium](https://medium.com/@harsht1326)

---

> **Author:** Harsh Nitin  
> 📧 harsht1326@gmail.com 
> 🌐 [LinkedIn](https://www.linkedin.com/in/harshtembhurnikar/)

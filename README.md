# 🎬 Book My Show Clone - Movie Ticket Booking Platform

<div align="center">
  <img src="bookmyshow-app/public/Bookmyshow-logo.png" alt="Book My Show Logo" width="200"/>
  <p><strong>A modern movie ticket booking platform with CI/CD implementation</strong></p>
</div>

## 🌟 Features

- 🎫 Real-time movie ticket booking system
- 🍿 Food & beverages ordering
- 🎯 Interactive seat selection
- 👥 User authentication & profile management
- 💳 Secure payment integration
- 📱 Responsive design for all devices
- 📖 Booking history tracking
- 🎥 Detailed movie information and ratings

## 🛠️ Technology Stack

### Frontend
- **Framework:** React.js (v17)
- **State Management:** Redux with Thunk
- **Routing:** React Router v5
- **UI Components:** Material-UI, Ant Design
- **Styling:** CSS Modules, Styled Components
- **Carousel:** React Multi Carousel, React Elastic Carousel

### DevOps & Deployment
- **CI/CD:** Jenkins Pipeline
- **Containerization:** Docker
- **Container Orchestration:** Kubernetes (EKS)
- **Code Quality:** SonarQube
- **Security Scanning:** 
  - OWASP Dependency Check
  - Trivy File System Scan
- **Cloud Platform:** AWS EKS

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- Docker
- npm or yarn

### Local Development Setup

1. **Clone the repository**
```bash
git clone https://github.com/harsht1608/Book-My-Show.git
cd Book-My-Show/bookmyshow-app

# Install dependencies
npm install

# Start development server
npm start

# 🐳 Docker Deployment
# Build the image
docker build -t hash/bms:latest .

# Run container
docker run -d -p 3500:3500 hash/bms:latest

# ☸️ Kubernetes Deployment
# Apply Kubernetes manifests
kubectl apply -f deployment.yml
kubectl apply -f service.yml

🔄 CI/CD Pipeline
Our project implements a robust CI/CD pipeline using Jenkins with the following stages:

Workspace Cleanup
Source Code Checkout
SonarQube Analysis
Quality Gate Check
Dependency Installation
Security Scanning
OWASP Dependency Check
Trivy FS Scan
Docker Build & Push
Deployment
Docker Container (Development)
AWS EKS (Production)

📸 Application Screenshots
Home Page

Movie Details









# 🎬 Book My Show Clone - Modern Movie Booking Platform

<div align="center">
  <img src="public/Bookmyshow-logo.png" alt="Book My Show Logo" width="200"/>
  <br/>
  <p>A full-stack movie booking platform with complete DevOps implementation</p>
  
  [![SonarQube](https://img.shields.io/badge/SonarQube-Integrated-success)](/)
  [![Docker](https://img.shields.io/badge/Docker-Containerized-blue)](/)
  [![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestrated-blue)](/)
  [![Jenkins](https://img.shields.io/badge/Jenkins-Automated-success)](/)
  [![Monitoring](https://img.shields.io/badge/Monitoring-Prometheus%20%26%20Grafana-orange)](/)
</div>

## 🌟 Features

- 🎫 Real-time movie ticket booking
- 🍿 Food & beverage ordering system
- 🎯 Interactive seat selection
- 💳 Secure payment integration
- 📱 Responsive design
- 👥 User authentication & profiles
- 📊 Booking history tracking
- 🔍 Advanced movie search & filters

## 🛠️ Technology Stack

### Frontend
- **Framework:** React.js 17
- **UI Components:** Material-UI, Ant Design
- **State Management:** Redux with Thunk
- **Routing:** React Router v5
- **Styling:** CSS Modules, Styled Components

### DevOps & Infrastructure
- **CI/CD:** Jenkins Pipeline
- **Containerization:** Docker
- **Container Orchestration:** AWS EKS (Kubernetes)
- **Code Quality:** SonarQube
- **Security Scanning:**
  - OWASP Dependency Check
  - Trivy File System Scan
- **Monitoring Stack:**
  - Prometheus
  - Grafana
  - Node Exporter
- **Cloud Platform:** AWS

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- Docker
- Kubernetes (for production deployment)

### Local Development
```bash
# Clone repository
git clone https://github.com/harsht1608/Book-My-Show.git

# Install dependencies
cd bookmyshow-app
npm install

# Start development server
npm start

Access the application at http://localhost:3500

🐳 Docker Deployment

# Build image
docker build -t hash/bms:latest .

# Run container
docker run -d -p 3000:3000 hash/bms:latest

☸️ Kubernetes Deployment

# Apply configurations
kubectl apply -f deployment.yml
kubectl apply -f service.yml

🔄 CI/CD Pipeline
Our Jenkins pipeline implements the following stages:

Workspace Cleanup
Source Code Checkout
SonarQube Analysis
Quality Gate Check
Dependencies Installation
Security Scans
OWASP Dependency Check
Trivy FS Scan
Docker Build & Push
Deployment
Docker Container (Development)
AWS EKS (Production)
📊 Monitoring & Observability
Tools Configuration
Prometheus for metrics collection
Grafana for visualization
Node Exporter for system metrics
Custom Jenkins metrics integration
Dashboards
Node Exporter Full (ID: 1860)
Jenkins Performance Overview (ID: 9964)

🔐 Security Features
SonarQube code quality gates
OWASP dependency scanning
Trivy container scanning
AWS IAM integration
Secure environment configuration
📈 Performance
Optimized Docker builds
Kubernetes-based scaling
Load balanced service deployment
Content delivery optimization
🤝 Contributing
Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit changes (git commit -m 'Add AmazingFeature')
Push to branch (git push origin feature/AmazingFeature)
Open a Pull Request

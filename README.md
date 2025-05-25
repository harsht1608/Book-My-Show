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
docker build -t kastrov/bms:latest .

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

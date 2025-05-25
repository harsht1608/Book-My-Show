
---

## 🛠️ Setup & Configuration

> All setup scripts for Jenkins, Docker, Trivy, and SonarQube installation are included in the documentation file.

### ✅ Prerequisites
- Ubuntu 24.04 (for CI server)
- Ubuntu 22.04 (for monitoring server)
- Open necessary ports in AWS Security Groups (22, 80, 443, 8080, 3000, 6443, 9000, 9090, 9100)

---

## 📊 Monitoring Dashboards

- **Grafana Dashboards Added:**
  - Node Exporter Full: [Grafana #1860](https://grafana.com/grafana/dashboards/1860)
  - Jenkins Health Overview: [Grafana #9964](https://grafana.com/grafana/dashboards/9964)

---

## 📬 Email Notification Integration

- Configured via Gmail SMTP using Jenkins credentials  
- Notifications triggered on **build success/failure** with logs attached

---

## 🧹 Cleanup

All AWS resources (EKS, EC2, IAM roles) are deleted post-deployment to optimize cost and resource usage.

---

## 🙌 Acknowledgements

Thanks to open-source contributors and AWS Free Tier for enabling this hands-on DevOps learning experience.

---

## 📎 Links

- 🔗 [GitHub Repo](https://github.com/KastroVKiran/Book-My-Show)  
- 📖 [Blog Writeup on LinkedIn](<insert-your-link-here>)  
- 📺 [Demo (Optional)](https://your-demo-link.com)

---

## 📢 Stay Tuned for Part 2!

Monitoring, auto-scaling, and alerting modules coming soon…

---

> **Author:** Harsh Tembhurnikar  
> 📧 harsh.tembhurnikar@example.com  
> 🌐 [LinkedIn](https://www.linkedin.com/in/your-profile/)

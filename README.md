# Prometheus-Grafana-Monitoring-AWS
# 🚀 AWS Monitoring with Prometheus & Grafana

This project demonstrates a **production-style monitoring architecture** using **Prometheus, Grafana, and Docker** on **AWS EC2**.

---

## 🧱 Architecture

- **EC2-1 (Application Server)**
  - Dockerized frontend, backend, proxy, database
  - cAdvisor (container metrics)
  - node_exporter (host metrics)

- **EC2-2 (Monitoring Server)**
  - Prometheus
  - Grafana
  - Blackbox Exporter (website monitoring)

---

## 🛠 Tech Stack

- AWS EC2
- Docker
- Prometheus
- Grafana
- cAdvisor
- node_exporter
- Blackbox Exporter
- Linux (Ubuntu)

---

## 📊 Monitoring Capabilities

- Docker container CPU & memory usage
- EC2 system metrics
- Website uptime & response time
- Email alerts

---

## ⚠️ Note

Docker Compose is **not used for the application in production**.  
Each service uses its own Dockerfile and runs independently.

---

## 📸 Screenshots

See the `screenshots/` folder.

---

## 👨‍💻 Author

Nikil Dovin


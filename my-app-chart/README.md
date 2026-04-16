# 🚀 DevOps Capstone Project – GitOps Kubernetes Platform

## 📌 Project Overview

This project demonstrates a complete **DevOps pipeline** using modern tools and practices.
It includes containerization, Kubernetes deployment, GitOps automation, monitoring, and auto-scaling.

---

## 🛠️ Tech Stack

* **Docker** – Containerization
* **Kubernetes (k3s)** – Container orchestration
* **Helm** – Package management
* **ArgoCD** – GitOps continuous deployment
* **Prometheus** – Monitoring & metrics collection
* **Grafana** – Visualization dashboards
* **HPA** – Auto scaling based on CPU usage
* **AWS EC2** – Cloud infrastructure

---

## 🏗️ Architecture

GitHub → ArgoCD → Kubernetes (k3s) → Application
↓
Prometheus → Grafana

---

## ⚙️ Features

* ✅ Containerized application using Docker
* ✅ Kubernetes deployment using Helm charts
* ✅ GitOps-based deployment using ArgoCD
* ✅ Automated synchronization from GitHub to cluster
* ✅ Monitoring using Prometheus & Grafana
* ✅ Real-time metrics visualization
* ✅ Auto scaling using HPA based on CPU utilization

---

## 🚀 Deployment Steps

1. Build and push Docker image
2. Create Helm chart for application
3. Push Helm chart to GitHub
4. Configure ArgoCD to track repository
5. Deploy application via GitOps
6. Install Prometheus & Grafana
7. Configure dashboards
8. Implement HPA for auto scaling

---

## 📊 Monitoring

* Prometheus collects cluster and node metrics
* Grafana visualizes:

  * CPU usage
  * Memory usage
  * Pod health
  * Node performance

---

## ⚡ Auto Scaling

* Configured HPA with:

  * Min Pods: 1
  * Max Pods: 5
  * Target CPU: 50%
* Pods automatically scale based on load

---

## 🧠 Key Learnings

* GitOps workflow using ArgoCD
* Kubernetes resource management
* Debugging real-world issues (disk pressure, metrics, scaling)
* Monitoring and observability setup
* Auto-scaling in Kubernetes

---

## 📌 Future Improvements

* Use EKS instead of k3s
* Implement CI/CD pipeline (Jenkins/GitHub Actions)
* Add Ingress with domain and SSL
* Separate GitOps and application repositories

---

## 👨‍💻 Author

**Mustafa Balasinorwala**

---

## ⭐ Conclusion

This project demonstrates a real-world DevOps workflow with automation, monitoring, and scalability, aligning with industry best practices.


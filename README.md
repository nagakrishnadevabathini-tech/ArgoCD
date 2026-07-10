# 🚀 Argo CD GitOps Deployment on Kubernetes

## 📌 Project Overview

This project demonstrates the deployment of a **Facebook application** on a **Kubernetes cluster** using **Argo CD** by following the **GitOps** methodology.

The goal of this project was to understand how Argo CD automates application deployment, continuously synchronizes the Kubernetes cluster with a Git repository, and provides visibility into application health and resource status.

---

## 🛠️ Technologies Used

* Kubernetes
* Argo CD
* Docker
* Git
* GitHub
* Linux

---

## 📂 Project Workflow

1. Containerized the application.
2. Stored Kubernetes manifests in a GitHub repository.
3. Installed and configured Argo CD.
4. Created an Argo CD Application.
5. Connected Argo CD to the Git repository.
6. Synced the application with the Kubernetes cluster.
7. Verified application health and synchronization.
8. Monitored Deployments, ReplicaSets, Pods, and Services through the Argo CD Dashboard.

---

## 📁 Repository Structure

```text
.
├── argocd/
│   └── application.yaml
├── manifests/
│   ├── deployment.yaml
│   ├── service.yaml
│   └── namespace.yaml
├── screenshots/
│   ├── 01-dashboard.png
│   ├── 02-application-details.png
│   ├── 03-sync-status.png
│   └── ...
└── README.md
```

---

## 🚀 Key Features

* GitOps-based deployment
* Automated synchronization
* Continuous Deployment (CD)
* Application health monitoring
* Kubernetes resource visualization
* Declarative infrastructure management

---

## 📷 Project Screenshots

### Argo CD Dashboard
<img width="1920" height="1080" alt="Screenshot (101)" src="https://github.com/user-attachments/assets/944489fd-34e0-4b80-ab2f-0c72cfc4cb33" />



### Application Details

<img width="1920" height="1080" alt="Screenshot (102)" src="https://github.com/user-attachments/assets/fa71f987-a817-427a-a79f-d874faf38c2f" />


### Resource Tree

<img width="1920" height="1080" alt="Screenshot (103)" src="https://github.com/user-attachments/assets/d738e8c4-fd03-4b42-b489-a8a0afd179e4" />


### Sync & Health Status
<img width="1920" height="1080" alt="Screenshot (100)" src="https://github.com/user-attachments/assets/f00faacc-846b-40db-9a85-ae93e10099fb" />



---

## 📚 What I Learned

* GitOps workflow using Argo CD
* Creating and managing Argo CD Applications
* Continuous deployment in Kubernetes
* Kubernetes Deployments, ReplicaSets, Pods, and Services
* Monitoring application health
* Synchronizing Kubernetes resources with Git
* Troubleshooting deployment issues using Argo CD

---

## 🎯 Future Improvements

* Enable automatic synchronization
* Configure self-healing
* Implement automated rollback
* Deploy using Helm Charts
* Integrate Argo CD with CI pipelines
* Add monitoring with Prometheus and Grafana

---

## 👨‍💻 Author

**Nagakrishna Devabathini**

If you found this project helpful, feel free to ⭐ the repository.

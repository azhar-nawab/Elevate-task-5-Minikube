# Elevate-task-5-Minikube
minikube-nginx-deployment

# Minikube Kubernetes Deployment on EC2

This project demonstrates how to set up a local Kubernetes cluster using **Minikube** on an **AWS EC2 instance**, and deploy a sample NGINX application with Kubernetes **Deployments** and **Services**.

---

## 🚀 Objective

- Deploy and manage applications in Kubernetes.
- Use Minikube, kubectl, and Docker on an EC2 instance.
- Validate pods and services.
- Scale deployments and expose services.
- Push deliverables (YAML files and outputs) to GitHub.

---

## 🛠️ Tools & Technologies

- **Minikube**
- **Kubernetes**
- **kubectl**
- **Docker**
- **AWS EC2 (Ubuntu 22.04/24.04)**

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `deployment.yaml` | Kubernetes Deployment for NGINX |
| `service.yaml`    | Kubernetes NodePort Service to expose the app |
| `pods_output.txt` | Output of `kubectl get pods` |
| `svc_output.txt`  | Output of `kubectl get svc` |

---

## 📦 Deployment Steps

### 1. Start Minikube

```bash
minikube start --driver=docker

# 🍕 Cloud Pizza Factory - Docker & Kubernetes Project

## Overview

Cloud Pizza Factory is a simple Flask-based web application designed to demonstrate the fundamentals of containerization and container orchestration using Docker and Kubernetes.

The project showcases how an application can be packaged into a Docker container, deployed on a Kubernetes cluster, automatically recover from failures, and scale based on demand.

---

## Architecture

```text
Python Flask Application
          ↓
      Docker Image
          ↓
    Docker Container
          ↓
 Kubernetes Deployment
          ↓
      Kubernetes Pods
          ↓
  Scaling & Self-Healing
```

---

## Technologies Used

* Python
* Flask
* Docker
* Kubernetes
* kubectl

---

## Features

* Containerized Flask application using Docker
* Docker image creation and deployment
* Kubernetes Deployment configuration
* Multiple Pod replicas
* Self-healing capability
* Horizontal scaling
* Simplified cloud-native application deployment

---

## Project Workflow

### 1. Build Docker Image

```bash
docker build -t cloud-pizza .
```

### 2. Run Docker Container

```bash
docker run -p 5000:5000 cloud-pizza
```

### 3. Deploy Application to Kubernetes

```bash
kubectl apply -f deployment.yaml
```

### 4. Verify Running Pods

```bash
kubectl get pods
```

### 5. Scale Application

```bash
kubectl scale deployment cloud-pizza --replicas=5
```

---

## Screenshots

### Docker Image Build

<img width="1516" height="641" alt="docker-build-image" src="https://github.com/user-attachments/assets/1ff8a9c4-61fa-4341-b129-e52b40848e8b" />


---

### Running Docker Container

<img width="1327" height="733" alt="docker-container" src="https://github.com/user-attachments/assets/2abe062a-3a46-434d-9ac1-e24e157584c4" />


---

### Application Running in Browser

<img width="1898" height="786" alt="Screenshot 2026-06-17 233527" src="https://github.com/user-attachments/assets/cfea8e58-75a2-4950-a957-eacfcf24bd45" />


---

### Kubernetes Pods

<img width="842" height="325" alt="pods-running" src="https://github.com/user-attachments/assets/fee811d6-781d-48f2-bc6b-c127a5fc9a67" />


---

### Scaling Pods

<img width="981" height="327" alt="scaling-demo" src="https://github.com/user-attachments/assets/672ef828-6199-4481-bb07-9640cb330435" />

---

### Self-Healing Demonstration

<img width="907" height="372" alt="self-healing" src="https://github.com/user-attachments/assets/fa4783bb-1408-444e-a288-a9b2bd31bfd2" />


---

### Cluster-Nodes
<img width="757" height="83" alt="cluster-nodes" src="https://github.com/user-attachments/assets/310a22e8-9462-48f6-86eb-ac8f2304dcb2" />

### Cluster-Resources
<img width="712" height="512" alt="cluster-resources" src="https://github.com/user-attachments/assets/ac2c87f1-7012-45a3-9711-589fdab05350" />



### Deployment Status

<img width="1280" height="88" alt="deployment-status" src="https://github.com/user-attachments/assets/c618c815-5fb6-441f-be6c-ddbfce59e395" />


---

## Learning Outcomes

Through this project, I learned:

* Docker Images and Containers
* Containerization Best Practices
* Kubernetes Pods and Deployments
* Replica Management
* Self-Healing Mechanisms
* Application Scaling
* Basic DevOps Concepts

---

## Conclusion

Cloud Pizza Factory provides a practical introduction to modern DevOps practices by demonstrating how Docker and Kubernetes work together to deploy, manage, and scale applications efficiently.


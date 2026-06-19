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
Technologies Used
Python
Flask
Docker
Kubernetes
kubectl
Features
Containerized Flask application using Docker
Docker image creation and deployment
Kubernetes Deployment configuration
Multiple Pod replicas
Self-healing capability
Horizontal scaling
Simplified cloud-native application deployment
Project Workflow
1. Build Docker Image
docker build -t cloud-pizza .
2. Run Docker Container
docker run -p 5000:5000 cloud-pizza
3. Deploy Application to Kubernetes
kubectl apply -f deployment.yaml
4. Verify Running Pods
kubectl get pods
5. Scale Application
kubectl scale deployment cloud-pizza --replicas=5
Screenshots
Docker Image Build
<img width="1516" height="641" alt="docker-build-image" src="https://github.com/user-attachments/assets/a3886921-966a-421d-8544-d1254980750a" />




Running Docker Container

<img width="1327" height="733" alt="docker-container" src="https://github.com/user-attachments/assets/5aa9157e-34f3-4202-b75a-a2c7bc0c5a65" />


Application Running in Browser

<img width="1898" height="786" alt="Screenshot 2026-06-17 233527" src="https://github.com/user-attachments/assets/fc6615da-9d98-4599-84f0-900eee16d599" />


Kubernetes Pods
<img width="842" height="325" alt="pods-running" src="https://github.com/user-attachments/assets/bdf460a7-4d12-4eba-8a07-7419737411d3" />



Scaling Pods

<img width="981" height="327" alt="scaling-demo" src="https://github.com/user-attachments/assets/af7779ec-63c2-4e44-958f-899ecceba208" />


Self-Healing Demonstration

<img width="907" height="372" alt="self-healing" src="https://github.com/user-attachments/assets/9ebf5ed2-d1f7-4106-bf92-c4199e10c85a" />

Deployment Status
<img width="1280" height="88" alt="deployment-status" src="https://github.com/user-attachments/assets/b8dd6ff7-660c-40d4-bef7-431827710fed" />


Learning Outcomes

Through this project, I learned:

Docker Images and Containers
Containerization Best Practices
Kubernetes Pods and Deployments
Replica Management
Self-Healing Mechanisms
Application Scaling
Basic DevOps Concepts
Conclusion

Cloud Pizza Factory provides a practical introduction to modern DevOps practices by demonstrating how Docker and Kubernetes work together to deploy, manage, and scale applications efficiently.

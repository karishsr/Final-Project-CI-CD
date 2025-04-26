# Final-Project-CI-CD

 Overview
This project sets up a complete CI/CD pipeline that:

Builds a Docker image for a Flask app.

Pushes it to Docker Hub using GitHub Actions.

Deploys it locally on Minikube (Kubernetes cluster).

Tools Used
Docker & Docker Hub

GitHub Actions

Kubernetes (Minikube)

Python Flask

 Steps
Dockerfile created for app containerization.

GitHub Actions Workflow configured to build, test, and push to Docker Hub.

Kubernetes Deployment (deployment.yml) and Service (NodePort) created.

App deployed and accessed via minikube service command.

🔗 Important Links
Docker Hub Image: karishrat123/cicd-project

GitHub Repo: https://github.com/karishsr/Final-Project-CI-CD.git

 Deliverables
GitHub Actions success screenshot

kubectl get pods and kubectl get services screenshots

Browser screenshot of the running app

# Kubernetes Flask DevOps Project

This project demonstrates deploying a containerized Flask web application using Docker and Kubernetes with Minikube.

## Tools Used
Docker
Kubernetes
Minikube
Ubuntu
GitHub

## Project Workflow

Flask App → Docker Image → Kubernetes Deployment → Kubernetes Service → Browser

## Commands Used

docker build -t flask-k8s-app .

kubectl apply -f kubernetes/deployment.yaml

kubectl apply -f kubernetes/service.yaml

kubectl get pods

kubectl get svc

minikube service flask-service

## Output

Hello from Kubernetes DevOps Project!

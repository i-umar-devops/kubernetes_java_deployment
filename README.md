# Docker + Java + Kubernetes Project

This repository contains a small Java microservices application (shopfront, productcatalogue, stockmanager) that is containerized with Docker and deployed to Kubernetes (Minikube locally and AWS EKS in the cloud). It demonstrates my hands-on experience with building containers, writing Kubernetes manifests, and running services in a cloud-native way.

## Tech stack

- Java + Maven
- Docker
- Kubernetes (Minikube & AWS EKS)
- kubectl, eksctl
- AWS (EKS, EC2, IAM)

## What this project does

- Builds three Java microservices with Maven.
- Packages each service as a Docker image and pushes it to Docker Hub.
- Deploys the services to Kubernetes using Deployment and Service YAML files.
- Runs locally on Minikube or on an EKS cluster created via eksctl.



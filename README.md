# Amazon Prime Clone Deployment Project
## Project Overview

This project focuses on implementing a Continuous Integration (CI) and Continuous Deployment (CD) pipeline using Jenkins. The goal is to deploy a clone of the Amazon Prime Video application to Amazon Elastic Container Registry (ECR) while incorporating security vulnerability scanning using Trivy. The pipeline also integrates SonarQube for static code analysis and quality gate checks.

This project demonstrates deploying an Amazon Prime clone using a set of DevOps tools and practices. The primary tools include:

- **Terraform**: Infrastructure as Code (IaC) tool used to create AWS infrastructure such as EC2 instances and EKS clusters.
- **GitHub**: Source code management platform.
- **Jenkins**: CI/CD automation tool.
- **SonarQube**: Code quality analysis and quality gate tool.
- **NPM**: Build tool for NodeJS.
- **Aqua Trivy**: Security vulnerability scanner.
- **Docker**: Containerization tool used to create images.
- **AWS ECR**: Repository for storing Docker images.
- **AWS EKS**: Managed Kubernetes service for containerized applications.
- **ArgoCD**: Continuous deployment tool.
- **Prometheus & Grafana**: Monitoring and alerting tools.

## Images

Here are some visual aids for the project:

![Project Overview](src/images/Overview.png)





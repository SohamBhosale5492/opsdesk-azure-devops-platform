

\# OpsDesk - Project Overview



\## 1. Project Description



OpsDesk is an Incident Management Platform deployed on Microsoft Azure using automated DevOps and DevSecOps practices.



The project demonstrates automated application building, testing, security scanning, containerization, infrastructure provisioning, deployment and monitoring.



\## 2. Problem Statement



Manual application deployment is time-consuming and error-prone. Organizations need automated and repeatable deployment workflows with security checks and operational monitoring.



OpsDesk demonstrates how these processes can be automated using modern DevOps tools.



\## 3. Application Stack



\- Frontend: React + Vite

\- Backend: Node.js + Express + TypeScript

\- Database: PostgreSQL



\## 4. DevOps Technology Stack



\- Version Control: Git and GitHub

\- CI/CD: Jenkins

\- Code Quality: SonarQube

\- Security Scanning: Trivy

\- Containerization: Docker

\- Container Registry: GitHub Container Registry

\- Infrastructure as Code: Terraform

\- Cloud: Microsoft Azure

\- Deployment: Azure Linux VM + Docker Compose

\- Reverse Proxy: Nginx

\- Monitoring: Prometheus and Grafana



\## 5. Core Objectives



1\. Automate application build and testing.

2\. Implement code quality and security checks.

3\. Build and publish Docker images.

4\. Provision Azure infrastructure using Terraform.

5\. Automate application deployment.

6\. Implement deployment health checks and rollback.

7\. Monitor application health and performance.



\## 6. Deployment Architecture



The application will run on an Azure Linux Virtual Machine using Docker Compose.



Jenkins will initially run locally and remotely deploy verified application images to the Azure VM.



\## 7. Cost Management



Development and testing will primarily use local Docker containers.



Azure infrastructure will be provisioned only when required for deployment demonstrations.




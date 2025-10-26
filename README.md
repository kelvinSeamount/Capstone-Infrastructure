![alt text](<FLow Diagaram.png>)


Overview

This repository contains the complete Infrastructure as Code (IaC) configuration for deploying and managing a production grade Kubernetes based application platform with integrated CI/CD, monitoring, security, and database infrastructure.


Architecture

The infrastructure consists of the following:

    AWS EC2 Infrastructure: Terraform managed compute resources

    Kubernetes Cluster: Multi namespace architecture for application isolation

    MongoDB Cluster: 3 node StatefulSet with persistent storage

    Security & Quality: Checkov (IaC security), SonarQube, Trivy, and HashiCorp Vault integration

    Monitoring Stack: Prometheus and Grafana for observability

    Ingress Controller: SSL/TLS enabled external access



Prerequisites


    AWS CLI configured with appropriate credentials

    Access to AWS account with EC2 provisioning permissions

    Steps for each the infrastructure can be found in the respective folder named steps.txt
 Project: Hybrid Cloud Infrastructure Deployment on AWS
 
 Overview:

This project demonstrates how to deploy and manage a hybrid cloud infrastructure using AWS, Terraform, Docker and Kubernetes.
The goal was to automate provisioning, containerize applications, orchestrate workloads and ensure scalability and reliability across environments.

 Objectives:

Automate AWS infrastructure provisioning using Terraform
Containerize applications with Docker
Orchestrate containers using Kubernetes
Implement secure networking and IAM configuration
Enable CI/CD-style deployment and scalability

 Tools & Technologies:

AWS - EC2, VPC, IAM, S3, Route 53 – Cloud compute, networking and storage
Linux – Server environment and shell automation
Terraform – Infrastructure-as-Code for AWS provisioning
Docker – Containerization of applications
Kubernetes (EKS) – Orchestration and deployment management
Git & GitHub – Version control and collaboration

 Architecture Flow:

Terraform provisions VPC, subnets and EC2 instances on AWS.
Docker builds lightweight images for microservices.
Kubernetes deploys containers across nodes for scalability.
Networking and IAM policies ensure secure communication between services.
Infrastructure updates and scaling can be managed through IaC versioning.

 Repository Structure (will be updated soon)

├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   └── outputs.tf
├── docker/
│   ├── Dockerfile
│   └── app/
├── k8s/
│   ├── deployment.yaml
│   ├── service.yaml
└── README.md


 Current Status:

 Infrastructure design complete
 Implementation in progress
 Full deployment and testing phase next

 Future Enhancements:

Integrate AWS ECR for image management
Add load balancer and auto-scaling groups
Implement CI/CD pipeline using GitHub Actions

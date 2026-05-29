# taskflow

create a plan to do this below basic 3 tier webapp in aws

Task Management App Name: TaskFlow

Like Trello-lite.

Features:
Login/Register
Create tasks
Task status
Dashboard

Stack:
Frontend: React
Backend: node.js
DB: PostgreSQL

Infra:
Cloud: AWS
Network: VPC
Frontend: EC2 VM1
Backend: EC2 VM2
Database: RDS psql
Terraform Remote State: s3

DevOps Practice

Dockerize frontend/backend
GitHub Actions CI/CD self hosted to same ec2 vm
Kubernetes setup and deployment in ec2 vm1 & vm2
Kong ingress 
Prometheus + Grafana + loki setup in kubernetes
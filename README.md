Simple nodejs with NGINX
Created 10 December 2022

Initial Setup Infrastructure as Code using terraform
main.tf

This automatic deploying Centos7 EC2 instance

Use "Terraform Init" > Initial

Use "Terraform plan" > Check plan configuration

Use "Terraform Apply" > Apply configuration

To Run Application

Use "docker compose up -d"

NGINX container can be accessed using PORT 80

Node JS container Expose with port 5000

CI/CD Pipeline Using Gitlab CI
.gitlab-ci.yml

This pipeline has 2 Stages 
- Build
- Deploy



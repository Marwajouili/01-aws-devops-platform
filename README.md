
# 01 - AWS DevOps Platform

**AWS Infrastructure as Code & CI/CD Automation**

[![AWS](https://img.shields.io/badge/Cloud-AWS-orange?logo=amazonaws)](https://aws.amazon.com/)
[![Terraform](https://img.shields.io/badge/IaC-Terraform-7B42BC?logo=terraform)](https://www.terraform.io/)
[![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?logo=githubactions)](https://github.com/features/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Overview

This project aims to build and automate a DevOps infrastructure on **Amazon Web Services (AWS)**.

The objective is to explore Infrastructure as Code (IaC), cloud infrastructure provisioning, CI/CD automation, containerization, and deployment practices through a practical project.

The platform is developed progressively, with an emphasis on automation, reproducibility, security, and maintainability.

## Objectives

- Understand and provision cloud infrastructure on AWS.
- Manage infrastructure using Terraform.
- Automate build and deployment workflows.
- Apply DevOps and CI/CD best practices.
- Work with Linux and cloud environments.
- Improve infrastructure security and monitoring practices.

## Planned Technology Stack

| Category | Technologies |
|---|---|
| Cloud Provider | AWS |
| Infrastructure as Code | Terraform |
| CI/CD | GitHub Actions |
| Version Control | Git, GitHub |
| Operating System | Linux |
| Scripting | Bash, Python |
| Containerization | Docker |
| Monitoring | Prometheus, Grafana |

*Technologies will be integrated progressively as the project develops.*

## Project Architecture

The target workflow is:

```text
Developer
   |
   v
GitHub Repository
   |
   v
GitHub Actions
   |
   v
CI/CD Pipeline
   |
   v
Terraform
   |
   v
AWS Infrastructure
   |
   v
Application Deployment
   |
   v
Monitoring & Logging
```

This diagram represents the planned workflow, not necessarily an already deployed architecture.

## Project Structure

The repository structure will evolve as implementation progresses.

```text
01-aws-devops-platform/
│
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
│   └── providers.tf
│
├── scripts/
│   └── deployment.sh
│
├── .github/
│   └── workflows/
│       └── ci-cd.yml
│
├── README.md
└── LICENSE
```

## Implementation Roadmap

- [ ] Step 1 — Define the AWS infrastructure architecture.
- [ ] Step 2 — Configure the AWS environment.
- [ ] Step 3 — Provision infrastructure using Terraform.
- [ ] Step 4 — Configure the CI/CD workflow with GitHub Actions.
- [ ] Step 5 — Automate application deployment.
- [ ] Step 6 — Integrate monitoring and logging.
- [ ] Step 7 — Apply security and infrastructure best practices.
- [ ] Step 8 — Document the architecture and deployment process.

## Learning Outcomes

Through this project, I aim to strengthen my practical skills in:

- AWS cloud infrastructure.
- Infrastructure as Code with Terraform.
- CI/CD pipeline automation.
- Linux administration and scripting.
- Cloud deployment and monitoring.
- DevOps engineering practices.

## Project Status

**Status:** In progress

This repository is part of my hands-on journey toward becoming a DevOps & Cloud Engineer.

New features, infrastructure components, implementation steps, and technical documentation will be added progressively.

## Author

**Marwa Jouili**  
Junior DevOps & Cloud Engineer

- GitHub: [@Marwajouili](https://github.com/Marwajouili)
- Portfolio: [marwajouili.github.io/portfolio](https://marwajouili.github.io/portfolio)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

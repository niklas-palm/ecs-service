# ECS Fargate

Load-balanced ECS service with Fargate with Github Actions.

## Prerequisites

- Create ECR repo and use inject into github actions workflow
- Setup OIDC between the repo and AWS (To allow CFN deploy, ECR actions etc.)
- Ensure VPC CIDR doesn't overlap with existing ranges

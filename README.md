# Symplichain Hackathon Submission

This repository contains my solution for the Symplichain Software Engineering Intern Hackathon.

## Contents

- CI/CD pipeline using GitHub Actions
- Automated deployment to AWS EC2 and S3

## Approach

I focused on building a simple, scalable, and practical deployment pipeline.

- Frontend is built using React and deployed to S3
- Backend (Django) is deployed to EC2
- GitHub Actions automates the full deployment process

## Security

All sensitive credentials such as AWS keys and EC2 SSH keys are stored securely using GitHub Secrets.

## Note

AWS resources and secrets are assumed to be configured. This repository focuses on workflow design and automation logic.

# CI/CD Pipeline Project

This project demonstrates a complete CI/CD pipeline using GitHub Actions, Tekton, and OpenShift.

## Features
- Automated linting using flake8
- Unit testing using nose
- Pipeline execution using Tekton
- Deployment on OpenShift

## Tools Used
- GitHub Actions
- Tekton Pipelines
- OpenShift

## Workflow
1. Code pushed to GitHub
2. GitHub Actions runs lint and tests
3. Tekton pipeline builds and deploys application
4. Application runs on OpenShift

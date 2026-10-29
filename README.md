
# ci-cd-final-project

## Project Overview
This project demonstrates a CI/CD workflow for a Python application using GitHub Actions and OpenShift Pipelines (Tekton).

## Technologies
- Python
- Flake8 for linting
- Nose for unit testing
- Buildah for container image builds
- OpenShift Pipelines (Tekton) for CI/CD automation

## Objectives
- Automate code linting and unit tests.
- Build a container image.
- Deploy the application to OpenShift.
- Validate the running application and its logs.

## Repository Structure
- `.github/workflows/workflow.yml` — GitHub Actions CI workflow
- `.tekton/tasks.yml` — Tekton cleanup and test task definitions

## Notes
Adjust the test command, source directory, image registry, and deployment settings to match the application and OpenShift environment before running the pipeline.

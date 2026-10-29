# Project Name: CI/CD Final Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.9](https://img.shields.io/badge/Python-3.9-green.svg)](https://shields.io/)

This repository contains the CI/CD pipeline implementation and practice code for the final project in **IBM-CD0215EN-SkillsNetwork Introduction to CI/CD**.

## Project Details
- **Project Name:** CI/CD Final Project - Counter Service
- **Course:** Introduction to CI/CD (IBM-CD0215EN-SkillsNetwork)
- **Application:** Python Flask Hit Counter Service
- **CI/CD Tools:** GitHub Actions, Tekton Pipelines, Red Hat OpenShift

## Contents

- Lab 1: [Build an empty Pipeline](labs/01_base_pipeline/README.md)
- Lab 2: [Adding GitHub Triggers](labs/02_add_git_trigger/README.md)
- Lab 3: [Use Tekton CD Catalog](labs/03_use_tekton_catalog/README.md)
- Lab 4: [Integrate Unit Test Automation](labs/04_unit_test_automation/README.md)
- Lab 5: [Building an Image](labs/05_build_an_image/README.md)
- Lab 6: [Deploy to Kubernetes](labs/06_deploy_to_kubernetes/README.md)

## Pipeline Stages
1. **cleanup**: Cleans the workspace
2. **git-clone**: Clones the source repository
3. **flake8**: Static code analysis and linting
4. **nose**: Automated unit testing with coverage
5. **buildah**: Container image build
6. **deploy**: Deployment to OpenShift / Kubernetes

## Instructor
John Rofrano, Senior Technical Staff Member, DevOps Champion, @ IBM Research

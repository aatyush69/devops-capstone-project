# DevOps Capstone Project - Customer Accounts

[![CI Build](https://github.com/aatyush69/devops-capstone-project/actions/workflows/ci-build.yaml/badge.svg)](https://github.com/aatyush69/devops-capstone-project/actions/workflows/ci-build.yaml)

An elegantly configured, continuous-integration equipped microservice implementation of a RESTful Customer Account directory built on Python Flask, PostgreSQL database, and SQLAlchemy models.

## Architectural Capabilities
- **TDD Practices**: Achieves 95%+ unit test coverage using PyUnit-driven `nosetests` test configurations.
- **Microservices REST**: Complete CRUD patterns supporting Create, Read, Update, Delete, and List customer listings.
- **Defensive Engineering**: Strictly secures public endpoints using `Flask-Talisman` HTTP protective security rules and structured `Flask-CORS` cross-origin specifications.
- **Cloud Hardened**: Packaged cleanly within a secure multi-stage Docker container and ready for single-command deployments using Kubernetes or OpenShift Tekton pipelines.

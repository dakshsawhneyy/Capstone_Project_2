# Developer Onboarding Guide

## Purpose

The goal of this platform is to allow developers to focus on writing application code while the platform handles infrastructure, deployments, security, and observability.

---

## Developer Workflow

1. Clone the repository.
2. Create a feature branch.
3. Develop the application.
4. Commit and push code.
5. Open a Pull Request.
6. CI pipeline validates the code.
7. After approval, changes are merged.
8. GitOps deploys the application automatically.

---

## Responsibilities

Developers are responsible for:

- Writing application code
- Unit testing
- Creating Pull Requests
- Fixing vulnerabilities

Developers are NOT responsible for:

- Kubernetes cluster management
- CI/CD infrastructure
- Monitoring setup
- Security policies
- GitOps configuration

---

## Development Standards

- Use feature branches.
- Every change requires a Pull Request.
- Never commit secrets.
- Follow coding standards.
- Write meaningful commit messages.
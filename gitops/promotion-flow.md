# Promotion Strategy

The platform follows a GitOps-based deployment workflow.

```
Developer

↓

GitHub

↓

GitHub Actions

↓

Container Registry

↓

Update GitOps Repository

↓

Argo CD

↓

Kubernetes
```
---

## Promotion Flow

```
Development

↓

Testing

↓

Approval

↓

Production

```

Deployments are promoted through Git instead of manual kubectl commands.

This provides consistency, traceability, and rollback capability.
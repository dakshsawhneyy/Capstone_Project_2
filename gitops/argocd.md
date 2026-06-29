# Argo CD Strategy

## Purpose

Argo CD continuously synchronizes the Kubernetes cluster with the desired state stored in Git.

---

## Responsibilities

- Monitor Git repository
- Detect configuration changes
- Synchronize Kubernetes
- Perform automatic rollback
- Correct configuration drift

---

## Benefits

- Git as source of truth
- Automatic deployments
- Self-healing
- Version-controlled infrastructure
- Simplified rollback
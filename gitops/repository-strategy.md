# Git Repository Strategy

## Repository Structure

```
application/
gitops/
platform/
monitoring/
security/
finops/
```

---

## Why a Monorepo?

Advantages

- Easier collaboration
- Centralized documentation
- Simple project management
- Ideal for learning

---

## GitOps Repository

The gitops directory stores the desired state of the platform.

Any infrastructure or deployment changes are managed through Git.

Git becomes the single source of truth.
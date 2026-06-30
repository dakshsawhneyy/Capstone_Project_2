# Enterprise Security Policies

## Source Control

- Protected main branch
- Pull Requests required
- Code review mandatory

---

## Secrets

- No secrets inside Git repositories
- Secrets managed through Secret Manager

---

## Container Images

- Images must pass vulnerability scanning
- Only trusted base images are allowed

---

## Kubernetes

- Least privilege access
- RBAC enabled
- Namespace isolation

---

## Compliance Goals

- Secure software delivery
- Consistent security standards
- Automated policy enforcement
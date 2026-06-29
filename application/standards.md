# Application Standards

## Source Control

- GitHub is the single source of truth.
- Protected main branch.
- Pull Requests are mandatory.

---

## Branch Naming

```
feature/<feature-name>

bugfix/<issue>

hotfix/<issue>
```

---

## Commit Message Standard

```
feat: add authentication

fix: resolve login bug

docs: update README

refactor: improve API structure
```

---

## Container Standards

- One Dockerfile per service
- Non-root containers
- Small base images
- Versioned images

---

## Code Quality

- Code review required
- Unit tests required
- Security scan required
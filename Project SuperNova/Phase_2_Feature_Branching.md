# SuperNova – Phase 2: Feature Development (Week 2)

## Story Context
You are assigned Login Authentication.

Team uses Feature Branch Workflow.

---

## Create Feature Branch

```bash
git checkout main
git pull origin main   # Always sync before branching

git checkout -b feature/login-auth   # Naming convention
```

Why:
- Branch isolates feature work
- Prevents breaking production

Docs:
https://git-scm.com/docs/git-checkout
https://git-scm.com/docs/git-branch

---

## Work & Commit

```bash
# Stage specific files (better practice than git add .)
git add src/auth.js

git commit -m "feat(auth): implement login validation logic"
```

Commit Convention:
type(scope): description

Examples:
feat(auth): add JWT validation
fix(payment): correct tax calculation
refactor(api): simplify response handler

---

## Merge via Pull Request

```bash
git push -u origin feature/login-auth
```

Open PR → Code Review → Merge

Docs:
https://docs.github.com/en/pull-requests
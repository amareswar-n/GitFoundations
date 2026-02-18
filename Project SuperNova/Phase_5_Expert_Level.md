# SuperNova – Phase 5: Production & Disaster Recovery (Month 3)

## Git Bisect (Bug Hunting)

```bash
git bisect start
git bisect bad
git bisect good <commit>
```

Binary search through history.

Docs:
https://git-scm.com/docs/git-bisect

---

## Reflog Recovery

```bash
git reflog                # Show reference history
git checkout <hash>       # Recover lost commit
```

Docs:
https://git-scm.com/docs/git-reflog

---

## Safe Force Push

```bash
git push --force-with-lease
```

Why:
Prevents overwriting teammate changes.

Docs:
https://git-scm.com/docs/git-push

---

## Worktrees (Parallel Development)

```bash
git worktree add ../supernova-experiment feature/ui-redesign
```

Docs:
https://git-scm.com/docs/git-worktree

---

## Git Internals Overview

Objects:
- Blob
- Tree
- Commit
- Tag

Docs:
https://git-scm.com/book/en/v2/Git-Internals-Plumbing-and-Porcelain
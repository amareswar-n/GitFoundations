# Week 3 – Advanced Git (SuperNova Phase 3)

## Cherry Pick

git cherry-pick <commit>

Use case:
Backport bug fix to release branch.

---

## Interactive Rebase

git rebase -i HEAD~3

Diagram:

A--B--C (main)
             D--E (feature)

After rebase:

A--B--C--D'--E'

---

## Git Bisect

git bisect start
git bisect bad
git bisect good <commit>

Binary search debugging.

---

## Lab 3
- Create 5 commits
- Introduce bug
- Use git bisect to find it
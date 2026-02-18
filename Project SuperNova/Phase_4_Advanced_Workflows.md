# SuperNova – Phase 4: Advanced Engineering (Month 2)

## Cherry Pick (Backport Fix)

```bash
git cherry-pick <commit_hash>  # Apply specific commit to current branch
```

Used when:
- Fix applied in main
- Needs to go into release branch

Docs:
https://git-scm.com/docs/git-cherry-pick

---

## Interactive Rebase

```bash
git rebase -i HEAD~5
```

Options:
pick
reword
squash
fixup
drop

Used for:
- Cleaning commit history before merge

Docs:
https://git-scm.com/docs/git-rebase
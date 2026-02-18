# SuperNova – Phase 1: Foundations (Day 0 – Week 1)

## Story Context
You have joined the SuperNova engineering team as a Junior Developer.
Your first responsibility is to initialize the repository and prepare the base project.

---

## Day 0 – Repository Initialization

```bash
# Initialize repository
git init SuperNova   # Creates .git directory

cd SuperNova

# Create initial documentation
touch README.md

# Stage files
git add README.md    # Adds file to staging area

# Commit using Conventional Commits
git commit -m "chore: initial commit – setup SuperNova repository"
```

### Why?
- `git add` stages changes
- `git commit` creates immutable history snapshot

Official Docs:
https://git-scm.com/docs/git-init  
https://git-scm.com/docs/git-add  
https://git-scm.com/docs/git-commit  

---

## Day 1 – Connecting Remote (GitHub)

```bash
git remote add origin <repo_url>   # Link local repo to GitHub

git push -u origin main            # Push and set upstream
```

Other options:
- `git remote -v` → view remotes
- `git push origin main --force-with-lease` → safe force push

Docs:
https://git-scm.com/docs/git-remote
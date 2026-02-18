# SuperNova – Phase 3: Release Engineering (Month 1)

## Story Context
SuperNova v1.0 release is approaching.

Team uses Git Flow.

---

## Create Develop Branch

```bash
git checkout -b develop
git push -u origin develop
```

---

## Create Release Branch

```bash
git checkout -b release/v1.0 develop
```

Purpose:
- Stabilize release
- Allow bug fixes only

---

## Tag Release

```bash
git checkout main
git merge release/v1.0

git tag -a v1.0 -m "release: SuperNova v1.0"

git push origin v1.0
```

Docs:
https://git-scm.com/docs/git-tag
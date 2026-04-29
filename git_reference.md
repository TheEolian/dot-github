# Git Quick Reference

A short reference for starting work, working on a branch, and cleaning up after your PR is merged.

#### Start work

```bash
git clone <repo-url>
cd <repo-name>
git checkout main
git pull
git checkout -b feature/your-branch-name
git push -u origin feature/your-branch-name
```

#### During work

```bash
git add .
git commit -m "message"
git push
```

#### After work

```bash
git checkout main
git pull
git branch -d feature/your-branch-name
git fetch --prune
```

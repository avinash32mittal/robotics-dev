# Git Cheat Sheet

## Initialize Repository

```bash
git init
```

---

## Check Status

```bash
git status
```

---

## Configure User

```bash
git config --global user.name "Your Name"
git config --global user.email "email@example.com"

git config --list
```

---

## Stage Changes

```bash
git add file
git add .
```

---

## Commit

```bash
git commit -m "message"
```

Commit Style

```
init:
docs:
feat:
fix:
refactor:
test:
perf:
chore:
```

---

## Repository History

```bash
git log
git log --oneline
```

---

## Branches

```bash
git branch
git branch -vv
```

---

## Remote Repository

```bash
git remote -v

git remote add origin git@github.com:user/repo.git
```

---

## Push

```bash
git push

git push -u origin main
```

---

## SSH

```bash
ssh -T git@github.com
ssh -vT git@github.com
```

---

## Git Workflow

Working Directory

↓

git add

↓

Staging Area

↓

git commit

↓

Repository

↓

git push

↓

GitHub
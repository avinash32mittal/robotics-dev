# Git Handbook

**Version:** 1.0\
**Curriculum:** Phase 1

------------------------------------------------------------------------

# Purpose

Learn Git and GitHub to track changes, collaborate safely, and maintain
professional engineering projects.

------------------------------------------------------------------------

# What is Git?

## Purpose

Git is a distributed version control system.

## Key Points

-   Tracks file history
-   Enables collaboration
-   Allows reverting changes
-   Industry standard

## Robotics Example

Track every change to robot code, CAD files, and documentation without
losing previous versions.

------------------------------------------------------------------------

# Git vs GitHub

  Git                        GitHub
  -------------------------- ----------------------------
  Version control software   Cloud hosting platform
  Works locally              Stores remote repositories
  Tracks history             Enables collaboration

------------------------------------------------------------------------

# Repository

A repository (repo) contains your project and its complete history.

``` bash
git init
```

------------------------------------------------------------------------

# Basic Workflow

``` text
Edit Files
    ↓
git status
    ↓
git add
    ↓
git commit
    ↓
git push
```

------------------------------------------------------------------------

# Essential Commands

  Command                 Purpose             Example
  ----------------------- ------------------- -----------------------------
  `git init`              Create repository   `git init`
  `git clone URL`         Copy repo           `git clone <url>`
  `git status`            Check changes       `git status`
  `git add .`             Stage all files     `git add .`
  `git commit -m "msg"`   Save snapshot       `git commit -m "Add notes"`
  `git push`              Upload commits      `git push`
  `git pull`              Download updates    `git pull`
  `git log`               View history        `git log --oneline`

------------------------------------------------------------------------

# Branches (Introduction)

A branch is an independent line of development.

``` bash
git branch
git checkout main
```

For this curriculum, we'll primarily work on `main` until branching is
introduced in depth.

------------------------------------------------------------------------

# Remote Repository

Connect a local repository to GitHub.

``` bash
git remote -v
```

Push changes:

``` bash
git push origin main
```

------------------------------------------------------------------------

# Commit Messages

Good:

``` text
Add Python loops notes
Fix Linux handbook formatting
Create robotics workspace
```

Avoid:

``` text
update
changes
final
test
```

------------------------------------------------------------------------

# .gitignore

Used to exclude generated or temporary files.

Example:

``` gitignore
__pycache__/
*.pyc
.venv/
build/
install/
log/
.vscode/
```

------------------------------------------------------------------------

# Recommended Workflow

1.  Pull latest changes
2.  Make small logical edits
3.  Check status
4.  Commit with meaningful message
5.  Push

------------------------------------------------------------------------

# Common Mistakes

-   Forgetting `git add`
-   Large unrelated commits
-   Poor commit messages
-   Editing directly on GitHub instead of locally
-   Ignoring merge conflicts

------------------------------------------------------------------------

# Quick Reference

  Task              Command
  ----------------- -----------------------
  Initialize repo   `git init`
  Clone repo        `git clone URL`
  Check status      `git status`
  Stage files       `git add .`
  Commit            `git commit -m "msg"`
  Push              `git push`
  Pull              `git pull`
  History           `git log --oneline`

------------------------------------------------------------------------

# Learn More

-   00 - Foundations Handbook
-   01 - Linux Handbook
-   03 - VS Code Handbook

# Linux Handbook

**Version:** 1.0\
**Curriculum:** Phase 1

------------------------------------------------------------------------

# Purpose

Learn the Linux fundamentals required for software engineering, robotics
development, and ROS 2.

------------------------------------------------------------------------

# Why Linux?

## Purpose

Understand why Linux is the preferred operating system for robotics.

## Key Points

-   Open source
-   Stable and secure
-   Excellent developer tools
-   Native support for ROS 2
-   Widely used in robotics and cloud systems

## Robotics Example

Most industrial and research robots run Linux-based operating systems.

------------------------------------------------------------------------

# Ubuntu

## Purpose

Ubuntu is a beginner-friendly Linux distribution used throughout this
curriculum.

## Key Points

-   Debian-based
-   Long Term Support (LTS) releases recommended
-   Large software ecosystem

------------------------------------------------------------------------

# Terminal

## Purpose

The terminal allows direct interaction with the operating system.

## Key Points

-   Faster than GUI for many tasks
-   Essential for development
-   Required for ROS 2 workflows

------------------------------------------------------------------------

# Linux File System

    /
    ├── home
    ├── etc
    ├── usr
    ├── var
    └── tmp

Your personal files are usually stored in:

``` text
/home/<username>/
```

------------------------------------------------------------------------

# Navigation Commands

## pwd

Shows current directory.

``` bash
pwd
```

## ls

Lists files.

``` bash
ls
ls -la
```

## cd

Changes directory.

``` bash
cd Documents
cd ..
cd ~
```

------------------------------------------------------------------------

# File Management

## mkdir

``` bash
mkdir robotics-dev
```

## touch

``` bash
touch notes.md
```

## cp

``` bash
cp source.txt backup.txt
```

## mv

``` bash
mv old.txt new.txt
```

## rm

``` bash
rm file.txt
rm -r folder/
```

⚠️ `rm` permanently deletes files.

------------------------------------------------------------------------

# Viewing & Editing Files

## cat

``` bash
cat file.txt
```

## less

``` bash
less file.txt
```

## nano

``` bash
nano file.txt
```

------------------------------------------------------------------------

# sudo

Runs commands with administrator privileges.

``` bash
sudo apt update
```

Use only when necessary.

------------------------------------------------------------------------

# Package Management

## Update package lists

``` bash
sudo apt update
```

## Upgrade installed packages

``` bash
sudo apt upgrade
```

## Install software

``` bash
sudo apt install git
```

------------------------------------------------------------------------

# Useful Shortcuts

  Shortcut   Action
  ---------- ------------------
  Tab        Auto-complete
  ↑          Previous command
  Ctrl+C     Stop command
  Ctrl+L     Clear terminal
  Ctrl+R     Search history

------------------------------------------------------------------------

# Recommended Workflow

1.  Open terminal
2.  Navigate to project
3.  Pull latest changes
4.  Activate environment (when applicable)
5.  Develop
6.  Commit changes
7.  Push to GitHub

------------------------------------------------------------------------

# Common Mistakes

-   Running commands in the wrong directory
-   Using `sudo` unnecessarily
-   Forgetting `-r` when removing folders
-   Typing relative paths incorrectly

------------------------------------------------------------------------

# Quick Reference

  Command       Purpose
  ------------- -------------------
  pwd           Current directory
  ls            List files
  cd            Change directory
  mkdir         Create folder
  touch         Create file
  cp            Copy
  mv            Move/Rename
  rm            Delete
  cat           Display file
  nano          Edit file
  sudo          Admin privileges
  apt update    Refresh packages
  apt upgrade   Upgrade software

------------------------------------------------------------------------

# Learn More

-   00 - Foundations Handbook
-   02 - Git Handbook
-   03 - VS Code Handbook

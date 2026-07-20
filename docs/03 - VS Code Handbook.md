# VS Code Handbook

**Version:** 1.0\
**Curriculum:** Phase 1

------------------------------------------------------------------------

# Purpose

Use Visual Studio Code (VS Code) as the primary development environment
for the Robotics Systems Engineering curriculum.

------------------------------------------------------------------------

# Why VS Code?

## Key Points

-   Lightweight and fast
-   Excellent Python support
-   Built-in Git integration
-   Integrated terminal
-   Large extension ecosystem
-   Cross-platform

## Robotics Example

VS Code is commonly used to develop Python, C++, ROS 2 and embedded
software.

------------------------------------------------------------------------

# Workspace Structure

``` text
robotics-dev/
├── docs/
├── projects/
├── tools/
├── README.md
├── ROADMAP.md
└── CHANGELOG.md
```

Open the **robotics-dev** folder instead of individual files.

------------------------------------------------------------------------

# Interface Overview

  Component        Purpose
  ---------------- ----------------------------
  Explorer         Browse files
  Search           Find text
  Source Control   Git integration
  Run & Debug      Execute and debug code
  Extensions       Install tools
  Terminal         Run Linux and Git commands

------------------------------------------------------------------------

# Essential Extensions

  Extension              Purpose
  ---------------------- ------------------
  Python                 Python support
  Pylance                IntelliSense
  Black Formatter        Code formatting
  GitHub Pull Requests   GitHub workflow
  Markdown All in One    Markdown editing

------------------------------------------------------------------------

# Integrated Terminal

Open with:

``` text
Ctrl + `
```

Use it for:

-   Linux commands
-   Git commands
-   Python execution
-   Package installation

------------------------------------------------------------------------

# Python Interpreter

Select the correct interpreter:

``` text
Ctrl + Shift + P
→ Python: Select Interpreter
```

Always verify the interpreter before running code.

------------------------------------------------------------------------

# Running Python

``` bash
python3 hello.py
```

or use the ▶ Run button.

------------------------------------------------------------------------

# Formatting Code

Format document:

``` text
Shift + Alt + F
```

Recommended formatter:

-   Black Formatter

------------------------------------------------------------------------

# Git Integration

The Source Control panel allows you to:

-   View changes
-   Stage files
-   Commit
-   Push
-   Pull
-   Resolve conflicts

------------------------------------------------------------------------

# Useful Shortcuts

  Shortcut       Action
  -------------- -----------------
  Ctrl+P         Open file
  Ctrl+Shift+P   Command Palette
  Ctrl+\`        Terminal
  Ctrl+/         Toggle comment
  Ctrl+S         Save
  Ctrl+Shift+F   Global search
  F5             Run / Debug

------------------------------------------------------------------------

# Best Practices

-   Open the project root folder.
-   Keep extensions minimal.
-   Commit changes frequently.
-   Organize files consistently.
-   Use the integrated terminal instead of multiple external terminals.

------------------------------------------------------------------------

# Common Mistakes

-   Opening a single file instead of the workspace
-   Using the wrong Python interpreter
-   Ignoring linting errors
-   Installing unnecessary extensions

------------------------------------------------------------------------

# Quick Reference

  Task                   Shortcut / Action
  ---------------------- -------------------
  Open Command Palette   Ctrl+Shift+P
  Open Terminal          Ctrl+\`
  Save File              Ctrl+S
  Format Code            Shift+Alt+F
  Run Program            F5

------------------------------------------------------------------------

# Learn More

-   00 - Foundations Handbook
-   01 - Linux Handbook
-   02 - Git Handbook
-   04 - Programming Handbook

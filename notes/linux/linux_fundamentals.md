# Linux & Development Fundamentals

## Package Management

### sudo

Run command as administrator.

Think:
temporary superpowers.

Example:

sudo apt update

---

### apt

Ubuntu package manager.

Equivalent:

Play Store + Installer + Updater

Example:

apt install git

---

### snap

Alternative package manager.

Containerized applications.

Usually:
slower startup
larger packages

Use selectively.

---

## Updating System

### update

Refresh package availability.

Does NOT install.

Example:

sudo apt update

Meaning:

"What software exists?"

---

### upgrade

Install newer versions.

Example:

sudo apt upgrade

Meaning:

"Install available updates."

---

### -y

Auto answer:

YES

Example:

sudo apt install git -y

---

## Development Tools

### build-essential

Core compiler tools.

Includes:

gcc
g++
make

Used to compile:

C
C++
ROS packages

---

### git

Version control.

Purpose:

Track changes.

Rollback mistakes.

Collaborate.

---

### curl

Request/download data.

Example:

curl website.com

---

### wget

Download files.

Example:

wget file.zip

---

### python3

Primary interpreter.

Used for:

robotics
automation
simulation

---

### pip

Python package manager.

Install libraries.

Example:

pip install numpy

---

### venv

Virtual environment.

Purpose:

Isolate project dependencies.

---

## Terminal Concepts

### echo

Output text.

Example:

echo hello

---

### >>

Append output.

Example:

echo hello >> notes.txt

---

### ~/.bashrc

Runs whenever terminal opens.

Used for:

environment setup

---

### source

Apply changes immediately.

Example:

source ~/.bashrc

---

### tee

Write command output into file.

Useful for configuration.

---

## Monitoring

### htop

Interactive system monitor.

Like:

Task Manager

---

### tree

Visualize folder structure.

Example:

tree ~/robotics-dev

---

## Principle Learned

Software environments are layered.

Editor ≠ Terminal ≠ Operating System.

Configuration determines behavior.

---

# Development Environment Concepts

## Formatter

Purpose:

Automatically rewrite code into consistent style.

Example:

Black Formatter

Input:

x=1
print( x )

Output:

x = 1
print(x)

Lesson:

Formatting and execution are separate concerns.

---

## Extension vs System Installation

Editor installation ≠ operating system installation.

Example:

Black extension worked.

black command failed.

Meaning:

VS Code contained formatter.

Ubuntu terminal did not.

Solution:

Install separately.

Validation:

black --version

---

## PATH

Environment variable.

Purpose:

Tells terminal where executable programs exist.

View:

echo $PATH

Mental Model:

Search map for commands.

Example:

black
python
git

Common Problem:

Program installed but terminal cannot find it.

Solution:

Update PATH.

---

## Development Environment

Layers:

Operating System
↓

Terminal
↓

Editor
↓

Extensions
↓

Runtime

Lesson:

Configuration determines behavior.

---

## Linux File Permissions

d
Directory

-
Regular File

l
Symbolic Link

Permission structure:

rwx | r-x | ---
Owner Group Others

---

## Special Directories

.
Current directory

..
Parent directory

~
Home directory

---

## Hidden Files

Files beginning with:

.

are hidden.

Examples:

.git
.ssh
.bashrc
.profile
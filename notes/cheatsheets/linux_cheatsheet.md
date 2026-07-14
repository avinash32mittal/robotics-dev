# Linux Cheat Sheet

## Navigation

```bash
pwd                 # Present Working Directory
ls                  # List files
ls -l               # Long listing
ls -la              # Long listing including hidden files
cd folder_name
cd ..
cd ~
tree
```

---

## File Operations

```bash
mkdir folder
touch file.txt
cp source destination
mv source destination
rm file
rm -r folder
```

---

## Useful Commands

```bash
clear
history
echo
cat
less
nano
code .
```

---

## Package Management (APT)

```bash
sudo apt update
sudo apt upgrade
sudo apt install package
sudo apt remove package
sudo apt autoremove
```

APT = Advanced Package Tool

---

## System Information

```bash
whoami
hostname
uname -a
neofetch
htop
df -h
free -h
```

---

## Permissions

```
r = Read
w = Write
x = Execute

Owner | Group | Others

rwx r-x ---
```

---

## Hidden Files

```
.
Current directory

..
Parent directory

~
Home directory

Files beginning with "." are hidden.
```

Examples

```
.git
.ssh
.bashrc
```

---

## SSH

```bash
ls -la ~/.ssh
ssh-keygen -t ed25519 -C "email"
cat ~/.ssh/id_ed25519.pub
ssh -T git@github.com
ssh -vT git@github.com
```

---

## Useful Shortcuts

```
Ctrl + C
Interrupt current program

Ctrl + D
End input / Exit shell

Ctrl + L
Clear terminal

Tab
Autocomplete command

Up Arrow
Previous command

history
Command history
```
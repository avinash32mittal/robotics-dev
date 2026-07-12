# Command Dictionary

# sudo

Category:
System

Syntax:

sudo command

What It Does:

Temporarily execute command with administrator privileges.

Mental Model:

Borrow root authority.

Example:

sudo apt install git

Breakdown:

sudo
→ execute as administrator

Typical Output:

[sudo] password:

Common Mistakes:

Running everything with sudo.

Validation:

Command executes successfully.

Related:

su

Notes:

Use intentionally.

---

# apt

Category:
Package Management

Syntax:

apt operation package

What It Does:

Installs and manages software.

Mental Model:

Linux package marketplace.

Example:

sudo apt install tree

Breakdown:

apt
→ package manager

install
→ install package

tree
→ package

Common Mistakes:

Forgetting update.

Validation:

package --version

Related:

snap
pip

---

# source

Category:
Environment

Syntax:

source file

What It Does:

Apply file immediately.

Mental Model:

Reload configuration.

Example:

source ~/.bashrc

Breakdown:

source
→ execute shell file

~/
→ home directory

.bashrc
→ startup config

Validation:

echo $PATH

Related:

bashrc
export

---

# tree

Category:
Filesystem

Syntax:

tree path

What It Does:

Displays folder hierarchy.

Mental Model:

X-ray of directory.

Example:

tree ~/robotics-dev

Validation:

Hierarchy displayed.

Related:

ls
find

# mv

Category:
Filesystem

Syntax:

mv source destination

What It Does:

Move or rename files.

Example:

mv notes/linux/file.md notes/

Mental Model:

Pick up and place.

Validation:

tree

Related:

cp
rm

---

# pwd

Category:
Navigation

Syntax:

pwd

What It Does:

Print current directory.

Mental Model:

Where am I?

Example:

pwd

Validation:

Path displayed.

Notes:

Useful when lost.

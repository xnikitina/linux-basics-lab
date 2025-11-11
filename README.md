# Linux Basics Lab

**Linux Basics Lab** is an interactive, beginner-friendly project that teaches essential Linux commands through categorized, executable Bash scripts. Each script explains what the command does, shows examples, and safely runs them in your terminal. It’s perfect for students, self-learners, or anyone who wants to build confidence using the Linux command line.

## Features

- Categorized command scripts (navigation, permissions, file handling, etc.)
- Executable examples with inline explanations
- Setup script to prepare the environment and test files
- Cheatsheet and filesystem overview
- Works in any Linux terminal or WSL (Windows Subsystem for Linux)

## Project Structure

```text
linux-basics-lab/
├── README.md
├── setup.sh
├── run_all.sh
├── commands/
│   ├── 00_filesystem.sh         # Linux directory structure
│   ├── 01_package_management.sh # apt install, remove, list
│   ├── 02_navigation.sh         # pwd, cd, ls, clear
│   ├── 03_permissions.sh        # chmod, chown, umask
│   ├── 04_file_handling.sh      # touch, mkdir, rm, mv, cp, nano
│   ├── 05_redirection.sh        # >, >>, |, tee
│   ├── 06_searching.sh          # grep, find, head, tail, less
│   ├── 07_users_groups.sh       # useradd, userdel, passwd, groups, usermod
│   ├── 08_help.sh               # man, whatis, apropos
│   └── 99_cheatsheet.sh         # optional: all-in-one summary
└── docs/
    ├── cheatsheet.md
    └── filesystem.md
```
## Getting Started

### Step 1: Clone the repository

```bash
git clone https://github.com/xnikitina/linux-basics-lab.git
cd linux-basics-lab
```

### Step 2: Run the setup script

- Create test directories and files
- Set permissions
- Make all command scripts executable

```bash
bash setup.sh
```

### Step 3: Run all command scripts

```bash
bash run_all.sh
```
Or run individual scripts:

```bash
bash commands/02_navidation.sh
```

## What You’ll Learn

### Package Management  
Learn how to manage software packages using `apt` commands:
- `apt install`
- `apt remove`
- `apt list --installed`  
[01_package_management.sh](commands/01_package_management.sh)

### File Navigation  
Explore how to move through the filesystem and list contents:
- `pwd`
- `cd`
- `ls`, `ls -l`, `ls -a`
- `clear`  
[02_navigation.sh](commands/02_navigation.sh)

### Permissions  
Understand file permissions and how to modify them:
- `chmod` (symbolic and numeric modes)
- `chown`
- `umask`  
[03_permissions.sh](commands/03_permissions.sh)

### File Handling  
Learn how to create, move, copy, and edit files and directories:
- `touch`
- `mkdir`, `rmdir`
- `rm`, `mv`, `cp`
- `nano`, `cat`  
[04_file_handling.sh](commands/04_file_handling.sh)

### Redirection & Pipes
Redirecting output and chaining commands:
- `>` (overwrite)
- `>>` (append)
- `|` (pipe)
- `tee

### Searching & Filtering
Searching and filtering content in files and across the filesystem:
- `grep`
- `find` with:
  - `-name`
  - `-iname`
  - `-mtime`
  - `-mmin`
- `head`
- `tail`
- `less`
- Wildcards: `*`

### Users & Groups
Managing users and groups:
- `useradd`
- `userdel`
- `passwd`
- `groups`
- `usermod`
- `chown`

### Help & Documentation
Accessing built-in help and command documentation:
- `man`
- `whatis`
- `apropos`

### Linux Filesystem Structure
Understanding key directories in the Linux system:
- `/home`
- `/etc`
- `/lib`
- `/mnt`
- `/tmp`
- `/bin`


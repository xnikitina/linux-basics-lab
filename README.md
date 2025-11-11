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
git clone https://github.com/yourname/linux-basics-lab.git
cd linux-basics-lab


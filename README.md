# Git Commands

This repository contains a comprehensive guide to essential Git commands.

## Basic Commands

### Version and Help
- `git --version` -> Get the version of Git installed on your system
- `git --help` -> Get the help menu
- `git <command> --help` -> Get the help menu for a specific command in the terminal
- `git help <command>` -> Get the help menu for a specific command in an HTML page

### Configuration
- `git config user.name "<name>"` -> Set the name of the user locally
- `git config user.email "<email>"` -> Set the email of the user locally
- `git config --global user.name "<name>"` -> Set the name of the user globally
- `git config --global user.email "<email>"` -> Set the email of the user globally
- `git config --list` -> List all configurations (local and global)
- `git config --global --list` -> List all global configurations

### Initializing a Repository
- `git init` -> Initialize a Git repository in the current directory

## Working with the Repository

### Status
- `git status` -> Check the status of the repository
- `git status --short` -> Check the status of the repository in short format
  - ?? -> Untracked files
  - A -> Files added to the staging area
  - M -> Files modified
  - D -> Files deleted

### Adding Files
- `git add <file1> ... <fileN>` -> Add the specified files to the staging area
- `git add .` | `git add --all` -> Add all the files to the staging area

### Committing Changes
- `git commit -m "<message>"` -> Commit the files in the staging area with a message

### Viewing History
- `git log` -> View the commit history

## Branching and Merging

### Branching
- `git branch <branch-name>` -> Create a new branch from the current branch
- `git branch` -> List all branches
- `git branch -d <branch-name>` -> Delete the specified branch

### Checking Out
- `git checkout <branch-name>` -> Switch to the specified branch
- `git checkout -b <branch-name>` -> Create a new branch and switch to it

### Merging
- `git merge <branch-name>` -> Merge the specified branch into the current branch
- `git merge --abort` -> Abort the merge process

---

Feel free to clone this repository and practice these commands on your local machine. Happy coding!
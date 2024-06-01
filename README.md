# Git Commands

## Basic Commands

- `git --version` -> to get the version of Git installed on your system
- `git --help` -> to get the help menu
- `git <command> --help` -> to get the help menu for a specific command in the terminal
- `git help <command>` -> to get the help menu for a specific command in an HTML page

## Configuration Commands

- `git config user.name "<name>"` -> to set the name of the user locally
- `git config user.email "<email>"` -> to set the email of the user locally
- `git config --global user.name "<name>"` -> to set the name of the user globally
- `git config --global user.email "<email>"` -> to set the email of the user globally
- `git config --list` -> to list all the configurations (local and global)
- `git config --global --list` -> to list all the global configurations

## Repository Commands

- `git init` -> to initialize a Git repository in the current directory

## Status Commands

- `git status` -> to check the status of the repository
- `git status --short` -> to check the status of the repository in short format
  - `??` -> untracked files
  - `A` -> files added to the staging area
  - `M` -> files modified
  - `D` -> files deleted

## Staging Commands

- `git add <file1> ... <fileN>` -> to add the specified files to the staging area
- `git add .` | `git add --all` -> to add all the files to the staging area

## Commit Commands

- `git commit -m "<message>"` -> to commit the files in the staging area with a message

## Log Commands

- `git log` -> to view the commit history

## Branch Commands

- `git branch <branch-name>` -> to create a new branch from the current branch
- `git branch` -> to list all the branches
- `git checkout <branch-name>` -> to switch to the specified branch
- `git checkout -b <branch-name>` -> to create a new branch and switch to it

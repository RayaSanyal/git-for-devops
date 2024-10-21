# Git for Devops

This repository is for understanding Git concepts for Devops


Git Commands Overview
Directory Management
Create a new directory:
mkdir <directory-name>

Change to a directory:
cd <directory-name>

Git Initialization
Initialize a new Git repository:
git init
File Operations
Create a new file:
touch <file-name>

List files and directories:
ls
ls -l
ls -la

Edit a file:
vim <file-name>

Remove a file:
rm <file-name>

Git Status
Check the status of the repository:
git status
Staging Changes
Add a file to the staging area:
git add <file-name>

Remove a file from the staging area:
git rm --cached <file-name>

Committing Changes
Commit staged changes:
git commit -m "Your commit message"
Branching
Create a new branch:
git checkout -b <branch-name>

Switch to an existing branch:
git checkout <branch-name>
git switch <branch-name>

List branches:
git branch

Viewing History
Show commit history:
git log
git log --oneline
Restoring Files
Restore a deleted or modified file:
git restore <file-name>
Configuration
Set global username:
git config --global user.name "Your Name"

Set global email:
git config --global user.email "your-email@example.com"

It has great security feature. You can't push any secret key or password while doing push from local to github

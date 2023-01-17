# Git Commands

This file contains basic git commands.

## Basic Git Commands

- ``git init``: create a repository 
- ``git add``: track a file
- ``git status``: status of repository
- ``git log``: log of all commits

## Configuration Commands

- git config -l: shows current configuration settings
- git config --global user.name "USERNAME"
- git config --global user.email email_address
- git remote -v
- git remote add origin URL
- git remote add origin TOKEN@URL
- git remote remove REMOTE_NAME

## Branches
- git branch --move BRANCHNAME NEWBRANCHNAME (e.g. git branch --move master main)

## Remote Commands

- git push origin main: pushes main branch to origin
- git fetch: fetches files from remote
- git checkout origin/main: examine files from remote
- git switch main: switch to local main branch
- git pull origin main

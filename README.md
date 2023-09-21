# Git Cheat Sheet and Branching Practice


## Overview

Some new over view



## Basic commands
* `git inti` - initialize local Git repo
* `git add fileName` - stage changed file
* `git commit -m message` - do commit

## Info commands
* `git status` - show status of working dir

## Branching commands
* `git branch` - list local branches
* `git branch -m newName` rename current branch
* `git checkout branchName` switch to local branch

## Remote commands
* `git push origin branchName` - push local commits to remote repo `origin` on branch branchName
* `git remote add origin url`
* `git push -u origin branchName` - push, and 
make origin the default remote for further push
* `git pull origin branchName` pull and 
attempt to merge branchName into local branch

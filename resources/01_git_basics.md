## Introduction to Git

This document outlines basic usage of git. For Linux and Mac users, these commands should work in **Terminal**. For Windows users, these should work in **Git Bash**.

### What is Git?

Git is a version control system that allows you to track files and file changes in a repository ("repo")

### Why should I use it?

Git provides you access to all versions of all files in a Git repository at any time. Multiple developers can work on project concurrently without affecting each other. 

### What is Github?

Github is a website that allows you to store your Git repos online. It serves as a backup for your files and provides a visual interface for navigating repos and makes repo collaboration easy. 

### Git Installation

Follow [Getting Started - Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) 

### Basic commands

##### Tell Git who you are
* `git config --global user.name "KC Tan"` Configure the author name 
* `git config --global user.email kctan6@gmail.com` and email address to be used with your commits

##### Create a new local repository
* `git init` Set the current directory as a new repository

##### Check out a repository
* `git clone /path/to/repository` Create a working copy of a local repository
* `git clone username@host:/path/to/repository` or a remote server

##### Add one or more files to staging (index):
* `git add <filename>` Single file
* `git add .` All the files

##### Commit
* `git commit -m "commit message"` Commit changes to head (but not yet to the remote repository)

##### Push
* `git push origin master` Send changes to the master branch of your remote repository

##### Status
* `git status` List the files you've changed and those you still need to add or commit

##### Connect to a remote repository 
* `git remote add origin <server>` If you haven't connected your local repository to a remote server, add the server to be able to push to it:
* `git remote -v` List all currently configured remote repositories:

##### Branches
* Create a new branch and switch to it
`git checkout -b <branchname>`
* Switch from one branch to another
`git checkout <branchname>`
* List all the branches in your repo, and also tell you what branch you're currently in
`git branch`
* Delete the feature branch:
`git branch -d <branchname>`
* Push the branch to your remote repository, so others can use it
`git push origin <branchname>`
* Push all branches to your remote repository
`git push --all origin`

##### Update from the remote repository
* Fetch and merge changes on the remote server to your working directory
`git pull`
* To merge a different branch into your active branch
`git merge <branchname>`
* View all the merge conflicts
`git diff`
* View the conflicts against the base file
`git diff --base <filename>`
* Preview changes, before merging
`git diff <sourcebranch> <targetbranch>`
* After you have manually resolved any conflicts, you mark the changed file
`git add <filename>`

##### Undo local changes
* If you mess up, you can replace the changes in your working tree with the last content in head. Changes already added to the index, as well as new files, will be kept.
`git checkout -- <filename>`
* Instead, to drop all your local changes and commits, fetch the latest history from the server and point your local master branch at it, do this:
`git fetch origin`
`git reset --hard origin/master`
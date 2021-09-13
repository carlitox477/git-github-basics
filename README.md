# What is git?
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

## What is a version control system?
* It allows us to save many versions of a same proyect using checkpoint
* It save us memory
* It comes to solve the problem of saving multiple files for one proyect to have checkpoints

## Git disadvantages
* It works locally. Meaning that working in a group project just with git unpractical.
* If we lose or damage the computer where the project is we can lose all the change log.

# What is github?
* Is the largest development platform
* It's a Cloud Hosting & collaboration provider
* It is a git repository hosting
* It come to solve the git's problems

Github and Git aren't the same thing, but they complement each other
![Git & Github comparison](/img/git_and_github.png)

# How does it work?
Whenever we use git, it is created a working directory and a hidden folder called __.git__ , where the version control system works.

![How git works](/img/how_git_works.png)

More information [here](https://medium.com/hackernoon/understanding-git-index-4821a0765cf)

## Basic concepts
* Working directory: Folder where git is managed
* Commit: files and folder snapshot. It registers the changes
* Branch: Order set of commits

# Git instalation
Check [website](https://git-scm.com/)

# Git basic commands
* **git init**: To initialize repository
* **git status**: Gives a description about the project files and the current branch. It also give us information about the current folder files, if they are in the worging directory or the staging area
* **git add file_name**: It add file_name to the staging area. If we use a point (__.__) instead of a file name, it adds all the current folder files to the staging area 
* **git commit -m "message"**: Moves files from staging area to the repository with an attached massage
* **git config --global user.email "email"**: It allow us to configure with which mail we identify ourself inside git
* **git config --global user.name "name"**: It allow us to configure with which name we identify ourself inside git
* **git config user.email**: It gives us the current user's mail
* **git config user.name**: It gives us the current user's name
* **git log**: It give us information about all the logs of the current branch
* **git checkout commitId_or_branch**: It allow us to restore to a previous version or to move to other branch
* **git branch**: It give us the names of all branches
* **git branch new_branch_name**: It creates another branch
* **git chechout -b new_branch_name**: It create a new branch and move the head to it.



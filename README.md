# Basic Command That Relate to Django

This is a note for basic command

## Basic Command for Git

### 1) git config
**Utility** : To set your user name and email in the main configuration file.
  
**How to** : To check your name and email type in **_git config --global user.name_** and **_git config --global user.email_**. And to set your new email or name **_git config --global user.name = “Zarif”_** and **_git config --global user.email = “zarif9110@gmail.com”_**
  
### 2) git init
**Utility** : To initialise a git repository for a new or existing project.

**How to** : **_git init_** in the root of your project directory.

### 3) git clone
**Utility :** To copy a git repository from remote source, also sets the remote to original source so that you can pull again.

**How to : _git clone <:clone git url:>_**

### 4) git status
**Utility :** To check the status of files you’ve changed in your working directory, i.e, what all has changed since your last commit.

**How to : _git status_** in your working directory. lists out all the files that have been changed.

### 5) git add
**Utility :** adds changes to stage/index in your working directory.

**How to : _git add ._**

### 6) git commit
**Utility :** commits your changes and sets it to new commit object for your remote.

**How to : _git commit -m ”sweet little commit message”_**

### 7) git push/git pull
**Utility :** Push or Pull your changes to remote. If you have added and committed your changes and you want to push them. Or if your remote has updated and you want those latest changes.

**How to : _git pull <:remote:> <:branch:>_** and **_git push <:remote:> <:branch:>_**

# GIT COMMANDS

## Content
- [Definition](#what-is-git)
- [Prerequisits](#prerequisits)
- [Git Initialization](#git-initialization)
- [Checking git status](#checking-git-status)
- [Staging your files](#staging-your-files)



## What is GIT?
Git is an **open source** distributed version control system


## Prerequisits
To use GIT ,you are expected to have an updated version of the software on your operating system
to download go to the [git website]() and download the version for your operating sysytem

## Git Initialization
To initialize a git repsitory we use the `git init` command. to do this,
1.Navigate to your working repository
```
cd working-dir
```
2.Type the command `git init` to initiate the dir into a repository
```
git init
```
## Checking git status
To check git status of your git repository,you can use the command `git status` as seen below
```
git status
```
## Staging your files
Staging or adding your file is the term used to describe the process of making git trackyour files,this involvesmoving the files from the woerkspace to the staging area.To do this,use `git add filename` command to add a single file, `git add file1 file1` to add multiple files, and `git add ,`
```
git add index.html
```
```
git add index.html style.css
```
```
git add,
```
## Checking git log
To check all logs we use `git log` and the view it in a summarized format or version `git log --`.

## Commit Command
To commit a file or folder we use `git commit -m "(input command executed)"` , this sends a message on the action or command executed.

## Remote Command
the remote command is used to manage remote repositories in Git, those are versions of your project that are hosted elsewhere, like on GitHub or another server. `git remote --v`
`git remote add origin (the repository link)` `git remote remove origin`

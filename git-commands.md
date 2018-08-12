# Git Commands

## Process

- **git init** : start a new project
- **git clone** : clone an existing project
- **git status** :
- **git add** :
- **git add --all** : Adds all files and modified files
- **git add \*.txt** : Adds all text files in current directory
- **git add "\*.text"** : Adds all txt file in the whole project
- **git add docs/\*.txt** : Adds all txt files in doc folder
- **git add -A** : add all files and ensures that the deletions are included
- **git commit -m 'Commit message'** : Stores the new version
  of our source code
- **git commit -am 'comment'** : auto remove deleted files from commit
- **git remote add origin <url>**
- **git push -u origin master** : Push your code to a local or remote repository

- **git rm <file name>** : removes files from disk and staging area
- **git rm -r <folder name>** : removes the entire folder
- **git merge <branch name>**

##Changes

- **git pull origin master**
- **git diff head** : checks the changes made from the last commit
- **git diff --staged** : shows us the changes that have been staged
- **git reset <file name>** : upstage a file
- **git checkout -- <file name>**: Gets rid all of the changes made since the last commit

##Branches

- **git branch <branch name>** : creates a new branch typically used to test a feature or fix a bug
- **git checkout <branch name>** : switches to that branch
- **git branch** : Shows our branches
- **git checkout -b <new_branch>** : creates and switches over to new branch
- **git branch -d <branch name>** : deletes branch
- **git branch -D <branch name>** : to forcefully delete a branch

##Notes

- When using get add, be careful not to use add all to include folders we don't want. Specify with the file name.
- **git log -- summary**: to see more information about each commit
- **git stash**: Sometimes when you go to pull you may have changes you don't want to commit just yet. One option you have, other than committing, is to stash the changes.
- **git stash apply** : to re-apply your changes after your pull.

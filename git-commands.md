Git Commands
============
A list of Git commands


&nbsp;
 

### Git Config 
| Description | Command |
| ------- | ----------- |
| Set user name | `git config user.name "[user name]" --global` | 
| Set user email | `git config user.email "[user email]" --global` | 
| Set an alias | `git config --global alias.[Alias name] [Command]`| 
| Unset an alias | `git config --global --unset alias.[Alias name]` | 
| Get list of aliases | `git config -l \| grep alias` | 
| Edit the global config options | `git config --global --edit` | 
| Store credentials on disk | `git config credential.helper store` | 
| Cache credentials | `git config --global credential.helper cache` | 
| Set a global gitignore | `git config --global core.excludesfile [File Path]` | 


&nbsp;


### Getting & Creating Projects

| Description | Command |
| ------- | ----------- |
| Initialize a local Git repository | `git init [folder name (optional)]` | 
| Create a local copy of a remote repository | `git clone ssh://git@github.com/[username]/[repository-name].git` | 



### Basic Snapshotting

| Description | Command |
| ------- | ----------- |
| Check status | `git status` | 
| Reset staging | `git reset` |
| Assign a version | `git tag [version name/number]` |
| Bring up a version | `git checkout [version name/number` |
| Add a file to the staging area | `git add [file-name.txt]` | 
| Adds all text files in current directory | `git add *.txt` | 
| Add all new and changed files to the staging area | `git add (-A) or (.)` | 
| Review and add chuncks to the staging area | `git add -p` | 
| Commit changes | `git commit -m "[commit message]"` | 
| Auto remove deleted files from commit | `git commit -am "[commit message]"` | 
| Removes file from disk and staging area | `git rm [file name.txt]` | 
| Remove a file (or folder) | `git rm -r [file-name.txt]` | 
| Remove everything from the repository | `git rm -r --cached .` | 


### Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git branch -D [branch name]` | Forcefully delete a branch |
| `git push origin --delete [branchName]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| Go back to last commit | `git checkout -- .` |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git checkout [commit id]` | Look out previous code (read only) |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |



### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote -v` | Get info about remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote rm [origin]` | Remove repository
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |



### Inspection & Comparison

| Description | Command |
| ------- | ----------- |
| View changes | `git log` | 
| View changes (detailed) | `git log --summary` | 
| Checks the changes made from the last commit | `git diff head` | 
| Check the changes that have been staged | `git diff --staged` | 
| Preview changes before merging | `git diff [source branch] [target branch}` |
| Shows one or more objects (blobs, trees, tags and commits) | `git show` |
| Shows a specific commit | `git show [commit id] [#f03c15]('asdasd')|



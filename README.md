# Git Commands

Git was developed by Lenus Torawalds to manage his project Linux.

## Configuration
*  **git config user.name "Name"-** Sets name for commits.
* **git config user.email "Email"**- Sets email for commits.
* **git config --list**- shows current configuration.

## Start a Repo
* **git init**- Initiaalize git in current folder
* **git clone "Link"**- Clones a repo from remote source.

## Workflow
* **git status**- shows status of working repo
* **git add "File Name"**- Stages a specific file for commit.
* **git add .**- Stages all files for commit.
* **git commit -m "Message"**- Commits stages foles with a message

## History
* **git log**= shows commit history.
* **git log --oneline**- oneline view of commit history.
* **git diff**- shows changes not yet staged,
* **git diff --staged**- shows changes that are staged.

## Branching and Merging
* **git branch**- shows all branches.
* **git branch "Branch name"**- Creates new branch.
* **git checkout "Branch name"**- Switch to the branch.
* **git checkout -n "Branch Name"**- Creates and switches to a branch.
* **git merge "Branch Name"**- Merges branch to current branch.

## Remote repo
* **git remote -v**- Show remote repo.
* **git remote add origin "Link"**- Adds a remote repository.
* **git fetch**- downloads remote repo.
* **git pull**- fetches and merges changes from remote.
* **git push**- pushes local commits to remote.
* **git push -u origin "Branch"**- Pushes and set branch to default upstream.

## Undoing
* **git chechout -- "File"**- Discard changes in file (unstages).
* **git reset "File"**- Unstages a stagges file.
* **git reset --hard**- Reset working directory and staging area to last commit.
* **git revert "Commit Id"- Creates a new commit taht undoes a specific commit.

## Stashing
* **git stash**- Temporaarily saves changes without committing.
* **git stash list**- shows stashed changes.
* **git stash apply**- applies the latest stash.
* **git stash pop**- Applies and removes the latest stash.

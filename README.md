# git-learning
### `git init` Git begining tracking changes made to the project.
### Three parts of a Git project:
  1. Working Directory. Where you'll be doing all the work.
  2. Staging Area. Where you'll list changes you make to the working directory.
  3. Repository. Where Git permanently stores those changes. 
  
### `git status`: checks the status of your changes.
### `git add file`: add a file to the staging area.
### `git diff filename`: check the differences between the working directory and the stage area. 
### A *commit* is a last step in a Git workflow. `git commit -m "Here is going message"`
### `git log`
### `git show HEAD`: show head
### `git checkout HEAD filename`: restore the file in your WD(working directory)as it did when you last made a commit.
### `git reset HEAD filename`: unstage file from the staging area (SA). This command *reset* the file in the SA to be the same as the `HEAD` commit. 
test row
### `git checkout filename`: restore the file as it did before you last stage the file
### `git rm filename`:remove file and stage changes.
### `git branch`: list branches.
### `git checkout <hash-commit>`: return to given commit. 
### `git branch <branch-name>`: create new branch.
### `git checkout <branch-name>`: switch to given branch.
### `git merge <branch-name>`: takes all changes from given branch and update the current branch.
### `git branch -m <origin-branch-name> <new-branch-name>` : rename branch.
### `git branch -D <branch-name>` : delete given branch.
### `git pull --progress "origin"`: get all changes.  
### `git merge origin/<branch-name>`:  merge given branch.
### `git checkout -B "<branch-name>" "origin/<branch-name>"` : switch remote branch


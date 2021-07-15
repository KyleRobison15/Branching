## Git Cheat Sheet
This is a brief reference for all the git commands.

* `git init` - Initialize a local git repo in a working directory
* `git branch -M main` - Change the name of my Master branch to main (only works if committed changes)
* `git add .` Stage current diretory in git index
* `git commit -m "message"` commit changes to git hub
* `git config-l`
* `git status` - Tracks and changes to repo
* `git log` - List commit history (gives you a shaw number)
* `git log --oneline` - Compact commit history (displays that commit's shaw number condensed)
* `git checkout *******` - Will move the HEAD to the commit you referenced

### Branching

The purpose of branching in GitHub is to isolate development work without affecting other branches in the repository.
So when we want to work on one specific feature or topic of our program, we can create a branch for that.
Then we can make all the changes we want to that specific part of the program and validate those changes before pulling to the main branch.
At the end of the day, the main branch is what GitHub displays when anyone visits the repository.

* `git branch` List branches. Shows the current branch with a splat
* `git branch newBranch` - Makes a new branch. ('git branch' + name of new branch you want to make)
* `git checkout newBranch` - Switched branches. ('git checkout' + name of branch you want to switch to)
* `git checkout -b otherBranch` - creates and switches to a new branch all at once

### Remote Repos
* `git remote add alias url` - add alias `alias` as name for remote repo `url` in
project configuration
* `git push alias aBranch` - push local commits to remote repo `alias`'s branch' `aBranch`
* `git pull alias aBranch` - pull remote `aBranch` from `alias` into current local branch


### Pushing commits in branches
* Merge conflicts occur when:

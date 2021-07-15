## Git Cheat Sheet

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
* `git branch` List branches. Shows the current branch with a splat
* `git branch newBranch` - Makes a new branch. ('git branch' + name of new branch you want to make)
* `git checkout newBranch` - Switched branches. ('git checkout' + name of branch you want to switch to)
* `git checkout -b otherBranch` - creates and switches to a new branch all at once

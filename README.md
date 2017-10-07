# GitCommands

### Initialisation ###

 - git init // initialise local repository
 - git add origin "www.github.com/example/example.git"
 - git pull origin master //pull all the data of default branch master in github repository

### After adding files to workspace ###

- git add -A // -A indicates add all files to index
- git commit -a -m "message" // commit since a file is created

### After changing existing files ###

- git commit -a -m "message"

### Adding branches and switching to them ###

- git branch branchname // create new branch
- git checkout branchname // switch to new branch from default master branch

### Merging branches ###

- git checkout master // switched to master branch to merge new branch to master
- git merge branchname //merge new branch to master

### Pushing ###

- git push origin master // to push branch master to github
- git push origin branchname // to push branch created branch to github

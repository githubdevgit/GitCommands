# GitCommands

1.git init // initialise local repository
2.git add origin "www.github.com/example/example.git"
3.git pull origin master //pull all the data of default branch master in github repository

#After adding files to workspace

4.git add -A // -A indicates add all files to index
5.git commit -a -m "message" // commit since a file is created

#After changing existing files

6.git commit -a -m "message"

#Adding branches and switching to them

7.git branch branchname // create new branch
8.git checkout branchname // switch to new branch from default master branch

#Merging branches

10.git checkout master // switched to master branch to merge new branch to master
11.git merge branchname //merge new branch to master

#Pushing

12.git push origin master // to push branch master to github
13.git push origin branchname // to push branch created branch to github
 

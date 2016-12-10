# GitPractice
This is for practicing with Git

## Creating a new branch workflow
###Retrieve all changes from github.com
* git checkout master
* git pull origin master


### Create a branch
* git branch (your branch name)
* git checkout (your branch name)


### Save your new branch to github.com
* git push
* git push --set-upstream origin (your branch name)


## Normal Daily Workflow
###Retrieve all changes from github.com into your branch
* git checkout master
* git pull origin master
* git checkout (your branch name)
* git merge master

(Do this anytime you need to get the updated changes)


### Make your changes
* Edit files
* git add .
* git commit
* ...


### Save your changes to github.com
* git push

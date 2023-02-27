# data210_git_basics

Hello this change was made on my local machine!

## Introduction
git =! GitHub

Git is a version control system which was available before GitHub

GitHub allows for distributed version control, rather than centralised

## Git commands:
* git status - check the status of our branch
* git add . - add the cwd to our local repository
* git commit -m "message" - package the changes we've made ready to push to GitHub
* git push -u origin main - push our changes to our repository (with specified branch)

Repository - a database which holds / changes of our files

## Git branches

Branches allow numerous people to work on a single project on different areas at the same time

As long as these changes don't conflict with one another

• git checkout -b <name> creates a new branch
• git push --set-upstream origin <name> ensures we are pushing to the right area / branch
• git push -u origin <name> push to branch on GitHub
• git checkout main - changes branch to main
• git branch - list branches
• git branch -a - list all branches

## Pull request

In GitHub I created a pull request so changes in branch could be merged

Then merged

Then git pull from local machine to bring down changes back to main branch

Probably pointless when on my own

Hello this change was made on GitHub!

Hello this change was made on the dev branch only!

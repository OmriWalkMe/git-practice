git-practice
============
Sign up for a GitHub account and then I can add you to this repository so you can mess around with it

clone a repository
```
git clone git@github.com:zhaol/git-practice.git
```

make changes by creating, modifying, or deleting files

stage your changes
```
git add .                 #add all of your changes
git add my_changed_file.c #add certain files
```

commit your changes
```
git commit -m 'add your commit message description'
```

push your changes to the remote repository
```
git push origin
```

fetch latest changes from remote repository
```
git fetch origin
```

bring your local master branch up to date with the remote master branch
```
git rebase origin/master
```

jump to a new branch
```
git checkout -b feature/new_branch 
```

make changes

stage and commit your changes
```
git add .
git commit -m 'your message'
```

checkout your master branch
```
git checkout master
```

merge changes from feature/new_branch into master
```
git merge feature/new_branch --no-ff
```

push to origin
```
git push origin
```

other git commands
==================
```
git status
git branch
git pull
git reset
git rebase
git log
git revert
git diff
```

git GUI clients
===============
Using a GUI client is the best way to visualize what's going on when starting out
http://git-scm.com/downloads/guis

git references
==============
https://www.atlassian.com/git/tutorial

http://nvie.com/posts/a-successful-git-branching-model/

[GIT Stage & Commit](https://docs.google.com/drawings/d/1xiTpqIep89EezF5F6ShygsVZPF_AwHuWA7QkZXB2XNE/pub?w=1179&h=367)

[GIT Source Management](https://docs.google.com/drawings/d/1T4Dp0Lk7a1fzQG3_eVBCdBB2I1udqjKwPRaa9WdhX-w/pub?w=2822&h=916)

[GIT Architecture](https://docs.google.com/drawings/d/1He1w1gT-_unXiK75ODtRSEc3qQJm4t1XoeonD5pAjXs/pub?w=1290&h=846)


# git references

## create repository
1. Create repository on GitHub with a new name
2. In local location where you want the folder use, do

* ``git init``


## add a change to git
* ``git add <filename>``
* ``git commit -m "comment on change added"``

## add change to github repo
* ``git push origin <main>``
** ``<main>`` is the branch name

## add a new remote to git repo
* ``git remote add <unique-remote-name> <remote-url>``
* from https://articles.assembla.com/en/articles/1136998-how-to-add-a-new-remote-to-your-git-repo#:~:text=To%20add%20a%20new%20remote%2C%20use%20the%20git%20remote%20add,tab%20of%20your%20Git%20repo

## origin and upstream differences on git with branches
* https://stackoverflow.com/questions/9257533/what-is-the-difference-between-origin-and-upstream-on-github

## editing .gitignore
* https://www.atlassian.com/git/tutorials/saving-changes/gitignore
* `echo file >> .gitignore`

## removing deleted file from `git status`
* https://stackoverflow.com/questions/12987907/git-how-to-commit-a-manually-deleted-file
* `git rm file`
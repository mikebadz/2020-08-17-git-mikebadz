# 2020-08-17

## Local

- `git status`: tells you what is going on in your repository
- `git add <FILE>`: places <FILE> into the staging area
	- `git add README.md`
-`git commit`: commits files in the staging area
	-if you opened this in VI(M): <ESC> `:q!`
	-git config --global.core editor

- `git log`: shows you your history
	`git log --oneline`: shows you your 1-line history
- `HEAD`: tells you where you are looking 

- `git diff`: shows you current state with last known state differences
- `git diff --staged`: shows difference from staging area with last known

## REMOTES
-`git remote add origin <URL>` adds <URL> with the name origin
-`git push origin master`: pushes the master branch to the origin remote
-`git pull origin master`"

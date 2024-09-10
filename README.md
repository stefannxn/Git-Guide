# Git-Guide

### initialize git bash
```c
git config --global user.name "Stefan Chen"
git config --global user.email grape25353@gmail.com
git config --global init.default branch main
```
### check
```c
git config -h
```
### more detail
```c
git help config
```
### refresh
```
clear
```
### initialize repository
```c
cd file.link
git init
```
view &rarr; show &rarr; hidden items &rarr; find .git
### track file
```c
git status
git add file.name

### untrack file
```c
git rm --cached file.name
```
### ignore files
1. create a new word document ".gitignore" in the file
2. open it in Notepad
`# ignore all .txt files`
`*.txt`
3. file &rarr; save
### track all files
```c
git add --all
```
### commit
```c
git commit -m "commit.name"
```
### change files and view differences
1. use Notepad for editing
2. save file
3. 
```c 
git status
```
4. 
```c
git add file.name
```
### not include file in commit
```c
git restore --staged file.name
```
### bypass staging and commit
```c
git commit -a -m "commit.name"
```
### remove and restore
```c
git rm "file.name"
git restore "file.name"
```
### rename 
```c
git mv "old.file.name" "new.file.name"
```
### commit history
```c
git log
```
or
```c
git log --oneline
```
### amend commit
```c
git commit -m "commit.name" --amend
```
### view changes in commits
```c
git log -p
```
or
```c
git help log
```
### reset to previous commit
```c
git reset commit.number
```
### rebase git repository
```c
git rebase -i --root
```
### create and commit branch 
```c
git branch branch.name
git switch branch.name
```
and use `git branch` to check
&rarr; change branch file in Notepad
```c
git commit -a -m "commit.name"
git switch main
```
### merge changes
```c
git merge -m "merge.name" branch.name
```
### delete branch
```c
git branch -d branch.name
```
### push to github
copy instructions 
use `git push --all` to push branches

### pull (fetch + merge)
```c
git pull
```
reference: [https://www.youtube.com/watch?v=tRZGeaHPoaw]

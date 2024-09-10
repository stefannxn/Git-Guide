# Git-Guide

### Initialize Git Bash
```c
git config --global user.name "Stefan Chen"
git config --global user.email grape25353@gmail.com
git config --global init.default branch main
```
### Check
```c
git config -h
```
### More Detail
```c
git help config
```
### Refresh
```
clear
```
### Initialize Repository
```c
cd file.link
git init
```
view &rarr; show &rarr; hidden items &rarr; find .git
### Track File
```c
git status
git add file.name
```
### Untrack File
```c
git rm --cached file.name
```
### Ignore File
1. create a new word document ".gitignore" in the file
2. open it in Notepad
`# ignore all .txt files`
`*.txt`
3. file &rarr; save
### Track All Files
```c
git add --all
```
### Commit
```c
git commit -m "commit.name"
```
### Change Files and View Differences
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
### Not Include File in Commit
```c
git restore --staged file.name
```
### Bypass Staging and Commit
```c
git commit -a -m "commit.name"
```
### Remove and Restore
```c
git rm "file.name"
git restore "file.name"
```
### Rename 
```c
git mv "old.file.name" "new.file.name"
```
### Commit History
```c
git log
```
or
```c
git log --oneline
```
### Amend Commit
```c
git commit -m "commit.name" --amend
```
### View Changes in Commits
```c
git log -p
```
or
```c
git help log
```
### Reset to Previous Commit
```c
git reset commit.number
```
### Rebase Git Repository
```c
git rebase -i --root
```
### Create and Commit Branch 
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
### Merge Changes
```c
git merge -m "merge.name" branch.name
```
### Delete Branch
```c
git branch -d branch.name
```
### Push to GitHub
copy instructions 
use `git push --all` to push branches

### Pull (Fetch + Merge)
```c
git pull
```
reference: [https://www.youtube.com/watch?v=tRZGeaHPoaw]

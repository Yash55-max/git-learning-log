# Git Toolkit

This file documents the Git undo and recovery tools I've learned.

git branch -  displays all the branches present in git repository
git checkout $branch-name - goes to specified branch if present
touch $filename - used for creating a file 


## Reset

- git reset --soft HEAD~1: undo last commit, keep changes staged
- git reset --mixed HEAD~1: undo last commit, keep changes in working directory (default)
- git reset --hard HEAD~1: undo last commit and discard all changes (dangerous!)
- Only use reset on commits that haven't been pushed
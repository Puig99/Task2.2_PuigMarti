# Git commands

We will now show the basic git commands you need to know how to use in order to work with it 

## git init
***

This creates a new local git repository (/.git)

## git clone
***

This command creates a copy of a remote repository 

The syntax is "git clone ``<url>``"

## git status
***
Generates a list of new files or modified

## git add
***
Takes a snapshot of the files and adds them to the index

Syntax: ``git add [-u] [filename].[pattern]``

The option [-u] add files that have to be deleted to the index

## git commit
***
Saves snapshots of the files permanently in the version history

Syntax: ``git commit [-m message]``

## git push
***
Loads all the staged files from the local branch to the remote repository

Syntax: ``git push origin master``

## git pull
***
Downloads and adds the changes from the remote repository to the local branch

Syntax: ``git pull origin master``
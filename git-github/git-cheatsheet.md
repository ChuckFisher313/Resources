# Git commands cheat sheet #

## Setup ##

`code` git config --global user.name "[firstname lastname]" `code`

Set a name that is identifiable for credit when reviewing version history. 

`code` git config --global user.email "[email@email.com]" `code`

## Setup & initialize project 

`code` git init `code` 

Initialize an existing directory as a Git repository. 

`code` git clone [url] `code`

Retrieve an entire repository from a hosted location via URL.

## Stage and snapshot ##

`code` git status `code`

Show modified files in working directory, staged for next commit. 

`code` git add [file] `code`
Add a file as it looks now to your next commit. 

`code` git add . `code` 
Add all files in working directory to your next commit. 

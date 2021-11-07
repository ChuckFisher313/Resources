# Git commands cheat sheet #

## Setup ##

` git config --global user.name "[firstname lastname]" `

Set a name that is identifiable for credit when reviewing version history. 

` git config --global user.email "[email@email.com]" `

## Setup & initialize project 

` git init ` 

Initialize an existing directory as a Git repository. 

` git clone [url] `

Retrieve an entire repository from a hosted location via URL.

## Stage and snapshot ##

` git status `

Show modified files in working directory, staged for next commit. 

` git add [file] `
Add a file as it looks now to your next commit. 

` git add . ` 
Add all files in working directory to your next commit. 

` git reset [file] `

Unstage a file while retaining the changes in working directory. 

` git diff ` 

Difference of what is changed but not staged. 

` git diff --staged ` 

Difference of what is staged but not yet committed. 

` git commit -m "[Descriptive message]" `

Commit your staged content as new commit, with added -m switch for including a message with your commit. 

## Branch and merge ##

` git branch ` 

List your brances. A * will appear next to the currently active branch. 

# Git commands cheat sheet #

These commands are taken directly from github education.

## Setup ##

` git config --global user.name "[firstname lastname]" `

Set a name that is identifiable for credit when reviewing version history.

` git config --global user.email "[email@email.com]" `

## Setup & initialize project ##

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

` git branch [branchname] `

Create a new branch at the current commit.

` git checkout `

Switch to another branch and check it out into your working directory.

` git merge [branc] `

Merge the specified branch's history into the current one.

` git log `

Show all commits in the current branch's history.

## Inspect and compare ##

` git log `

Show the commit history for the currently active branch.

` git log branchB..branchA `

Show the commits on branchA that are not on branchB.

` git log --follow [file] `

Show the commits that changed this file, even across renames.

` git diff branchB..branchA `

Show the difference of what is in branch A that is not in branch B.

` git show [SHA] `

Show any object in git in human-readable format.

## Tracking path changes ##

` git rm [file] `

Delete the file from project and stage the removal for commit.

` git mv [existing-path] [new-path] `

Change an existing file path and stage the move.

` git log --stat -M `

Show all commit logs with indication of any paths that moved.

## Share and update ##

These commands work, but were found elsewhere.

` git remote add origin master https://github.com/ChuckFisher313/Resources `

Adds a git URL as an alias. Tells git where to send your project when you push.

` git push origin master `

Push a project from local machine up to "origin" alias, which sends the project to github.

## Temporary commits ##

` git stash `

Save modified and staged changes.

` git stash list `

List stack-order of stashed file changes.

` git stash pop `

Write working from top of stash stack.

` git stash drop `

Discard the changes from top of stash stack.

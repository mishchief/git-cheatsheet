# git-cheatsheet
Just a cheatsheet for me while I get a hold of git commands

## **Cloning specific branch**

git clone -b **< branch >** --single-branch **< url >** [Additionally: --depth **< number of commits >**]


## **MAKE CHANGES**

Review edits and craft a commit transaction

$ git status

Lists all new or modified files to be committed

$git add [file]

Snapshots the file in preparation for versioning

$ git reset [file]

Unstages the file, but preserve its contents

$ git diff

Shows file differences not yet staged

$ git diff --staged

Shows file differences between staging and the last file version

$ git commit -m "[descriptive message]"

Records file snapshots permanently in version history

## **GROUP CHANGES**

Name a series of commits and combine completed efforts

$ git branch

Lists all local branches in the current repository

$ git branch [branch-name]

Creates a new branch

$ git checkout [branch-name]

Switches to the specified branch and updates the working directory

$ git merge [branch]

Combines the specified branch’s history into the current branch

$ git branch -d [branch-name]

Deletes the specified branch

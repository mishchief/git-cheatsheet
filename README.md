# git-cheatsheet
Just a cheatsheet for me while I get a hold of git commands

Cloning specific branch


git clone -b **< branch >** --single-branch **< url >** [Additionally: --depth **< number of commits >**]


MAKE CHANGES
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

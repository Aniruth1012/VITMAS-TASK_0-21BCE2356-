# VITMAS-TASK_0-21BCE2356-
Basic Git Commands
git config
This command sets the author name and email address respectively to be used with your commits.

git config –global user.name “[name]”

git config –global user.email “[email address]”

git init
This command is used to start a new repository.

git init [repository name]

git clone
This command is used to obtain a repository from an existing URL.

git clone [url]

git add
This command adds a file to the staging area.

git add [file]

This command adds one or more to the staging area.

git add * ####

git commit
This command records or snapshots the file permanently in the version history.

git commit -m “[ Type in the commit message]”

This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

git commit -a

git diff
This command shows the file differences which are not yet staged.

git diff

This command shows the differences between the files in the staging area and the latest version present.

git diff –staged

This command shows the differences between the two branches mentioned.

git diff [first branch] [second branch]

git push
This command sends the changes made on the master branch, to your remote repository.

git push -u origin master

git pull
This command will pull everything from the remote server onto your local repository.

git pull

git reset
This command unstages the file, but it preserves the file contents.

git reset [file]

This command undoes all the commits after the specified commit and preserves the changes locally.

git reset [commit]

This command discards all history and goes back to the specified commit.

git reset –hard [commit]

git status
This command lists all the files that have to be committed.

git status

git log
This command is used to check the commit history in a git repository.

git log

git rm
This command deletes the file from your working directory and stages the deletion.

git rm [file]

git remote
This command is used to connect your local repository to the remote server.

git remote add origin [remote server link]

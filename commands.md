# Commands
git config --global -e --> Edit our global configuration settings
git ls-files --> Files in staging area
git commit -am "commit message"/ git commit -a -m "commit message" --> Add files to staging area and commit them with a message
git status --> Shows the status of the project
git rm file_name *.txt --> Removes files from working directory as well as the staging area
git mv original_filename new_filename --> Renames a file and adds it to the staging area
git rm --cached -r fileOrfolder_name --> Remove file or directory from staging
git status -s --> Shorter git status
git diff --> What we have in the working directory vs what we have in the staging area
git diff --staged --> Changes that are going to happen in the next commit
git config --global diff.tool vscode --> Set a name to our default diff tool
git config --global difftool.vscode.cmd "code --wait --diff $LOCAL $REMOTE" --> Launch vscode
git log --> History of commits
git log --oneline --> History summary of the commits
git log --oneline --reverse --> Shows from top to bottom the first to last commit
git show commit_id --> View information of the specified commit. The ID doesn't have to be written completely if the others commits not start with the same characters.
git show HEAD --> View the last coomit
git show HEAD~NUMBER_VALUE --> Show the previous commit from the HEAD dependending on the "NUMBER_VALUE" value
git show HAED:.gitignore --> Show the content of the file from the specified commit
git ls-tree commit_id --> Shows all the files and directories of the commit
git --version --> Shows version of git.
git restores --staged file_name --> Changes from staging area switch to active directory for the specified file.
git restores git restore file_name -->Restore the file the their previous state.
git restore file_name --> Discard local changes.
git clean -fd --> Undo local changes
git restore --source=commit-id file_name --> Restore a file to a previous version.


# .gitignore
github.com/github/gitignore --> Templates for .gitignore file
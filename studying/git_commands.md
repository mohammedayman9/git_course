# Git Code Syntax :
-------------------

- You Type git then type the command.
- EX : git [command]

-----------------------------------

## Commands you'll use a lot :
- git help [command] : Opens the documentation of this command.
- git clone [repo_link] : Clones the repo into your drive.
- git status : Gives you the status of files in your git dir.
- git add [file_name | (*) To add all files] : Adds the file to the staging area from your working dir.
- git reset head [file_name] : Restore the file to your working dir.
- git commit -m 'Message contains what you have finished': Adds the file from the staging area to the local repo.
- git remote : Gives you the remote name of yours.
- git push [remote_name] [branch_name] : Adds the commited files to the remote repo.
- git pull [remote_name] : Pulls the new editions from the remote repo to your local repo.
- git config [-l | --list] : Gives you the available configs.
- git config --global [one_of_configurations] : Gives you the the value of this config.
- git config --global [one_of_configurations] ["value"] : Edits the value of this config.
- git config --global [one_of_configurations] --unset : Removes the value of this config.
- git config --global --edit : Opens the config file in the your text editor.
- git config --global alias.[nickname] [original_command] : Makes an alias name you can use for the command.
- git branch : Shows you your current existed branches.
- git branch [branch_name] : Makes a new branch for you.
- git checkout [branch_name] : Transfer you to this branch.
- git checkout -b [branch_name] : Makes a new branch then transfers you to this branch.
- git branch -d [branch_name] : Deletes the branch after checking that it has no edits or updates.
- git branch -D [branch_name] : Forces deleting the branch without checking on anything.
- git branch -m [new_branch_name] : Renames the current branch.
- git stash : Moves the files from the staging area to the stash.
- git stash list : Gives you the list of the files in the stash.
- git stash drop : Deletes a file from the stash.
- git stash clear : Deletes all the files in the stash.
- git restore --staged [file_name] : Restore the file from the staging area to your local repo.
- git clean -n : Gives you the files that would be deleted from your local repo.
- git clean -f : Deletes the files that ain't in the staging area or on the remote repo.
-----------------------------------
- git commands : https://www.freecodecamp.org/news/git-cheat-sheet/
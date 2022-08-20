# Git Code Syntax :
--------------------

- You Type git then type the command.
- EX : git [command]

------------------------------------

## Commands you'll use a lot :
-------------------------------

- git : Gives you all commands of git. 
- git help [command] : Opens the documentation of this command.

--

- git config [-l | --list] : Gives you the available configs.
- git config --global [one_of_configs] : Gives you the the value of this config.
- git config --global [one_of_configs] ["value"] : Edits the value of this config.
- git config --globa --unset [one_of_configs] : Removes the value of this config.
- git config --global --edit : Opens the config file in the your text editor.
- git config --global alias.[nickname] [original_command] : Makes an alias name you can use for the command.

--

- git init [repo_name]: Creates a new local Repository in the current working dir.
- git status : Gives you the status of files in your git dir.
- git clone [repo_link] : Clones a remote repo into your local repo.

--

- git add [file_name | (*) To add all files] : Adds the file to the staging area from your working dir.
- git add [file_name] -f : Adds the file to the staging area even it is in the ignored files.
- git restore --staged [file_name] : Restore the file from the staging area to your local repo.
- git reset head [file_name] : Restore the file to your working dir.
- git commit -m 'Message contains what you have finished': Adds the file from the staging area to the local repo.
- git log : Gives you the latest commits.
- git checkout [commit_id] : Moves the head to the commit with this id and removes the changes of next commits.
- git reset --hard [commit_id] : Moves the head pointer from the last commit to the commit you give its id and deletes the commits after it.
- git pull [remote_name] : Pulls the new editions from the remote repo to your local repo.
- git push [remote_name] [branch_name] : Adds the commited files to the remote repo.
- git push origin main --force : Updates the remoter repo with the deleted commits.

--

- git branch : Shows you your current existed branches.
- git branch [branch_name] : Makes a new branch for you.
- git branch -d [branch_name] : Deletes the branch after checking that it has no edits or updates.
- git branch -D [branch_name] : Forces deleting the branch without checking on anything.
- git branch -m [new_branch_name] : Renames the current branch.
- git merge [branch_name] : Merges the work of this branch and the master branch.

--

- git remote : Gives you the remote name of yours.
- git checkout [branch_name] : Transfer you to this branch.
- git checkout -b [branch_name] : Makes a new branch then transfers you to this branch.

--

- git stash : Moves the files from the staging area to the stash.
- git stash list : Gives you the list of the files in the stash.
- git stash drop : Deletes a file from the stash.
- git stash clear : Deletes all the files in the stash.

--

- git clean -n : Gives you the files that would be deleted from your local repo.
- git clean -f : Deletes the files that ain't in the staging area or on the remote repo.

--

- git tag [version_name] : Separates your projects on many tag to separate your project's version.
- git tag -a [version_name] -m "Write what's new in this version": Creates a new tag for already released project.
- git tag : Gives you a list of your tags.
- git tag -d : Deletes a tag from your local repo.
- git push origin --delete : Deletes a tag from the remote repo.

-------------------------------------
- git commands : https://www.freecodecamp.org/news/git-cheat-sheet/
-------------------------------------

### To Ignore Adding Some Files To The Remote Repo :
-----------------------------------------------------

- Make a file with extension .gitignore
- Put the files you need to ignore in.
- To ignore Files in a specific extension you can put *.ext
- To ignore a specific dir you can put dir_name/
- To ignore a specific file you can put file_name.ext

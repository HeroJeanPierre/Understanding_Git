Understanding Git
====================
This will be used to practice and understand git. 

Useful Commands
====================

git status - This will show the current status of the tracked and untracked files in your repo.

git add - This will add the designated files to the staging area, the place files go before they are commited

git commit - This allows you to commit the file, getting it ready to push
    -m allows you to put the message of the commit directly fintothe shell
       Short subject line all caps followed by a colon followed by a capitalized present tense verb followed by a message that briefly explains what the commit does.
       Ex. RUNTIME: Fix erros and add roslaunch file
    -am allows you to stage and commit files at the same time. NOTE: If the file is untracked (it wasn't yet added) it will not commit that file. Make sure all the files that you want to commit have been added to the staging area that you want aded before using -am

git log - shows information of the log history, very usefuly whe working with other devs.

git branch - After this you could type a branch name that you wanted to create and it put you into the branch
    -d this is the command to delete a branch node
    -b this is the command to turn a detached branch node into an attached one, just place the name of the branch after the -b

git checkout - This is the command used to change branches NOTE: If you checkout without commit changes to the current branch, the changes will be transfered to the branch you checkout to, that is why it is important to either commit all changes, or stash the changes (after all changed files are tracked) before changing branches.

git stash - This is the comnmand that allows you to store files in a branch that have not been commited.

git merge - This will allow you to merge a branch to a desired branch. NOTE: Merge conflicts may occur, so tools such as kdiff3 will help solve them.

git fetch - This will download the changes from the remote repo to a branch, but it will not merge them to the current repo.

git pull - Thie will downlod the changes stored in the repo and will merge them with the current repo




 

Concepts
====================

- Staging (adding)
This is the idea of adding a file in before you actually commit it to the repo. It is not used that much in reality, but is a nice thing to have when you do not want to change the current commit but are not finished tweaking a program.


- Committing
This is to be used when a part of code works completely and you are ready to commit the change to the repo. Should only be used when you are sure that something works properly.

- .gitignore
This is a file that other filenames are added to so that thosee files will be ignored when you are adding and commiting files

- Branches
This is the process of creating a seperate instance of the repo inorder to maintain the integrity of the master branch, while being able to mess around with something else, and it is a good idea to do this if you are changing something in a working piece of cade. It is like creating a backup and working on that, as to not mess up the working project.

- Merge and Merge Conflicts
This is the idea of taking a seperate branch and combining with a current branch. Though it is important to avoid merge conflicts. This is when a change from a seperate branch occurs in the same file on a line that was already changed and committed (if that makes sense).
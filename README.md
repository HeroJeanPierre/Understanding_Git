# Understanding_Git
This will be used to practice and understand git.

Useful Commands
====================

git status - This will show the current status of the tracked and untracked files in your repo.

git add - This will add the designated files to the staging area, the place files go before they are commited

git commit - This allows you to commit the file, getting it ready to push
    -m allows you to put the message of the commit directly fintothe shell
       Short subject line all caps followed by a colon followed by a capitalized present tense verb followed by a message that briefly explains what the commit does.
       Ex. RUNTIME: Fix erros and add roslaunch file
    -am allows you to stage and commit files at the same time.

git log - shows information of the log history, very usefuly whe working with other devs.


 

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

- Merge
# Terminal and Git Cheat Sheet (Week 1 Day 2)


## Terminal commands:

- ***`pwd`***: will show you which location you are currently in.

- ***`cd`***: change directory. This can take you to a folder if the name of another directory is added to the end of it. If `cd` is used by itself, it will take you to the home directory. (e.g cd documents).

- ***`.`***    : show the current directory.

- ***`. .`***  : shows the parent directory.

- ***`mkdir`***: creates a new directory. Add the name of the new directory after the command to name it. (Use underscores instead of spaces).
- ***`history`***: shows last 10,000 commands.
- ***`mv`***: will move file to another location. Add the name of the file that you wish to move. (e.g `mv cheat_sheet.txt`).
- ***`ls`*** = will list all folders and files in a directory.
- ***`ls -a`***: will list all folders/files in a directory including hidden files.
- ***`ls -l`***: will list all folders/files in a directory with their full details.
- ***`ls -al`***: will list all folders/files in a directory with full detail, including hidden files.
- ***`touch`***: will create a new file. Add file name and file type at the end (e.g `touch cheat_sheet.txt`).
- ***`rm`***: will delete a file. Add name of file at the end (e.g `rm cheat_sheet.txt`)
- ***`rm - rf`***: will delete entire directory, bypassing any warning prompts. Add directory name at the end (e.g `rm -rf cheat_sheet`)


## Git Commands:

- ***`git init`***: will initialize a new repository for Github.
- ***`git add`***: stage a file so that for can track it. (***`git add .`*** will track all files in the directory).
- ***`git commit`***: will commit the changes that are staged after invoking ***`git add`.*** (include `-m" "` to add a message describing the commit).
- ***`git push`***: this command will push any changes to the file located on your device to Github. 
- ***`git pull`***: this command will pull any changes to the repo and will apply them locally.
- ***`git status`***: checks which files have changes that are to be committed.
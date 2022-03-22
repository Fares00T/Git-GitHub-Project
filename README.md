# Git-GitHub-Project
GMC Git &amp; GitHub Project

1-Create a folder called learn_git_again.
mkdir learn_git_again

2-Cd (change directory) into the learn_git_again folder. 
cd learn_git_again

3-Create a file called third.txt.
touch third.txt

4-Initialize an empty git repository.
git init

4-Add third.txt to the staging area.
git add third.txt

5-Commit with the message "adding third.txt".
git commit -m "adding third.txt"

6-Check out your commit with git log.
git log

7-Create another file called fourth.txt.
touch fourth.txt

8-Add fourth.txt to the staging area.
git add fourth.txt

9-Commit with the message "adding fourth.txt"
git commit -m "adding fourth.txt"

10-Remove the third.txt file.
rm third.txt

11-Add this change to the staging area.
git add third.txt

12-Commit with the message "removing third.txt".
git commit -m "removing third.txt"

13-Check out your commits using git log.
git log

14-Change your global settings to core.pager=cat
git config --global core.pager "cat"

15-Write the command to list all of the global configurations for git on your machine. You can type git config
--global to find out how to do this

- git config --global --list



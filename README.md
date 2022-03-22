# Git-GitHub-Project
GMC Git &amp; GitHub Project

1-Create a folder called learn_git_again. <br />
mkdir learn_git_again
<br />
<br />
2-Cd (change directory) into the learn_git_again folder. <br />
cd learn_git_again
<br />
<br />
3-Create a file called third.txt.<br />
touch third.txt
<br />
<br />
4-Initialize an empty git repository.<br />
git init
<br />
<br />
4-Add third.txt to the staging area.<br />
git add third.txt
<br />
<br />
5-Commit with the message "adding third.txt".<br />
git commit -m "adding third.txt"
<br />
<br />
6-Check out your commit with git log.<br />
git log
<br />
<br />
7-Create another file called fourth.txt.<br />
touch fourth.txt
<br />
<br />
8-Add fourth.txt to the staging area.<br />
git add fourth.txt
<br />
<br />
9-Commit with the message "adding fourth.txt"<br />
git commit -m "adding fourth.txt"
<br />
<br />
10-Remove the third.txt file.<br />
rm third.txt
<br />
<br />
11-Add this change to the staging area.<br />
git add third.txt
<br />
<br />
12-Commit with the message "removing third.txt".<br />
git commit -m "removing third.txt"
<br />
<br />
13-Check out your commits using git log.<br />
git log
<br />
<br />
14-Change your global settings to core.pager=cat. <br />
git config --global core.pager "cat"
<br />
<br />
15-Write the command to list all of the global configurations for git on your machine. You can type git config
--global to find out how to do this<br />
- git config --global --list
<br />


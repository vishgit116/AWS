#git newwwwwwwwwwwwwwwwwwwwwwwwwwww


1. Create github account
2. Create repository(Project Name)
3. Open repository and click on clone/download - and copy url :
https://github.com/vishgit116/AWS.git

4. Download Git bash in local machine and Install
5. Create one folder in local machine
6. Open create folder and right click - you will see git bash here. 
7. Click on it. Terminal opens 
Note : Local means your machine > local repository/folder
Note : Remote/origin repository means > Github repository
-------------------------
    git config --global user.name "Your Name"
    git config --global user.email you@example.com

-------------------------
For the first name we need to initiate the local repository
>> git init

Now, we need to sync with remote repository with local repository;
setting up git connetion with git hub using url
>> git remote add origin "https://github.com/vishgit116/AWS.git"

Note : Master is the main repository
Note : pull means > we are download/pulling file from github (Remote) to local repository
Note : Push means > we are pusing/upload file to github (Remote) from local repository
Note : Branch means > folder/directory
Note : SVN is similar one as Git; but it is just different vendor.
-------
Pulling file from github (remote to local)
> git pull origin <foldername/branch>
eg: git pull origin master

Note : never pull one file, always try to pull all the files related to project.
------
Note : commit and push : used in pushing file from local to remote

Local to remote :
step:1
* Create a file in local repository and save the file
* Then "add" those files to the local repositoy
* Added files will be shown in the repository 
step:2
* then "Commit" those files to the git repository
step:3

check the status using > git status (un-added files will shows in "Red")

Adding files to local repository
> git add test.txt (if we add one file - use the name of the file)
> git add . (or) git add -A (if we want to add all the folder use ".")

check the status using > git status (Added files will shows in "Green")

Commit:
> git commit -m "this is my first file in local repository"

Note: check status : git status
Note: If you modify any commited file/added file - when u check for git status it shows as modified
Note: Create one file in local repository and check the status (git status)

commiting multiple files :

>git commit -a -m "adding multiple files"

check the status : 
>git status

To see the logs : 
>git log

Now, pushing files to remote repository.
step 1 : pull all the files from remote repository
>git push origin master
step 2 : now push; sometimes it will ask per the github password.
> git push origin master
-------------------------------

Branches :

* git branch -->> to know all the branches in git
* git branch vishnu -->> to creare new branch vishnu in git
* git branch -d vishnu -->> to delete branch name vishnu
* git branch -D vishnu -->> to delete forcefully
* git branch -m bairi -->> to rename vishnu branch to bairi
* git branch -a  -->> to see all the branches






 





# Git

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

For the first name we need to initiate the local repository
>> git init

Now, we need to sync with remote repository with local repository;
setting up git connetion with git hub using url
>> git remote add origin "https://github.com/vishgit116/AWS.git"

Note : Master is the main repository
Note : pull means > we are download/pulling file from github (Remote) to local repository
Note : Push means > we are pusing/upload file to github (Remote) from local repository
Note : Branch means > folder/directory

pulling file from github
> git pull origin <foldername/branch>
eg: git pull origin main

Note : never pull one file, always try to pull all the files related to project.

 





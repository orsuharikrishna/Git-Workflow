Main Branches:

Master Branch // Production branch
Develop Branch // Development/Integration branch -- should not touch Master branch

Supporting Branches:

Feature Branch // All enhancement should go to this branch
Release Branch // Once the enhancement is released after peer review and code review. This should used for QA Release
Hotfixes Branch // Any issue in production should branch from Master branch 

Note:

1. Master and Develop branch resides in Origin and developer machine.
2. Feature branches typically resides only in developer machine. 

Useful commands:

1. git branch -vv // list out your local branches with more information including what each branch is tracking and if your local branch is ahead, behind or both.

2. $ git push origin --delete serverfix // To delete remote branch

3. $ git branch --remotes // To see all remote tracking branches

4. $ git push --set-upstream origin development // To push remote branch to origin 


Command:

1. Initialize the new project

    1. git init // Create an empty Git repository or reinitialize an existing one -- It is safe to run this command on existing directory
    2. git commit --allow-empty -m "Initial commit" // --allow-empty overrides safety commit, since the origin and initilize should be same. 
    3. git checkout -b develop master // Create develop branch from master -- this 2 branches should exist always. 

2. Set the user name and user email property using config command

3. 
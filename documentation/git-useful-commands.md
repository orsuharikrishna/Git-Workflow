#### [Click here to readme](https://github.com/SarvM/git-work)


### Useful Git Commands 

1. git init

    * Create an empty Git repository or reinitialize an existing project
    * It is safe to run this command on existing directory
    
2. git commit --allow-empty -m "Initial commit"

    * Just to have initial commit to server before we create a *develop* branch
    * Option *--allow-empty* allow us to override safety commit because git won't allow us to commit without changes to the project
    
3. git checkout -b develop master

    * Create and checkout develop branch from master. 
    
4. git push origin develop

    * This command is used to push develop branch to remote *origin* for remote tracking. 
    
5. git status --short

    * This command is used to output the working status of the tree. 
    * --short is used to output the result in short format.

6. git clone *[url]*

    * If you need to collaborate with someone on a project, or if you want to get a copy of a project so you can look at or use the code, you will clone it. You simply run the git clone [url] command with the URL of the project you want to copy.
    
7. git log --oneline -2

    * This command is used to display the commits
    * The output can be altered by using sub commands. *--oneline* is used to display the output in single line. 
    * sub command *-2* is used to display last 2 commits.
    
8. logout

    * This command is used to exit the bash command line. 
    
9. git branch -d {the_local_branch}

    * To remove local branch from your machine.
    * Use -D instead to force deletion without checking merged status
    
10. git push origin --delete {the_remote_branch}

    * To remove remote branch from your server.


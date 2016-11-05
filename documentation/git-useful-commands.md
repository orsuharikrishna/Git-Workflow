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
    


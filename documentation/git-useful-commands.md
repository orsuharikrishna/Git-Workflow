### Useful Git Commands

1. [git init](#init)

    1. git branch -vv // list out your local branches with more information including what each branch is tracking and if your local branch is ahead, behind or both.

    2. $ git push origin --delete serverfix // To delete remote branch

    3. $ git branch --remotes // To see all remote tracking branches

    4. $ git push --set-upstream origin development // To push remote branch to origin

    5. $ git merge --abort // To roll back all merge operation.

    6. $ git pull origin feature/F100-login-signup // To update the feature branch. 


## init

```sh
git init
```

*It creates an empty Git repository or reinitialize an existing one
*It is safe to run this command on existing directory



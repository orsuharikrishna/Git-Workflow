## Git commands - Workflow

Below commands may be used to achieve the branching model explained in previous topic.

### Scenario

1. Below freelancers are working for an experimental project called 'pratice-git'

    * Developers: Lisa, Sophie and Rachel
    * Admin: Erika 

2. Below task is assigned to each of them:

    * Erika - Setup existing project in git, create *develop* branch
    * Lisa - Signup API -- api change; Enhancement Reference # IME02384
    * Sophie - Signup API -- to send email confirmation; New Feature Reference # F139823
    * Rachel - Fixing bug on login page; Bug Reference # BZ2948
    
3. Release Process - Tag this enhancement, feature and bug fix in single release with tag name v1.0.1


### Git commands

Please refer [git useful commands](https://github.com/SarvM/git-work/blob/master/documentation/git-useful-commands.md) for more details on below commands.

#### Initialize the project

This command is used by admin to initialize the project in server and setup *develop* branch. 

Note: This section is not required for developers.

```sh

$ git init 

$ git commit --allow-empty -m "Initial commit"

$ git checkout -b develop master

$ git push origin develop

```

    
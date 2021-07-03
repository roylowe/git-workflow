# git-workflow

## Common commands used in The Git Workflow

**git push origin feature/main-css --** used to push changes to branch named feature/main-css
**git remote -v --** can see the remotes URLs not just short name
**git checkout main --** checkout the branch to work on
**git branch --** list, create or delete branches
**git pull origin main --** make sure you have the most up to date content
**git show-branch --** shows all local branches
**git branch -D feature/main-css --** deletes the branch names feature/main-css
**git checkout develop --** checkout the branch you want to work on
**git pull origin develop --** pulls the most up to date content from the branch develop
**history --** shows the history of commands in your bash terminal
**git branch -a  --** lists both the remote tracking branches and the local branches
**git fetch --all  --** Run this command only if there are remote branches on the server which are untracked by your local branches.

## Using Git Hub workflow steps:

1. After you create your repo and are up and running on main
    create a branch for development
    **git checkout -b develop**
2. when ready to develop, create another branch for the feature
   **git checkout -b feature_name** 
3. checkout the feature_name branch
    **git checkout feature_name**
4. Write the code and commit regularly to feature_name branch
    **git add .**
    **git commit -m"commit message" origin feature_name**
5. push changes to feature_name branch
    **git push origin feature_name**
6. Go to github.com under pull requests
    a. do a new pull request
    b. set feture_name branch to push to develop branch
    c. click create pull request
    d. delete feature_name branch

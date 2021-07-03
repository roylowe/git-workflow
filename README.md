# git-workflow

## Common commands used in The Git Workflow

```
git push origin feature/main-css
git remote -v
git checkout main
git branch
git pull origin main
git show-branch
git branch -D feature/main-css
git checkout develop
git pull origin develop
history
git branch -a
git fetch --all


## Using Git Hub workflow steps:

1. After you create your repo and are up and running on main
    create a branch for development
    **git checkout -b develop**
2. when ready to develop create another branch for the feature
   **git checkout -b feature_name** 
3. Then checkout the feature_name branch
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



```

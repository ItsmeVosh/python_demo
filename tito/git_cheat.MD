# stashing

`git stash , git stash apply , git stash drop`

# gitignore not working

- git rm -r --cached node_modules
- git add / commit - push

# delete all commits

- git checkout --orphan latest_branch
- git add -A
- git commit -am "feat: initial commit"
- git branch -D main
- git branch -m main
- git push -f origin main

# handling remotes

- git config --get remote.origin.url
- git remote remove origin
- rm -rf .git

# setting email to git

- git config --global user.name "username"
- git config --global user.email "git email address"

# delete remote branch

- git branch -d localBranchName

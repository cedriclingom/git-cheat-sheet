# My git CheatSheet
## Branch notion

git checkout -b feature/add_branch_documentation --> create a new branch

git branch --> liste les branches

## Remote branch documentation
git remote -v --> to list the remotes for the current repository

git remote add origin https://github.com/avanade-talentagile/gitandsocialcoding.git --> to add the default remote to our local repository

git remote set-url origin https://github.com/avanade-talentagile/gitandsocialcoding-newname.git -->  change remote url (When a repo is moved or renamed, its URI changes)

git push --set-upstream origin features/1234-new-killing-feature --> To push the current branch and set the remote as upstream

git fetch --> is the base command to get an update of the default remote repository. It will update your repository reference folder (the .git folder) but not content (your content): your local files will remain unchanged.


Test locked branch 3

## Pull request
gh pr create --base main --head features/1234-new-killing-feature --title '[#1] Initialize repo' --body 'More details on the PR that solves issue #1' --> create a PR

gh pr create --help --> To get more details on the capabilities of the gh pr create

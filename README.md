# ADVANCED JAVA

# GIT WORKFLOW

- To create a new branch use `git branch <name of branch>`
- To switch to the new branch `git checkout <name of branch>`
- After adding and committing the changes, it is then pushed to remote branch using `git push origin <name of branch>`
- To merge changes to main branch, do the following!

1. Make sure to checkout to main branch using `git checkout main`
2. Merge the changes in the new branch to main using `git merge <name of branch>`

- Delete a branch locally using `git branch -d <name of branch>`
- Delete branch remotely using `git push origin --delete <name of branch>`
- Move a saved commit to test branch `git checkout -b test <commit hash>`

# Tutorial link:
https://www.youtube.com/watch?v=RGOj5yH7evk&ab_channel=freeCodeCamp.org
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

# Add - Commit - Push 
- git add .
    -> stage changes in the working directory to the Git index (staging area) before committing them
- git commit -m "description"
    -> save changes to a Git repository by creating a new commit that records the current state of the repository. 
    -> Commits serve as snapshots of the repository and allow you to revert back to a previous state if necessary.
- git push origin main
    -> upload local changes to a remote repository

# Status
- git status

# Branch commands
- git branch
    -> list branches, current
- git checkout -b branch_name
    -> create a branch "branch_name"
- git checkout branch_name
    -> switch to branch "branch_name"
- git diff other_branch_name
    -> show what changes have been made (current branch vs other brand)

# Pull request
-> on github.com create merge pull request and then merge 
- git pull origin main  
    -> pull merged main branch
- git branch -d "branch_name"
    -> delete branch that was merged to main on github

# Merge main (edited by other users) keep your branch up-to-date
-> locally you should not merge branch into main, but you may want to update your branch with a main (as other users may change it)
- git merge main
    -> merge to keep your branch up to date with what is going in master
    -> after mergining you should add and commit 
-> git commit -am 

# Undoing
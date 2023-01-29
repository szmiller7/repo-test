# Add
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


# Git Commands

Git is a powerful version control system, and knowing the essential commands is crucial for managing projects efficiently.  
Here is a collection of the most commonly used Git commands, explained in a simple way.

## Starting a Repository

git init                  # Create a new local Git repository
git clone <url>           # Copy an existing repository from remote to your machine

## Tracking Changes

git status                 # See which files have been modified, staged, or untracked
git add file_name          # Stage a specific file for commit
git add .                  # Stage all changes in the repository
git commit -m "Message"    # Commit staged changes with a descriptive message

## Working with Remote Repositories

git push origin main       # Push local commits to the remote repository on GitHub
git pull origin main       # Fetch and merge changes from the remote repository
git fetch                  # Download updates from the remote without merging

## Undoing Changes

git checkout file_name     # Discard changes in a specific file
git reset --soft HEAD~1    # Undo last commit but keep changes staged
git reset --hard HEAD~1    # Undo last commit and remove all changes

## Branching and Merging

git branch                 # List all branches in the repository
git branch branch_name     # Create a new branch
git checkout branch_name   # Switch to a different branch
git checkout -b new_branch # Create a new branch and switch to it
git merge branch_name      # Merge changes from another branch into the current branch
git branch -d branch_name  # Delete a branch that is no longer needed

## Viewing History and Differences

git log                    # View commit history
git log --oneline          # View commit history in a compact format
git diff                   # Show differences between working files and last commit
git diff branch_name       # Compare current branch with another branch


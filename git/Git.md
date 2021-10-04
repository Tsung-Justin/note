# Git

## Initial
```zsh
# Copy the remote repository file to the local end.
git clone [Repository URL]

# Create a new local Repository.
git init

# Add the specified file (or folder) to version control.
# Use "git add ." all can be add.
git add [file or folder]

# Check the status of local file changes.
git status

# Submit (commit) the current transaction.
git commit

# Submit (commit) the current transaction and set summary description text through the -m parameter.
git commit -m "[message]"

# Publish the commit of the local repository to the remote end.
git push

# Publish to the remote designated branch.
git push origin [branch_name]
```

## Branch
```zsh
# View the branch.
git branch

# Create the branch.
git branch [branch_name]

# Force delete the specified branch. (You need to switch to another branch before deleting.)
git branch -D [branch_name]

# Modify the branch name,
git branch -m [old_branch_name] [new_branch_name]

# Switch to the specified branch.
git checkout [branch_name]

# Create and switch to the specified branch.
git checkout -b [branch_name]

# Switch to the specified commit. (Same as git checkout [branch_name].)
git checkout [hash]
```

## Something
```zsh
# Get the dirty state of the current working directory, and save it to a stack of unfinished changes, so that it can be restored to the original state at any time.
git stash

# View the previous commit record.
git log

# Force recovery the specified commit. (Through the Hash value.)
git reset --hard [hash]
```

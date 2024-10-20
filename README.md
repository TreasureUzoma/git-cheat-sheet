# GIT Cheat Sheet

### Repository

```bash
git init     # Initialize a new git repo
git clone <repo-url>  # Clone a repo from it’s url
```

### Basics

```bash
git status     # Show changes status
git add <file> # Add changes to staging
git commit -m "message"  # Commit changes with message
git log                  # View commit history

```

### Branching

```bash
git branch     # List Branches
git branch <branch-name>    # Create a new branch
git checkout <branch-name>  # Merge changes from a branch
git branch -d <branch-name> # Delete a branch
```

## Remote Repositories

```bash
git remote        # List remotes
git remote  add <name> <url>      # Add a remote
git push <remote> <branch>  # Push changes to a remote 
git pull <remote> <branch>  # Pull changes from a remote 
```

### Undoing Changes 

```bash
git pull  # Fetch and merge changes 
git fetch # Fetch changes without merging 
git reset --hard HEAD    # Discard Changes
git revert <commit-hash> # Revert changes in a commit
```

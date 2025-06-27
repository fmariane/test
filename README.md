# Git Cheat Sheet – Essential Commands
### Setup
`git config --global user.name "Your Name"`
`git config --global user.email "you@example.com"`

### Create a Repository From local
Navigate to the folder you want to turn into a git repo
`git init`

### Get a Repository

`git clone <repo-url>`      # Copy a repo to your local machine

### Make Changes

`git status`                # See what’s changed
`git add <file>`           # Stage a file
`git add .`                 # Stage all changes
`git commit -m "message"`   # Save a snapshot

### Branching

`git branch`               # List branches
`git branch <name>`         # Create a new branch
`git checkout <name>`       # Switch branches
`git checkout -b <name>`    # Create and switch

### Update & Share

`git pull`                  # Get changes from remote
`git push`                  # Upload changes to remote

### Merge & Rebase

`git merge <branch>`        # Merge into current branch
`git rebase <branch>`       # Rebase onto another branch

### Undo Things

`git reset --soft HEAD~1`   # Undo last commit (keep changes staged)
`git reset --hard HEAD~1`   # Undo last commit (discard changes)
`git checkout -- <file>`    # Discard changes in a file

### History & Logs

`git log`                   # Show commit history
`git log --oneline --graph` # Compact, visual history
`git diff`                  # Show unstaged changes
`git diff --staged`         # Show staged changes

### Life-Saving Tools

`git stash`                 # Save changes temporarily
`git reflog`                # Recover lost commits

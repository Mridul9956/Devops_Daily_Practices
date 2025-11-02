git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list        # View git config
git commit -m "message"             # Commit staged changes
git commit -am "message"            # Add & commit tracked files in one go
git log                             # View commit history
git log --oneline                   # Short log
git show <commit_id>                # Show details of a commit
git branch                         # List all branches
git branch <branch_name>            # Create new branch
git checkout <branch_name>          # Switch to branch
git checkout -b <branch_name>       # Create + switch
git merge <branch_name>             # Merge a branch into current
git branch -d <branch_name>         # Delete branch


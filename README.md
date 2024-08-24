entails the git commands 
vConfiguration
git config --global user.name "Your Name": Set the name for commits.
git config --global user.email "you@example.com": Set the email for commits.
git config --list: List all Git configuration settings.
Repository Initialization and Cloning
git init: Initialize a new Git repository.
git clone [url]: Clone a repository from a URL.
Basic Snapshot Commands
git add [file]: Add a file to the staging area.
git add .: Add all changes in the current directory to the staging area.
git commit -m "message": Commit staged changes with a message.
git status: Show the working directory and staging area status.
git diff: Show changes between commits, commit and working tree, etc.
git log: Show the commit history.
git reset [file]: Unstage a file while retaining its changes.
Branching and Merging
git branch: List all branches.
git branch [branch-name]: Create a new branch.
git checkout [branch-name]: Switch to a branch.
git checkout -b [branch-name]: Create and switch to a new branch.
git merge [branch-name]: Merge a branch into the current branch.
git branch -d [branch-name]: Delete a branch.
Remote Repositories
git remote add [name] [url]: Add a new remote repository.
git remote -v: List all remote repositories.
git fetch [remote]: Fetch changes from a remote repository.
git pull [remote] [branch]: Fetch and merge changes from a remote repository.
git push [remote] [branch]: Push changes to a remote repository.
Tagging
git tag: List all tags.
git tag [tag-name]: Create a new tag.
git tag -d [tag-name]: Delete a tag.
git push [remote] [tag-name]: Push a tag to a remote repository.
Undoing Changes
git checkout -- [file]: Discard changes in the working directory.
git revert [commit]: Revert a specific commit by creating a new commit.
git reset --hard [commit]: Reset the working directory and index to a specific commit.
Stashing
git stash: Stash changes in a dirty working directory.
git stash apply: Apply the most recent stash.
git stash pop: Apply the most recent stash and remove it from the stash list.
git stash list: List all stashes.
Working with Remotes
git remote remove [name]: Remove a remote repository.
git remote rename [old-name] [new-name]: Rename a remote repository.
Rebasing
git rebase [branch]: Reapply commits on top of another base tip.
git rebase -i [commit]: Interactive rebase to edit, squash, or reword commits.
Configuration and Info
git config --global -e: Open the global configuration file in an editor.
git help [command]: Get help for a specific command.
git version: Display the installed version of Git.
Miscellaneous
git archive: Create an archive of files from a specific commit.
git bisect: Use binary search to find the commit that introduced a bug.
git cherry-pick [commit]: Apply the changes from a specific commit to the current branch.

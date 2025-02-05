 # GitAndGIthub         
          
Git Cheat Sheet     
    
Basic Commands  
 
  - git init: Initialize a new Git repository in the current directory.
  - git clone : Clone an existing Git repository from a remote URL.
  - git add : Stage changes in a file to be committed.
  - git commit -m : Commit staged changes with a descriptive message.
  - git push: Push committed changes to a remote repository.
  - git pull: Fetch and merge changes from a remote repository.

Branching

  - git branch : Create a new branch.
  - git checkout : Switch to a specific branch.
  - git merge : Merge changes from another branch into the current branch.
  - git branch -d : Delete a branch after merging it.

Viewing and Diffing

  - git status: Show the current state of the repository, including unstaged changes and branches.
  - git log: View the commit history of a repository.
  - git diff: Compare the current state of a file or the working directory with a previous version.

Remotes

  - git remote add  : Add a new remote repository with a given name and URL.
  - git remote remove : Remove a remote repository.
  - git fetch : Fetch changes from a remote repository without merging them.

Advanced Commands

  - git rebase : Rebase changes from another branch onto the current branch without creating a merge commit.
  - git stash: Temporarily save unstaged changes aside.
  - git restore: Restore previously stashed changes.
  - git cherry-pick : Pick a specific commit from another branch and apply it to the current branch.
  - git tag: Create, delete, or list tags to mark specific commits.

Troubleshooting

  - git reset --hard: Reset the working directory to a specific commit.
  - git revert : Undo the changes made in a specific commit.
  - git clean: Remove untracked files from the working directory.

Resources

  - Git Documentation: [[URL git documentation ON git documentation ON
  - Pro Git Book: [[URL pro git book ON pro git book ON
  - Git Cheat Sheet: [[URL git cheat sheet ON GitHub - GitHub]]([URL git cheat sheet ON GitHub - GitHub])

Additional Tips

  - Use descriptive commit messages.
  - Branch frequently for isolated development.
  - Keep your local repository up-to-date with remote changes.
  - Use tags for important releases.
  - Review and merge pull requests carefully before accepting them.
  - Utilize interactive rebasing for carefully reordering commits.
  - Use the .gitignore file to exclude files or directories from being tracked by Git.

# How to use `git`
1. Initialize a repository with git init: This command initializes a new Git repository in your current directory.
2. Stage your files with git add <file>: Use this command to stage specific files or directories for the next commit. You can also use git add . to stage all changes.
3. Whenever you make a substantial change, put it into the history with git commit -m "Commit  message": This command records the staged changes to the repository along with a descriptive message.
4. See your history with git log: This displays a list of commits in reverse chronological order, showing commit hashes, authors, dates, and commit messages.
5. Move around (history and branches!) with git checkout <commit/branch>: This allows you to navigate through commits or switch between branches in your repository.
6. Create new branches with git branch <branch-name>: This creates a new branch at the current commit.
7. To collaborate, first git fetch others' changes, then git merge theirs into yours: Use git fetch to retrieve changes from the remote repository, and then use git merge to integrate those changes into your local branch. Alternatively, you can use git pull to fetch and merge changes in one step.
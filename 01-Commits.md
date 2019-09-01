# Git Commits
> The core of git functionality.

## What are commits?
Commits are similar to bookmarks in a book. You can go back to an old commit in the "commit history" or forward to a new one; and every new commit has all of the old ones behind it.

## Creating a commit
Before you create a commit, you have to "add" the files you want to commit. To do this, do `git add [files]` with as many files as you're trying to add. You can also do `git add .` or `git add -a` to add all files that have been changed since the last commit. To commit those changes, do `git commit -m "<commit message>`. Your commit message should be brief and informational, not just "changes". Any unadded files won't get added to the commit.

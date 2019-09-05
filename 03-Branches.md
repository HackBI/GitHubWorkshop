# Branches
> Manage big projects.

## What are branches?
Branches split off from the main branch "master" and have a seperate commit history from it. Later, the changes in the branch can be "merged" back into master, so master's commit history matches that of the branch.
![Image from microsoft docs: https://docs.microsoft.com/en-us/azure/devops/learn/_img/history-abcd-cool-new-feature-e-f-merge-1.png](https://docs.microsoft.com/en-us/azure/devops/learn/_img/history-abcd-cool-new-feature-e-f-merge-1.png) image from https://docs.microsoft.com

## Why are branches useful?
Branches allow for multitasking in a project or adding to a project without affecting the people using it during development (when things tend to break). Also, branches allow you to keep the commit history clean and brief.

## Creating a branch
To create a branch and switch to it, type `git checkout -b <branch_name>`. You can name the branch whatever you like. To switch between branches, type `git checkout <branch_name>`. Now that you've got a branch, type `git branch` to make sure you're on the new branch you just created. Notice that there's two branches: the one you created and "master". The "master" branch is the default branch; and should be where the working / main version goes.

## Make changes and put them on GitHub
Now, make some changes. Change a file that already exists, add a new file, even delete a file. Once you've done that, `git add` and `git commit` your files, and finally, `git push` them. If you're pushing changes from a branch GitHub doesn't know exists, you'll get an error message which will tell you to type `git push --set-upstream origin <branch_name>`.

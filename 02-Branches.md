# Git Branches
> Manage big projects.

## What are branches?
Branches split off from the main branch "master" and have a seperate commit history from it. Later, the changes in the branch can be "merged" back into master, so master's commit history matches that of the branch.
![Image from microsoft docs: https://docs.microsoft.com/en-us/azure/devops/learn/_img/history-abcd-cool-new-feature-e-f-merge-1.png](https://docs.microsoft.com/en-us/azure/devops/learn/_img/history-abcd-cool-new-feature-e-f-merge-1.png) image from https://docs.microsoft.com

## Why are branches useful?
Branches allow for multitasking in a project or adding to a project without affecting the people using it during development (when things tend to break). Also, branches allow you to keep the commit history clean and brief.

## Merging branches
From the git documentation:
>Assume the following history exists and the current branch is "master":
>
>	        A---B---C topic
>          /
>     D---E---F---G master
>Then `git merge topic` will replay the changes made on the topic branch since it diverged from master (i.e., E) until its current commit (C) on top of master, and record the result in a new commit along with the names of the two parent commits and a log message from the user describing the changes.

However, branches can be merged through GitHub with a Pull Request, which is the preferred way to do it in almost all situations to prevent merge conflicts.

## Merge Conflicts
If you try to merge two branches that have conflicting commit histories, you get what's called a "merge conflict". This can happen if a file is changed in both branches, or if another commit has been pushed to the target branch since the two branches split. When this happens, git allows you to "resolve" the conflicts. For more information on how to resolve conflicts, see https://help.github.com/en/articles/resolving-a-merge-conflict-using-the-command-line.

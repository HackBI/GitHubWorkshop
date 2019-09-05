# More Info

## Merging branches
From the git documentation:
>Assume the following history exists and the current branch is "master":
>
>	        A---B---C topic
>          /
>     D---E---F---G master
>Then `git merge topic` will replay the changes made on the topic branch since it diverged from master (i.e., E) until its current commit (C) on top of master, and record the result in a new commit along with the names of the two parent commits and a log message from the user describing the changes.

However, branches can be merged through GitHub with a Pull Request, which is the preferred way to do it in almost all situations to prevent merge conflicts.

### Merge Conflicts
If you try to merge two branches that have conflicting commit histories or `git pull` when the remote branch has changed, you get what's called a "merge conflict". This can happen if a file is changed in both branches, or if another commit has been pushed to the target branch since the two branches split. When this happens, git allows you to "resolve" the conflicts. For more information on how to resolve conflicts, see https://help.github.com/en/articles/resolving-a-merge-conflict-using-the-command-line.
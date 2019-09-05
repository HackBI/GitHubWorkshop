# Add, Commit, Push
> Tell git what files to commit, commit them, and put them on GitHub.

## What are commits?
Commits are the core functionality of git. A good way to think of a commit is like a bookmark; like a bookmark, a commit saves your place in your work. A commit is like hitting "Save", with the major difference being that git tracks all previous commits. This way, you can jump back to a previous commit if you screw things up or need to see how it used to work.

## Add files to a commit
Before you commit your files, you must add them. Git tracks your changes, but it doesn't add anything to a commit unless you explicitly tell it to. You do this with the `git add [files]` command.

### Add files to your repo
Before we commit, let's add a file to our repo to put it on GitHub. Add any file to your repository: an empty text file, a picture from your desktop, anything (though I suggest something small so you don't have to wait for it to upload). You can even change the README.md file if you don't want to add files.

Now that you've added a file to your repository, you should add it to the commit. To do this, go to Terminal or git bash and type `git add <name_of_file>`. If you added multiple files, you can add their names to the end of each commit.

## Commit your changes
To commit your changes, run `git commit -m "<message>"`. Normally, your message should be brief and informational (not just "added files" or "changes"), but in this case anything will do.

## Push your changes to GitHub
Now that your changes are in a commit, upload or "push" it to GitHub by running `git push`. This will update the repository on GitHub with your changes to the commit history.

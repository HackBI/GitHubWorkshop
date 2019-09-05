# Good git Practices
> There's no "wrong way", but there's definitely a "preffered way".

While git does allow you to make as many commits as you want, have useless commit messages, and `git merge` as much as you want, there's a better way of doing things.

## Don't `git merge`
`git merge` is the command line command for making two branches into one. However, using `git merge` can cause a lot more problems than it solves. For one, you can create merge conflicts that are a huge pain to remove. For another, `git merge` doesn't always work exactly how you expect it to. In general, it's not hard to avoid if you use Pull Requests.

## Tell a story with your commit messages
Good commit messages go a long way. They allow anyone who is looking at your project in the future an easy way to go back and see the history of development on the project, and they mean that you can easily jump back to a specific point in development history if things break or you find compatibility issues. Avoid useless commit messages like "changes" or "added files", describe briefly what you changed. A good way of doing this is to make changes / add features in separate branches, and merging them in with a PR. If you follow the next tip, this will give you a very, very clean commit history.

## Keep PRs to one commit
Wherever possible, you should keep Pull Requests to one commit. This doesn't mean you can't have multiple commits along the way, it just means that before you create your Pull Request you should `git rebase` your commit history. Check out this great tutorial https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase for more information.

## Have a nice README file
This one should be pretty self-explanatory. READMEs are the main thing people look at on your project's GitHub page (if you haven't already, check out this workshop's page at https://github.com/hackbi/githubworkshop). Nobody knows as much about your project as you, so try to keep that in mind when writing your README file. It doesn't have to contain all of your documentation, but "Installation", "Getting Started" and "More Info" section are quite useful.

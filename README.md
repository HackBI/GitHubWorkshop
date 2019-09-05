# HackBI Example Workshop
> Learn about git repositories, commits, branches, and the GitHub platform.

## Get Started
Create a GitHub account at https://github.com, and install git (see https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). If you're on a mac, you might already have it installed; try opening a terminal and typing `git`. On Windows, make sure you install git bash when installing git; this workshop assumes you're using bash. 

## Uses
Git is a form of VCS, or Version Control Software, which is used to manage versions of projects. It has tools that allow you to go back in your code to previously commit version. It is the most common VCS in recent years. GitHub is a git provider, meaning it hosts repositories. It allows for more collaborative work on projects using git, such as Pull Requests, which allow you to review, propose, and request changes to other people's code.

## Purpose
This workshop will cover git repositories, commits, branches, and touch on good git practices. It will cover GitHub Pull Requests.

## Goal
Create a repository, make changes, and put them on GitHub. Make a new branch and merge the changes with a PR.

## Challenges
1. Create a repo on GitHub and clone it to your computer
2. Make changes, commit, and push them to GitHub
3. Create a new branch, make changes, push them to GitHub, and create a PR to merge them in.

## Git Cheat Sheet
* `git clone <url>` - clones a repository from a remote location to your computer.
* `git add [files]` - stages a file or files to be added to the next commit. Use `git add -a` or `git add .` to add all changes.
* `git commit -m "<message>"` - create a commit with a message.
* `git pull` - pull changes from the remote host (in our case, GitHub).
* `git push` - push changes to the remote host.
* `git checkout <branch name>` - switch to a branch. Use `git checkout -b <branch name>` to create a branch before checking out.

## Resources for Further Learning
* git documentation - https://git-scm.com/docs
* GitHub Guides - https://guides.github.com/
* Atlassian git tutorials - https://www.atlassian.com/git/tutorials
    * While these tutorials use Bitbucket (a GitHub alternative), they are super useful for anyone looking to learn more on git.

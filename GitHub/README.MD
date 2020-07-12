# GIT-Setup
Install GIT for the OS(Windows/Mac/Linux) | https://git-scm.com/downloads

## For setting up the existing local repository with existing GIT repository
Go to your local repository folder in Command Terminal and execute the following for setup

- git init
- git add .
- git commit -m "<some message>"
- git remote add origin <remote_git_repository_url>
- git remote -v
-  git push origin master
    - Error shall appear due to conflicts
- git pull <remote_git_repository_url> (or) git pull <remote_git_repository_url> --allow-unrelated-histories
    - Conflicts may appear as both repositories are individually developed
    - Conflicts could be resolved by opening the file and merging changes using the IDE comparer tool
- git add .
- git commit -m "<some message>"
- git push origin master
- Forcing to push local to remote (during merge conflicts): git push -f origin master

## For setting up the existing local repository with existing GIT repository
- git clone <remote_git_repository_url>
- IDE shall provide all features

## Change username and email global

- git config --global user.name "Nanhe Kumar"
- git config --global user.email "info@nanhekumar.com"

## Change username and email for current repo
- git config  user.name "Nanhe Kumar"
- git config  user.email "info@nanhekumar.com"

## Package to switch accounts in GIT
- https://github.com/paul-hanneforth/GitManager

## GIT Architeture
- https://stackoverflow.com/questions/2745076/what-are-the-differences-between-git-commit-and-git-push#answer-2745097

## References
- https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet
- https://www.siteground.com/tutorials/git/commands.htm
- http://kbroman.org/github_tutorial/pages/init.html
- https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/

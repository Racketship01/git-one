# GIT

## What is **GIT**?

- system that records changes to our files overtime
- recally specific version of thos files at any given time
- can easily collaborate on a project and have own version of project files on computer

## Why use **GIT**?

- store revision in a project in just one directory
- rewind to any revision in the project
- work on new featurers without messing the main codebase
- easily collaborate with other programmers

# GITHUB

- online service that hosts project
- share our codde with other developers
- developers can download project and work on them
- can re-upload edits and merge then with the main codebase

![](./img/github.png)

### Collaborate with GITHUB

> command : git push https://github.com/imeldabumanlag/git-one.git [to push from local project to github]

> command : git push https://github.com/imeldabumanlag/git-one.git master [to push from local project to github / add branch want to push]

> command : git remote add origin https://github.com/imeldabumanlag/git-one.git [github repos make origin in bash]

> command : git remote -v (fetch and origin)

> command : git clone https://github.com/imeldabumanlag/crap-portfolio.git [clone from github to local]

## Repositories

- is a container for a project want to track with Git (e.g website)
- can have many different repos for many different projects on computer
- lika a project folder which Git tracks the contents

## Commits

![](./img/commit.png)

| Modified                   | Staging                                              | Committed                                                    |
| -------------------------- | ---------------------------------------------------- | ------------------------------------------------------------ |
| changed filesnot committed | add any changed files to staging that want to commit | any files staging area are added to the commit when make one |

### Undoing Things

> **checkout commit** - navigate between branches created by git branch
> command : git checkout (log)

> **Revert commit** - undo a particular commit, almost delete out of the commit change. is a forward-moving undo operation that offers a safe method of undoing changes. Instead of deleting or orphaning commits in the commit history, a revert will create a new commit that inverses the changes specified.
> command : git revert (log)

> **Reset commit** - permanently take you back in time to a particular commit (permanently delete all codes)
> commannd : git reset (log)
> command : git reset (log) --hard [delete specific code in the code editor

## Branches

- massive part of git
- when creating repo creating a master branch
- master branch respresents stable ver of codes

![](./img/branch.png)

> command : git branch (name new branch)

> command : git checkout (name new branch) to switch to the new branch

> command : git branch -a [list of branches]

> command : git branch -d (name of branch to delete) (work once merge the branch)

> command : git branch -D (name of branch to delete) (work when not merge the branch)

> command : git checkout -b (name of new branch) [shortcut to create branch and switching]

### Merging Branches (& conflicts)

> command : git merge (name of the branch want to merge in the master branch)

## Forking

- can fork repository to own GitHub
- wanted to contributte to some kind of open source project

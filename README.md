# Git guide
Git guide for initiate on this awesome world.

# Git has an amazing documentation

### Introduction
- Git is distributed version control software. Version control is a way to save changes over time without overwriting previous versions. Being distributed means that every developer working with a Git repository has a copy of that entire repository - every commit, every branch, every file. If you're used to working with centralized version control systems, this is a big difference!
- [Reference](https://github.com/git-guides)

### Install
#### Checking for Git
 To see if you already have Git installed, open up your terminal application.

- If you're on a Mac, look for a command prompt application called "Terminal".
- If you're on a Windows machine, open the windows command prompt or "Git Bash".


Once you've opened your terminal application, type git version. The output will either tell you which version of Git is installed, or it will alert you that git is an unknown command. If it's an unknown command, read further and find out how to install Git.

- If thats not works, see this [Link](https://github.com/git-guides/install-git)

### Init a git project
#### How to Use git init

Common usages and options for git init
- git init: Transform the current directory into a Git repository
- git init <directory>: Transform a directory in the current path into a Git repository
- git init --bare: Create a new bare repository (a repository to be used as a remote repository only, that won't contain active development)
  
You can see all of the options with git init in [link](https://github.com/git-guides/git-init).
  
### Clone a project
#### How to Use git clone

Common usages and options for git clone
- git clone [url]: Clone (download) a repository that already exists on GitHub, including all of the files, branches, and commits.

You can see all of the options with git clone in [link](https://github.com/git-guides/git-clone).

### Git add
#### How to Use git add
- git add [filename] selects that file, and moves it to the staging area, marking it for inclusion in the next commit. You can select all files, a directory, specific files, or even specific parts of a file for staging and commit.

You can see all of the options with git add in [link](https://github.com/git-guides/git-add)
  
### Git commit
#### How to Use git commit
- git commit creates a commit, which is like a snapshot of your repository. These commits are snapshots of your entire repository at specific times. You should make new commits often, based around logical units of change. Over time, commits should tell a story of the history of your repository and how it came to be the way that it currently is. Commits include lots of metadata in addition to the contents and message, like the author, timestamp, and more.

You can see all of the options with git commit in [link](https://github.com/git-guides/git-commit)
  
### Git remote
#### What is remote?
- git remote manages the set of remotes that you are tracking with your local repository.
#### What is origin?
- If you try running git remote -v in your repositories, you'll probably see something called origin. You may notice origin in many messages from Git. origin is the human-friendly name for the URL that the remote repository is stored at. It's like a key value pair, and origin is the default.
  
You can see all of the options with git remote in [link](https://github.com/git-guides/git-remote)
  

### Git status
#### What does git status?
- git status shows the current state of your Git working directory and staging area.

You can see all of the options with git status in [link](https://github.com/git-guides/git-status)
  
### Git pull
#### What does git pull?
- git pull updates your current local working branch, and all of the remote tracking branches. It's a good idea to run git pull regularly on the branches you are working on locally.
#### Common usages and options for git pull
- git pull: Update your local working branch with commits from the remote, and update all remote tracking branches.
- git pull --rebase: Update your local working branch with commits from the remote, but rewrite history so any local commits occur after all new commits coming from the remote, avoiding a merge commit.
- git pull --force: This option allows you to force a fetch of a specific remote tracking branch when using the <refspec> option that would otherwise not be fetched due to conflicts. To force Git to overwrite your current branch to match the remote tracking branch, read below about using git reset.
- git pull --all: Fetch all remotes - this is handy if you are working on a fork or in another use case with multiple remotes.
  
You can see all of the options with git pull in [link](https://github.com/git-guides/git-pull)
  
### Git push
#### What does git push?
 - git push uploads all local branch commits to the corresponding remote branch.
#### What Does git push Do?
- git push updates the remote branch with local commits. It is one of the four commands in Git that prompts interaction with the remote repository. You can also think of git push as update or publish.

By default, git push only updates the corresponding branch on the remote. So, if you are checked out to the main branch when you execute git push, then only the main branch will be updated. It's always a good idea to use git status to see what branch you are on before pushing to the remote.
  
You can see all of the options with git push in [link](https://github.com/git-guides/git-push)

### Some useful links
[Hackerrank](https://www.hackerrank.com/domains/sql)
[Sql practice](https://www.sql-practice.com/)
[W3Schools](https://www.w3schools.com/sql/sql_exercises.asp)

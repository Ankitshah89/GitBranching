## Git Branching

### Overview

 Overview and cheat sheet of Git commands. Introduction to Branching.

### Basic Commands

* 'git init' - Initialize Git in working directory
* 'git add .' - Stage local working directory for commit
* 'git commit -m message' - Commit staged files to local repo
* 'git status' - Show status of repository
* 'git rm --cached fileName' - Remove fileName from commit index
* 'git log' - Show commit history
* 'git log --oneline' - Show commit history (compact)

###  Basic Branching
* 'git remote add origin remoteRepoUrl' - Link local repo to 'remoteRepoUrl'
* 'git pull origin master' - Pull 'master' branch content from remote origin into current local Branching
* 'git push origin master' - Push current local branch to 'master' branch of remote origin
* 'git remote show origin' - To Sow the Git URL

###  Remote Repository Commands
* 'git branch' - List local branches, highlight checked-out branches
* 'git branch branchName' - Create branch 'branchName'
* 'git checkout branchName' - Move to branch 'branchName'
* 'git push origin branchName' - Push local branch 'branchName' to origin

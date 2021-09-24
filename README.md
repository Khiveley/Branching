## Git Branching Practice and Cheat Sheet

Summary and cheat sheet of git commands, and practice Branching

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Basic commands

* `git init` - initialize a local git repo in current folder

* `git add .` - stage current changes for commit

* `git commit -m "Message"` - commint staged changes to local repo


### Informational commands

* `git status` -show status of working folder and repo

* `git log` - show log of commits

* `git log --oneline` - compact commit history

### Branching commands
`git branch` - list local braches, shows which branch we are on

`git branch -M branchName` - rename current branch to `branchName`

`git branch newBranch` - create local branch `newBranch`

`git checkout newBranch` - go to branch

### Remote commands

* `git remote add origin someRemoteRepoUrl` - link local repo with remote `someRemoteRepoUrl`

* `git push origin main` - push local commits to remote branch Informational

* `git push origin branchName` - push to remote branch `branchName`

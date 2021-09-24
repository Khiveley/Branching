## Git Branching Practice and Cheat Sheet

Summary and cheat sheet of git commands, and practice Branching

Text added in main branch. Blah Blah Blah.

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

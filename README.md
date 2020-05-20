## Git Cheat Sheet

### Information commands
* `git status`        -Status of current git repo
* `git config -l`     - List configuration of repo
* `git config --list` - same as above
* `git log`           - Log of commits in this repo
* `git log --oneline` - Compact log listing
* `git branch` - Display branch information

### Basic commands

* `git init` - Initialize a repo in a current working directory
* `git add .` - Stage current directory for commits
* `git commit -m` - Commit staged data with a message
* `git commit` - Commit staged data, enter message in vi editor

### Branching commands

* `git branch branchName` - Create branch "branchName"
* `git checkout branchName` - Go to branch "branchName"
* `git checkout -b branchName` - Create and checkout "branchName"

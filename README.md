# The ultimate git cheatsheet !!

## The only git hub commands you are gonna need

## Git basic commands

| Command                        | Description                                                                                                         |
|:-------------------------------|:------------------------------------------------------------------------------------------------------------------|
| `git add <filename>` | This command is used to stage changes in a specific file.|
| `git add .` | This command is used to stage changes in all file at once.|
| `git commit -m <message>` | This command commit all changes.|
| `git commit -am <message>` | This command is stage and commit in one go.|

## Git branching commands
| Command                        | Description                                                                                                         |
|:-------------------------------|:------------------------------------------------------------------------------------------------------------------|
| `git branch` | This command lists all branch of the current repository.|
| `git branch <branchname>` | This command creates an new branch|
| `git commit -d <branchname>` | This command delete a branch you provided.|
| `git commit -D <branchname>` | This command delete a branch you provided even if it's not merged.|
| `git branch -m <new-name>` | This command rename the current branch you are on.|
| `git checkout <branchname>` | This command switch to the branch you provided.|
| `git checkout -b <branchname>` | This command create and switch to the created branch on one go.|
| `git switch <branchname>` |  This command switch to the branch you provided.|
| `git switch -c <branchname>` | This command create and switch to the created branch on one go.|
| `git merge <branchname>` | This command merge the changes into the current branch from the branch you provided.|

## Git log

| Command                        | Description                                                                                                         |
|:-------------------------------|:------------------------------------------------------------------------------------------------------------------|
| `git log` | Log all the commit history of an branch.|
| `git log --oneline` | Log all the commit history of an branch but in oneline i.e only last six char of commit hash and commit message|





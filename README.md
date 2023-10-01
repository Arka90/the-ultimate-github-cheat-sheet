# The Ultimate GitHub Cheatsheet !!

## The Only GitHub Commands You're Gonna Need

## Git Basic Commands

| Command                   | Description                                                  |
|:--------------------------:|:-----------------------------------------------------------|
| `git add <filename>`       | This command is used to stage changes in a specific file.    |
| `git add .`                | This command is used to stage changes in all files at once.  |
| `git commit -m <message>`  | This command commits all changes.                            |
| `git commit -am <message>` | This command stages and commits in one go.                   |

## Git Branching Commands
| Command                       | Description                                                  |
|:------------------------------:|:-----------------------------------------------------------|
| `git branch`                  | This command lists all branches of the current repository.  |
| `git branch <branchname>`     | This command creates a new branch.                           |
| `git branch -d <branchname>`  | This command deletes a branch you provided.                  |
| `git branch -D <branchname>`  | This command deletes a branch you provided even if it's not merged. |
| `git branch -m <new-name>`    | This command renames the current branch you are on.         |
| `git checkout <branchname>`   | This command switches to the branch you provided.           |
| `git checkout -b <branchname>`| This command creates and switches to the created branch in one go. |
| `git switch <branchname>`     | This command switches to the branch you provided.           |
| `git switch -c <branchname>`  | This command creates and switches to the created branch in one go. |
| `git merge <branchname>`      | This command merges the changes into the current branch from the branch you provided. |

## Git Log
| Command                       | Description                                                  |
|:------------------------------:|:-----------------------------------------------------------|
| `git log`                     | Logs all the commit history of a branch.                    |
| `git log --oneline`           | Logs all the commit history of a branch but in one line, i.e., only the last six characters of the commit hash and the commit message. |

## Git Stash
| Command                       | Description                                                  |
|:------------------------------:|:-----------------------------------------------------------|
| `git stash`                   | Save changes before moving to another branch without committing. |
| `git stash pop`               | This command applies the changes that are in the stash and removes them from the stash. |
| `git stash apply`             | This command applies the changes that are in the stash but keeps the changes as well. |
| `git stash list`              | Lists all changes that are in the stash.                     |
| `git stash apply @{n}`        | Apply the nth stash.                                         |
| `git stash drop <stashname>`  | Delete a particular stash.                                   |

## Undoing changes
| Command                       | Description                                                  |
|:------------------------------:|:-----------------------------------------------------------|
| `git checkout HEAD~n`                   | move to n commit back from HEAD. |
| `git checkout <commit-hash>`            | move to that commit hash. |
| `git switch -`                          | move to the branch you are on before going back to a particular branch. |
| `git reset <commit-hash>`               | delete that commit history but keep the changes. |
| `git reset --hard <commit-hash>`        | delete that commit history and changes. |
| `git revert <commit-hash>`              | delete that commit history and changes. |

## git config
| Command                       | Description                                                  |
|:------------------------------:|:-----------------------------------------------------------|
| `git config --global user.email <"your_email@example.com">` | Add your mail address globally to the system |
| `git config --global user.name <"your_username">` | Add your user name globally to the system |

## Git remote
| Command                       | Description                                                  |
|:------------------------------:|:-----------------------------------------------------------|
| `git remote -v` | Show all remote repos connected with |
| `git remote add <name> <url>` | connect to a remote repo |

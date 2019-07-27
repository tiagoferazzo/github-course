# Github
Arquivo da aula de Git e GitHub para iniciantes

Tiaguera Ferazzo aprendendo git testezera

Getting & Creating Projects:
| Comando  | Descrição |
| git init | Initialize a local Git repository |
| git clone ssh://git@github.com/[username]/[repository-name].git | Create a local copy of a remote repository |

Basic Snapshotting:

| Comando | Descrição |
| git status | Check status |
| git add | Add a file to the staging area |
| git add -A | Add all new and changed files to the staging area |
| git commit -m | Commit changes |
| git rm -r [file-name.txt] | Remove a file (or folder) |

Branching & Merging:

| Comando | Descrição |
| git branch | List branches (the asterisk denotes the current branch) |
| git branch -a | List all branches (local and remote) |
| git branch [branch name] | Create a new branch |
| git branch -d [branch name] | Delete a branch |
| git push origin --delete [branch name] | Delete a remote branch |
| git checkout -b [branch name] | Create a new branch and switch to it |
| git checkout -b [branch name] origin/[branch name] | Clone a remote branch and switch to it |
| git checkout [branch name] | Switch to a branch |
| git checkout - | Switch to the branch last checked out |
| git chechout -- [file-name.txt] | Discard changes to a file |
| git merge [branch name] | Merge a branch into the active branch |
| git merge [source branch] [target branch] | Merge a branch into a target branch |
| git stash | Stash changes in a dirty working directory |
| git stash clear | Remove all stashed entries |

Sharing & Updating Projects:

| Comando | Descrição |
| git push origin [branch name] | Push a branch to your remote repository |
| git push -u origin [branch name] | Push changes to remote repository (and remember the branch) |
| git push | Push changes to remote repository (remembered branch) |
| git push origin --delete [branch name] | Delete a remote branch |
| git pull | Update local repository to the newest commit |
| git pull origin [branch name] | Pull changes from remote repository |
| git remote add origin ssh://git@github.com/[username]/[repository-name].git | Add a remote repository |
| git remote set-url origin ssh://git@github.com/[username]/[repository-name].git | Set a repository's origin branch to SSH |

Inspection & Comparison:

| Comando | Descrição |
| git log | View changes |
| git log --summary | View changes (detailed) |
|git diff [source branch][target branch] | Preview changes before merging |


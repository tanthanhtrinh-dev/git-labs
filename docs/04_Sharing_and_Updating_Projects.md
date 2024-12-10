### Sharing & Updating Projects

| Command                                                                            | Description                                                 |
|------------------------------------------------------------------------------------|-------------------------------------------------------------|
| `git push origin [branch name]`                                                    | Push a branch to your remote repository                     |
| `git push -u origin [branch name]`                                                 | Push changes to remote repository (and remember the branch) |
| `git push`                                                                         | Push changes to remote repository (remembered branch)       |
| `git push origin --delete [branch name]`                                           | Delete a remote branch                                      |
| `git pull`                                                                         | Update local repository to the newest commit                |
| `git pull origin [branch name]`                                                    | Pull changes from remote repository                         |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git`      | Add a remote repository                                     |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git`  | Set a repository's origin branch to SSH                     |

## Example
```shell
git remote set-url origin https://github.com/tanthanhtrinh-dev/dotnet-labs.git
```
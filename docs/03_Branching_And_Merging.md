### Branching & Merging

| Command                                               | Description|
| ----------------------------------------------------- | ----------------------------------------------------------------------------- |
| `git branch`                                          | List branches (the asterisk denotes the current branch)|
| `git branch -a`                                       | List all branches (local and remote)|
| `git branch -r`                                       | List all branches remote |
| `git branch [branch name]`                            | Create a new branch|
| `git branch -d [branch name]`                         | Delete a branch|
| `git push origin --delete [branch name]`              | Delete a remote branch|
| `git checkout -b [branch name]`                       | Create a new branch and switch to it|
| `git checkout -b [branch name] origin/[remote branch name]`  | Clone a remote branch and switch to it|
| `git branch -m [old branch name] [new branch name]`   | Rename a local branch|
| `git checkout [branch name]`                          | Switch to a branch|
| `git checkout -`                                      | Switch to the branch last checked out|
| `git checkout -- [file-name.txt]`                     | Discard changes to a file|
| `git merge [branch name]`                             | Merge a branch into the active branch|
| `git merge [source branch] [target branch]`           | Merge a branch into a target branch|
| `git stash`                                           | Stash changes in a dirty working directory|
| `git stash clear`                                     | Remove all stashed entries|
| `git pull origin master --allow-unrelated-histories`  | The “fatal: refusing to merge unrelated histories” Git error [REF](https://www.educative.io/answers/the-fatal-refusing-to-merge-unrelated-histories-git-error) |
| `git merge origin master --allow-unrelated-histories` | The “fatal: refusing to merge unrelated histories” Git error [REF](https://www.educative.io/answers/the-fatal-refusing-to-merge-unrelated-histories-git-error) |
| `git branch -m oldbranch newbranch`                   | Change branch name by new one|

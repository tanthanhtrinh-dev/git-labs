**List branches (the asterisk denotes the current branch)**
`git branch`

**Delete a remote**
```shell
git branch -D -r origin/[remote-branch]; git push origin --delete [remote-branch]
```

**Push and set defaul remote branch**
```shell
git push --set-upstream [remove-name] [local-branch]:[remote-branch];
```
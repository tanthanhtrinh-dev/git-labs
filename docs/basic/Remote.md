# Remote in Git

**Adding remote into repo**
```ssh
git remote add [remote-local-name] ssh://git@github.com/[username]/[repository-name].git
```

**Push and set stream**
```ssh
git push --set-upstream [remote-name] [local-branch]:[remote-branch];
```
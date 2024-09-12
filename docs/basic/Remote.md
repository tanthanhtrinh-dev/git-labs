# Remote in Git

**Adding remote into repo**
```bash
git remote add [remote-local-name] ssh://git@github.com/[username]/[repository-name].git
```

**Push and set stream**
```bash
git push --set-upstream [remote-name] [local-branch]:[remote-branch];
```

```bash
git push --set-upstream origin tantrinh/feature/suggest-delivery-info
```

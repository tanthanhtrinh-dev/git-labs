# Snippets Github

1. Push source code to repository quickly when the branch's final setting
```shell
git pull; git add .; git commit -m "[Message content]"; git push;
```

1. Push source code to repository with other remote branch and non set-upstream
    - Syntax
    - `git push -u [remote-name] [local-branch]:[remote-branch]`
    - 
    ```shell
    git pull; git add .; git commit -m "Empty message content"; git push -u [remote-name] [local-branch]:[remote-branch];
    ```
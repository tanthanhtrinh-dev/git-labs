# Deleting your git commit history without removing repo on Github/Bitbucket

1. Step 1
```shell
cd myrepo; rm -rf .git;
```
2. Step 2
```shell
git init; git add .; git commit -m "Removed history, due to sensitive data";
```
3. Step 3
```shell
git remote add origin github.com:yourhandle/yourrepo.git; git push -u --force origin main;
```   
4. 
# Deleting your git commit history without removing repo on Github/Bitbucket

[Source](https://www.willandskill.se/sv/articles/deleting-your-git-commit-history-without-removing-repo-on-github-bitbucket)
1. Step 1 - Remove old git version
```shell
cd myrepo; rm -rf .git;
```
2. Step 2 - Init Repo for new repo
```shell
git init; git add .; git commit -m "Removed history, due to sensitive data";
```
3. Step 3 - 
```shell
git remote add origin github.com:yourhandle/yourrepo.git; git push -u --force origin main;
```   
4. Step 4 - Tips shell usual
```shell
git add .; git commit -m "Comment something"; git push -u --force origin main;
```
6. 
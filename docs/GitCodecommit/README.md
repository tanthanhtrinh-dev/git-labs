# Git common Shell

### Git Init
```shell
git init; 
git add .; 
git commit -m 'Initial commit';
git remote add origin [url_repo_to_remote];
git push --mirror --force;
```


### Git Init Option
```shell
# Clone the project, e.g. `myproject` is my project repository:
git clone https://github.com/tanthanhtrinh-dev/aws-learning.git

# Since all of the commits history are in the `.git` folder, we have to remove it:
cd myproject

# And delete the `.git` folder:
git rm -rf .git

# Now, re-initialize the repository:
git init
git remote add origin https://github.com/tanthanhtrinh-dev/aws-learning.git
git remote -v

# Add all the files and commit the changes:
git add --all
git commit -am "Initial commit"

# Force push update to the master branch of our project repository:
git push -f origin master
```

**Git Commit**
```shell
git pull; git add .; git commit -m "Updating document for aws-learning";
```

**Git Commit And Push**
```shell
git pull; git add .; git commit -m "Fixing document for aws-learning"; git push -f;
```

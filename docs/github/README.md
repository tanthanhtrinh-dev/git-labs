**Setup**

 1. **Setup From Github**
    1. Create repo on github and then clone from the url github
       ```shell
       git clone https://github.com/tanthanhtrinh-dev/[name-of-repo].git
       ```
    2. 

 2. **Setup From localhost and then add remote**
    1. Create git from localhost
       ```shell
       git init 
       ```
    2. Adding the repo to remote
       1. origin remote
        ```shell
        git remote add origin https://github.com/tanthanhtrinh-dev/[repository-name].git
        ```
        2. Ading other remote
        ```shell
        git remote add codecommit https://github.com/tanthanhtrinh-dev/[repository-name].git
        ```
    3. **Git Push Remote**
       1. **Git Push Origin Remote**
       ```
       git push -v --set-upstream origin feature/task_local:feature/task_remote
       ```
       3. **Git Push CodeCommit Remote**
        ```
        git push -v --set-upstream CodeCommit feature/task_local:feature/task_remote
        ```
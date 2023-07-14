### Global Git Configuration
| Command                                 | Description                                                  |
|-----------------------------------------|--------------------------------------------------------------|
| `git config -–global –list`             | command is used to display the list of configurations.       |
| `git config --list --show-origin`       | You can view all of your settings and where they are coming. |
| `git config -–global –get user.name`    | command can be utilized.                                     |
| `git config -–global –get user.email`   | command is used to view the user email.                      |
| `git config -–global credential.helper` | command is used to show the credentials.                     |

### Setting Git Configuration
| Command                                               | Description                                                  |
|-------------------------------------------------------|--------------------------------------------------------------|
| `git config --global user.name "Tan Trinh"`           | To set your user name and email address. |
| `git config --global user.email tantrinh@tpfgroup.cc` | To set your user name and email address. |

### Getting & Creating Projects
| Command                                                           | Description                                |
|-------------------------------------------------------------------|--------------------------------------------|
| `git init`                                                        | Initialize a local Git repository          |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### Create .gitignore
| Command             | Description                                    |
|---------------------|------------------------------------------------|
| `touch .gitignore`  | Go to the root of your local git and create it |
| *.log               | Ignore any files with the .log extension       |
| temp/               | Ignore ALL files in ANY directory named temp   |
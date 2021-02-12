# git-commands
List of handy git commands for efficient and fast way of working

### Setup
Configuring user information used across all local repositories

| Command      | Description | 
| :---        |    :----   |
| `git config --global user.name "Name"`    |  configure global author name for all your commits      |
| `git config --global user.email "email"`    |  configure global email for all your commits        |
| `git config user.name "Name"`    |  configure repo only author name for all your commits  |
| `git config user.email "email"`    |  configure repo only email for all your commits        |

### Setup & Init
Configuring user information, initializing and cloning 

| Command      | Description | 
| :---        |    :----   |
| `git init`     |  initiliaze an existing directory as Git repo        |
| `git clone [url]`     |  retreive an entire repo from a hosted URL          |


### Staging

| Command      | Description | 
| :---        |    :----   |
| `git add .`    |  Stage all modified/deleted files, ignoring the untracked files       |


### Committing 

| Command      | Description | 
| :---        |    :----   |
| `git commit -m "Commit message`   |  commit changes to head (not yet to the remote repo       |
| `git push`   |  send changes to the main branch of your remote repo        |
| `git status`   |  list the files you've changed and those you still need to add or commit        |


### Branches

| Command      | Description | 
| :---        |    :----   |
| `git branch`  |  list all your branches         |
| `git checkout [branch-name]`   |  to switch from one branch to another          |
| `git checkout -b [branch-name]`   |  create a new branch and switch to it         |
| `git checkout -d [branch-name]`  |   - delete the branch          |

### Merging
If you want to merge to main, please do `git checkout main` and then merge

| Command      | Description | 
| :---        |    :----   |
| `git merge [branch-name]`  |  merge [branch-name] to current branch         |
| `git merge --squash [branch-name]`   |  merge [branch-name] into another as a single commit        |

### Update from remote repo
| Command      | Description | 
| :---        |    :----   |
| `git pull`   |  list all your branches         |
| `git checkout [branch-name]`   |  to switch from one branch to another  , `git pull` is shorthand for `git fetch` followed by `git merge FETCH_HEAD`         |
| `git-fetch`   |  download objects and refs from another repository           | 

### Tags

| Command      | Description | 
| :---        |    :----   |
| `git tag`  |  list all the tags          |
| `git tag -a v1.0.0 <commitID> -m 1.0.0`    |   tag a commit           |
| `git tag -d v1.0.0`    |   delete a tag           |


### Resources
[Github](https://education.github.com/git-cheat-sheet-education.pdf)  
[Git](https://git-scm.com/)  
[OhSGit](https://ohshitgit.com/)  


# Git Commands




## Install Git

1. See [Install Git](./README.md#1-install-git) in README




## Configure Git


1. See [Configure Git](./README.md#2-configure-git) in README



2. Other configuration commands

<!-- https://stackoverflow.com/a/46986031/441878 -->
```bash
# Show settings and location of all Git config files (system, global, local)
git config --list --show-origin
```



## Using Git


1. Basic version control workflow

```bash
# Get the current status of the repository
git status

# Stage all the changed files
git add .

# Create a commit
git commit -m "Adds all the files"

# Do some more work and repeat...
```


2. Comparing files

```bash
# Show changes in files 
git diff

# Show changes in specific files
git diff [filename]

# Show history of commits
git log
```



3. Fetch, pull, and push

```bash
# Get information about updates on the remote repository
git fetch

# Download the updates from the remote repo
git pull

# <after you have made edits to your local>

# Push your commits to the remote repo
git push
```




## Git Collaboration


1. Git Branches

```bash
# See your current branch
git status

# Create a branch
git branch [branch-name]

# Switch to a branch and update the files in the working directory
git switch -c [branch-name]

```
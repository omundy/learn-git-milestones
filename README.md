# Git Milestones

Below is a list of tasks. By mid-semester, everyone should...

1. Understand what the task is asking
1. Be able to do the task
1. Make it clear through your actions you understand what's happening


### Instructions

1. Fork this repository
1. Complete and check off each of the tasks below, adding content where prompted with: **??**
1. Note: Sometimes I give the command you need and sometimes you have to read the documentation to find it.
1. Celebrate your Git proficiency! 🙌  


## Git Basics


### Your first commit
Create a Git account and make your first commit on github.com

- [ ] [Create a Github account](https://github.com/join)
- [ ] Fork [this repository](https://github.com/omundy/learn-git-milestones) - click the Fork button at the top right.
- [ ] Edit the README file (click the pencil icon) and add your favorite emoji here: **??**
- [ ] Commit changes to the README file directly to the master branch with the message `commit #1` 


### Installation
Install your development environment

- [ ] Install Git on your machine

Windows: Install [Git for Windows](https://gitforwindows.org/) (includes [Git BASH](https://www.atlassian.com/git/tutorials/git-bash), its own version of the bash shell)

Mac: 
1. Install the [homebrew package manager](https://brew.sh/)
1. Install git using Homebrew `brew install git`
1. Set your default shell to bash `chsh -s /bin/bash` - You'll be prompted to type a password. The command line doesn't give you feedback that you're typing. Just type your password and hit enter. Backspace a lot if you make a mistake.

- [ ] On the command line, confirm Git is installed by typing `git` at the prompt and hitting enter
- [ ] [Install Github Desktop](https://desktop.github.com/)
- [ ] Connect your Github account in Githhub Desktop




## Git Workflows


### In Github Desktop
You should be able to perform a basic Git workflow...

- [ ] In Github Desktop clone a repo
  - [ ] Clone your fork of this repository: File > Clone Repository... and choose it from the list
  - [ ] Open the repo in Atom: Repository > Open in Atom  
  - [ ] In Atom, edit the README file and add your *second* favorite emoji here: **??**
  - [ ] Commit changes to the README file directly to the master branch with the message `commit #2` 
- [ ] Push your edits to remote and confirm them on Github.com  
  - [ ] Click Push origin to push your changes back to remote repo  
  - [ ] Choose Repository > View on Github to see the changes to the README file were pushed
  - [ ] Click on the README file and then click on History to see the history of this file
- [ ] Create a new branch, add a new file, and create a pull request
  - [ ] In Github Desktop, create a new branch by clicking on Branch > New Branch. Type `my-new-branch` and click Create Branch
  - [ ] In Atom, create a new file called `hello.txt`, add some text, and save it.
    - [ ] Click the small Git button at the bottom right to display the Git panel. 
    - [ ] Click on your file in Unstaged changes and confirm your changes match what you see in Github Desktop.
  - [ ] In Github Desktop, commit your changes to `my-new-branch` with the message `commit #3` 
  - [ ] Choose Branch > Create Pull Request. This will open Github.com. Confirm the edits you made.
    - [ ] Click Create Pull Request
    - [ ] On the next page click Merge Pull Request
  - [ ] Back in Github Desktop pull the changes. Your master branch should now show the edits from `my-new-branch` 





### Command line (CLI) basics
Using only your favorite command line application...

- [ ] Use the CLI to navigate directories
  - [ ] In Github Desktop, with the repo you cloned above selected, click Repository > Open in Terminal
  - [ ] Use `pwd` to see your current directory. Copy and paste that here: **??**
  - [ ] [Confirm](https://docs.github.com/en/github/using-git/setting-your-username-in-git) your name and email is correct in the Git config
  - [ ] `ls` to list current files
  - [ ] `ls -la` to list current files, including hidden, and confirm the existence of the `.git` directory (where Git versions and config are stored)
- [ ] Use Git on the CLI to `branch`, `edit`
  - [ ] View the status of your repo `git status` 
  - [ ] View the current branch `git branch`
  - [ ] Change back to the master branch `git checkout master`  
- [ ] Use Git on the CLI to `add`, `push`  
  - [ ] Create a new file and add some text to it `echo "hello" >> hello.txt`
  - [ ] `ls` to list current files
  - [ ] View the status of your repo `git status` to confirm the new file
  - [ ] Add the new file to the staging area `git add hello.txt`
  - [ ] Check the status of your repo `git status` to confirm it has been added
  - [ ] Commit your changes with the message `commit #4` 
  - [ ] Use `git push` to [push those changes to your remote repo](https://docs.github.com/en/github/using-git/pushing-commits-to-a-remote-repository)





## Git Fluency



### Turn in your first assignment
Using your favorite tool(s) for Git...

- [ ] Create a new repository for your first assignment
  - [ ] Make a new folder on your computer with your class name - `mkdir dig245`
  - [ ] `cd` into this folder
  - [ ] Make a new folder inside this folder with your class name followed by the assignment # - `mkdir dig245-a1`
  - [ ] `cd` into this folder
  - [ ] Use `pwd` to confirm you have the following directory structure. Copy and paste that here: **??**
  ```
  dig245
    |-- dig245-a1
  ```   
  - [ ] Create an empty Git repository in this folder - `git init`
  - [ ] Add a README file - `touch README.md`


TO ADD


Set up a Github page https://pages.github.com/

Reference the [Github Cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/) to do X





## Further learning

* Github Cheatsheet [HTML](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/) and [PDF](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
* [Github Learning Lab](https://lab.github.com/) which contains tutorials like [Introduction to Github](https://lab.github.com/githubtraining/introduction-to-github) and others





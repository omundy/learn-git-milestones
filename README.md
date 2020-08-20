# Git Milestones

Below is a list of tasks. By mid-semester, everyone should...

1. Understand what the task is asking
1. Be able to do the task
1. Make it clear through your actions you understand what's happening


### Instructions

1. Fork this repository
1. Complete and check off each of the tasks below
1. Note: Sometimes I give the command you need and sometimes you have to read the documentation to find it.
1. Celebrate your Git proficiency! 🙌  


## Git Basics


### Your first commit
Create a Git account and make your first commit on github.com

- [ ] [Create a Github account](https://github.com/join)
- [ ] Fork [this repository](https://github.com/omundy/learn-git-milestones) - click the Fork button at the top right.
- [ ] Edit the README file and add your favorite emoji here:
- [ ] Commit changes to the README file directly to the master branch with the message "commit #1" 


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



### In Github Desktop
You should be able to perform a basic Git workflow...

- [ ] In Github Desktop clone your repo
  - [ ] Clone your fork of this repository: File > Clone Repository... and choose it.
  - [ ] Open the repo in Atom: Repository > Open in Atom  
  - [ ] Edit the README file and add your *second* favorite emoji here:
  - [ ] Commit changes to the README file directly to the master branch with the message "commit #2" 
- [ ] Push your edits to remote and confirm them on Github.com  
  - [ ] Click Push origin to push your changes back to remote repo  
  - [ ] Choose Repository > View on Github to see the changes to the README file were pushed
  - [ ] Click on the README file and then click on History to see the history of this file
- [ ] Create a new branch, add a new file, and create a pull request
  - [ ] Back in Github Desktop, create a new branch by clicking on Branch > New Branch. Type `my-new-branch` and click Create Branch
  - [ ] In Atom, create a new file in Atom called `hello.txt`, add some text, and save it.
    - [ ] Click the small Git button at the bottom right to display the Git panel. 
    - [ ] Click on your file in Unstaged changes and confirm your changes match what you see in Github Desktop.
  - [ ] Back in Github Desktop, commit your changes to `my-new-branch` with the message "commit #3" 
  - [ ] Choose Branch > Create Pull Request. This will open Github.com. Confirm the edits you made.
    - [ ] Click Create Pull Request
    - [ ] On the next page click Merge Pull Request
  - [ ] Back in Github Desktop pull the changes. You master branch should now show the edits from `my-new-branch` 





### Command line (CLI) basics
Using only your favorite command line application...

- [ ] Use Git on the CLI to pull, branch, edit, push
  - [ ] `cd` to the directory with the tutorial repo above
  - [ ] [Confirm](https://docs.github.com/en/github/using-git/setting-your-username-in-git) your name and email is correct in the Git config
  - [ ] `ls` to show the current files
  - [ ] `ls -la` to show the current files, including hidden files, to confirm the existence of the `.git` directory where versions are stored
  - [ ] Check the status of your repo `git status` 
  - [ ] Check the current branch `git branch`
  - [ ] Create a new file and add some text to it `echo "hello" >> hello.txt`
  - [ ] `ls` to show the current files
  - [ ] Check the status of your repo `git status`
  - [ ] Add the new file to the staging area `git add hello.txt`
  - [ ] Check the status of your repo `git status`









### Git Workflow
Using your favorite tool(s) for Git...

- [ ] Create a new repository for your first assignment
  - [ ] Make a folder with your class name (e.g. `mkdir dig245`)
  - [ ] `cd` into the above folder
  - [ ] Make a folder with your class name followed by the assignment # (e.g. `mkdir dig245-a1`)
  - [ ] You should have the following directory structure
  ```
  dig245
    |-- dig245-a1
  ```   
  - [ ] `cd` into your first assignment folder
  - [ ] Create an empty Git repository (e.g. `git init`)



TO ADD


Set up a Github page https://pages.github.com/

Reference the [Github Cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/) to do X





## Further learning

* Github Cheatsheet [HTML](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/) and [PDF](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
* [Github Learning Lab](https://lab.github.com/) which contains tutorials like [Introduction to Github](https://lab.github.com/githubtraining/introduction-to-github) and others





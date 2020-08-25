# Git Milestones

Below is a list of tasks. By mid-semester, everyone should...

1. Understand what the task is asking
1. Be able to do the task
1. Make it clear through your actions you understand what's happening


### Instructions

1. Fork this repository
1. Complete and check off each of the tasks below, adding content where prompted with: **??**
1. Note: Sometimes I give the instructions or command you need and sometimes you have to read the documentation to find it.
1. After you finish, celebrate your Git proficiency! 🙌  


## Git Basics


### Your first commit
Create a Git account and make your first commit on github.com

- [ ] [Create a Github account](https://github.com/join)
- [ ] Fork [this repository](https://github.com/omundy/learn-git-milestones) - click the Fork button at the top right.
- [ ] Edit the README file (click the pencil icon) and add your favorite emoji here: **??**
- [ ] Commit changes to the README file directly to the master branch with the message `commit #1 from Github.com` 
- [ ] View the commit history and confirm your edits


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




## Basic Git Workflows

- You should be able to perform a basic Git workflow using Github.com, the command line, Github Desktop, and Git in Atom
- Doing the same things in four different interfaces will give you practice and help you understand Git better
- You've already forked and made a commit on Github.com so let's move to Github Desktop:


### In Github Desktop

- [ ] In Github Desktop clone a repo to your computer, edit files, commit, and confirm changes on Github.com
  - [ ] Clone the fork of this repository (you created above): File > Clone Repository... and choose it from the list
  - [ ] Open the repo in Atom: Repository > Open in Atom  
  - [ ] In Atom, edit this README file and add your *second* favorite emoji here: **??**
  - [ ] In Github Desktop, confirm the README file was saved and shows your new changes in the Changes tab 
  - [ ] Commit your changes to the README file directly to the master branch with the message `commit #2 from Github Desktop` 
  - [ ] Click Push origin to push your changes back to remote repo  
  - [ ] Confirm the changes to the README file were pushed: Choose Repository > View on Github 
  - [ ] Click on the README file and then click on History to see the history of this file


### Command line (CLI) 
- Now that you've got Github Desktop down and the repo is on your computer, let's make some edits on the command line.
- Some advanced Git operations can only be done on the CLI. In addition, some use the CLI for basic file edits; I'm not going to make you suffer when we have Atom installed
- You've already used most of the commands you'll need below (e.g. `git status`, `git add`, `git commit`, `git push`) by initiating them with GUI


- [ ] Use the CLI to navigate directories
  - [ ] In Github Desktop, with the repo you cloned above selected, click Repository > Open in Terminal (on Windows "Bash"?)
  - [ ] Use `pwd` to see your current directory. Copy the full path
  - [ ] Open the README file in Atom with and paste that path here: **??**
  - [ ] `ls` to list current files
  - [ ] `ls -la` to list current files, including hidden, and confirm the existence of the `.git` directory (where Git versions and config are stored)
- [ ] Use Git on the CLI
  - [ ] [Confirm](https://docs.github.com/en/github/using-git/setting-your-username-in-git) your name and email is correct in the Git config
  - [ ] View the status of your repo `git status` 
  - [ ] Create a new file and add some text to it `echo "hello" >> hello.txt`
  - [ ] `ls` to list current files
  - [ ] View the status of your repo `git status` to confirm the new file exists
  - [ ] Add the new file to the staging area `git add hello.txt` (pro tip: type the first three characters of a file and press tab to autocomplete!)
  - [ ] Check the status of your repo `git status` to confirm it has been staged
  - [ ] Commit your changes with the message `commit #3 from CLI` 
  - [ ] Use `git push` to [push those changes to your remote repo](https://docs.github.com/en/github/using-git/pushing-commits-to-a-remote-repository)


### Git in Atom 
- Finally, on to a real development environment!

- [ ] Use Git in Atom for basic Git workflow
  - [ ] In Github Desktop, open the repo in Atom: Repository > Open in Atom  
  - [ ] In Atom, edit this README file and add your *third* favorite emoji here: **??**
  - [ ] Add some more text to `hello.txt` and save it.
  - [ ] Click the small Git button at the bottom right to display the Git panel. 
  - [ ] Click on your file(s) in Unstaged changes and confirm your changes match what you expect to see
  - [ ] Double click on each file with changes to stage them  
  - [ ] Commit your changes directly to the master branch with the message `commit #4 from Atom` 




## Turn in Assignments
- Use Git to create and turn in DIG 245 assignments


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
  - [ ] In the README write your name and the date
- [ ] Complete Assignment 1
  - [ ] Create a file called `index.html` in your repo
  - [ ] Add some text to it like `<h1>Hello world!</h1>`
  - [ ] Commit the file
- [ ] Set up a [Github page](https://pages.github.com/) "project site" for your repo 
  - [ ] Choose "Project site"
  - [ ] Do not use a theme; Start from scratch
  - [ ] In your repository settings, scroll aaaaallllll the way down to the Github Pages section, select he master branch source and click save
  - [ ] Visit your project site at http://*username*.github.io/dig245-a1



## Git Fluency
- Use Git to create branches, push and pull changes, and create pull requests




- [ ] Create a new branch, add a new file, and create a pull request
  - [ ] In Github Desktop, create a new branch by clicking on Branch > New Branch. Type `my-new-branch` and click Create Branch
  - [ ] In Atom, create a new file called `hello.txt`, add some text, and save it.

  - [ ] In Github Desktop, commit your changes to `my-new-branch` with the message `commit #3` 
  - [ ] Choose Branch > Create Pull Request. This will open Github.com. Confirm the edits you made.
    - [ ] Click Create Pull Request
    - [ ] On the next page click Merge Pull Request
  - [ ] Back in Github Desktop pull the changes. Your master branch should now show the edits from `my-new-branch` 




- [ ] Use Git on the CLI to `branch`, `edit`
  - [ ] View the current branch `git branch`
  - [ ] Change back to the master branch `git checkout master`  





TO ADD





- [ ] Reference the [Github Cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/) to do X





## Further learning

* Github Cheatsheet [HTML](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/) and [PDF](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
* [Github Learning Lab](https://lab.github.com/) which contains tutorials like [Introduction to Github](https://lab.github.com/githubtraining/introduction-to-github) and others





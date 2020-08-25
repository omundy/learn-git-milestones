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
- [ ] Fork this repository [learn-git-milestones](https://github.com/omundy/learn-git-milestones) (click the Fork button, top right).
- [ ] Edit the README file (click the pencil icon) and add your favorite emoji here: **??**
- [ ] Commit changes to the README file directly to the master branch with the message `commit #1 from Github.com` 
- [ ] View the commit history and confirm your edits


### Git Installation
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
You should be able to perform a basic Git workflow using Github.com, the command line, Github Desktop, and Git in Atom. Using four different interfaces will give you practice and help you understand Git better. You've already forked and made a commit on Github.com so let's move to Github Desktop ...


### In Github Desktop
You should be able to ...

- [ ] In Github Desktop, clone the fork (you made above) of this repository [learn-git-milestones](https://github.com/omundy/learn-git-milestones): File > Clone Repository > Github.com and select it ...
  - [ ] ... Local Path: Click "Choose" and add a new folder on your computer. This will be the base folder for your work in this class: `critical-web-design`
  - [ ] ... Click "Clone" to make a local copy
- [ ] Open the repo in Atom: Repository > Open in Atom  
- [ ] In Atom, edit this README file and add your *second* favorite emoji here: **??**
- [ ] In Github Desktop, confirm the README file was saved and shows your new changes in the Changes tab 
- [ ] Commit your changes to the README file directly to the master branch with the message `commit #2 from Github Desktop` 
- [ ] Click Push origin to push your changes back to remote repo  
- [ ] Confirm the changes to the README file were pushed: Choose Repository > View on Github 
- [ ] Click on the README file and then click on History to see the history of this file


### Command line (CLI) 
You should have a basic familiarity with the command line in case you need to do advanced Git commands. Many folks use the CLI for file editing, though I'm not going to make you suffer when we have Atom installed. You've used most of these already through a GUI (e.g. `git status`, `git add`, `git commit`, `git push`) ...


- [ ] Use the CLI to navigate directories
  - [ ] In Github Desktop, with the [learn-git-milestones](https://github.com/omundy/learn-git-milestones) repo you cloned above selected, click Repository > Open in Terminal ("Bash" in Windows?)
  - [ ] List files in this directory: `ls`
  - [ ] List files in this directory, including hidden: `ls -la`  
  - [ ] Confirm the existence of the `.git` directory (where Git versions and config are stored)
  - [ ] View your current directory and copy the full path: `pwd`
  - [ ] Open this README file in Atom and paste that path here: **??**
  
- [ ] Use Git on the CLI
  - [ ] [Confirm](https://docs.github.com/en/github/using-git/setting-your-username-in-git) your name and email is correct in the Git config
  - [ ] View the status of your repo: `git status` 
  - [ ] Add all changed files to the staging area `git add .`
  - [ ] View the status of your repo `git status` to confirm it has been staged
  - [ ] Commit your changes with the message `commit #3 from CLI` 
  - [ ] Use `git push` to [push those changes to your remote repo](https://docs.github.com/en/github/using-git/pushing-commits-to-a-remote-repository)


### Git in Atom 
You should be able to ...

- [ ] In Github Desktop, open this repo [learn-git-milestones](https://github.com/omundy/learn-git-milestones) in Atom: Repository > Open in Atom  
- [ ] In Atom, edit this README file and add your *third* favorite emoji here: **??**
- [ ] Create a new file `hello.txt`, add some text and save it.
- [ ] Display the Git panel (click the small Git button at the bottom right). 
- [ ] Select on your file(s) in Unstaged changes and confirm your changes match what you expect to see
- [ ] Double click on each file with changes to stage them  
- [ ] Commit your changes directly to the master branch with the message `commit #4 from Atom` 




## Turn in Assignments
Now that we have basic Git commands out of the way use Git to create and turn in your DIG 245 assignment ...


### Turn in your first assignment
You should be able to ...


- [ ] In Github Desktop, click File > New Repository ...
  - [ ] ... Name: `dig245-a1`
  - [ ] ... Local Path: Click "Choose" and create a new folder `dig245-a1` inside the `critical-web-design` folder you made above
  - [ ] ... Click Create Repository
  - [ ] This should be your class folder's directory structure. 
  ```
  critical-web-design
    |-- dig245-a1
    |-- learn-git-milestones
  ```
- [ ] Open your new repository in Atom (with Github Desktop or drag the `dig245-a1` project folder into Atom)

  - [ ] Add a README file - `README.md`

- [ ] Create an empty Git repository in this folder - `git init`

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





## Resources

* Github Cheatsheet [HTML](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/) and [PDF](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
* [Github Learning Lab](https://lab.github.com/) which contains tutorials like [Introduction to Github](https://lab.github.com/githubtraining/introduction-to-github) and others





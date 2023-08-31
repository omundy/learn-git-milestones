<!-- 
<img width="400" src="assets/img/logo-git-github.png"> -->

# Git Milestones

An introduction to Git and Github.


## Instructions

Complete each task below, creating files and adding content inside the [completions](#completions) table when prompted with a ✏️  - After you finish, celebrate your Git proficiency! 🙌

- Follow the instructions. Review course content as needed.
- Sometimes I share the command you need, but you may need to read the documentation.
- This milestone is for multiple classes. Insert your own class name when prompted, for example: `critical-web-design`





## 1 - Install Git

⚠️ Complete this [command line crash course](https://github.com/omundy/learn-computing/blob/main/topics-command-line.md#crash-course) to prepare to install Git on your machine.
<!-- https://gist.github.com/derhuerst/1b15ff4652a867391f03 -->

**Windows** - Download and install Git from: [gitforwindows.org](https://gitforwindows.org/). This includes [Git BASH](https://www.atlassian.com/git/tutorials/git-bash).

**Mac** - Install Git using Homebrew 

1. Copy and run this whole line to Install the [homebrew package manager](https://brew.sh/). If prompted to "Install Command Line Developer Tools?", choose **yes**. 

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. To confirm installation:

```bash
brew doctor
```


3. Then install git using homebrew:

```bash
brew install git
```

Verify Git is installed by typing `git` on the command line and pressing enter. You should see a help file with a list of possible commands.

<!-- 1. Set your default shell to bash `chsh -s /bin/bash` - You'll be prompted to type a password. The command line doesn't give you feedback that you're typing. Just type your password and hit enter. Backspace a lot if you make a mistake. -->








## 2 - Configure Git

1. Check to see if Git is already configured?

```bash
cat ~/.gitconfig
```

2. Add your name (replace with ***your*** information, press return after each line)

```bash
git config --global user.name "Your Name"
```

3. Add your email

```bash
git config --global user.email youraddress@example.com
```

4. Set the [default branch to main](https://www.theserverside.com/feature/Why-GitHub-renamed-its-master-branch-to-main)

```bash
git config --global init.defaultBranch main
```

5. Set pull to merge ([not rebase](https://stackoverflow.com/a/36587353/441878))

```bash
git config --global pull.rebase false
```

6. Confirm your global settings worked

```bash
cat ~/.gitconfig
```

<!-- reference https://stackoverflow.com/a/46986031/441878 -->
<!-- # or show settings and location of each config file (system, global, local)
git config --list --show-origin -->





## 3 - Markdown Introduction

Markdown is a lightweight markup language for creating rich text.

- It has a [simple syntax](https://www.markdownguide.org/cheat-sheet/) similar to [HTML](https://en.wikipedia.org/wiki/Markdown#Example)
- It is the standard language for formatting README files (what you are currently viewing!)
- Files use the `.md` extension and can be edited with any plain text editor (e.g. VS Code).
- Preview using the VS Code or the [Markdown Viewer](https://chrome.google.com/webstore/detail/markdown-viewer/ckkdlimhmcjmikdlpkmbgfkaikojcbjk/related?hl=en) 

Markdown | HTML | Rendered Output
--- | --- | ---
`[link](https://davidson.edu)` | `<a href="https://davidson.edu">link</a>` | [link](https://davidson.edu)
`**bold text**` | `<b>bold text</b>` | **bold text**
`*italicized text*` | `<i>italicized text</i>` | *italicized text*
<code>\`code`</code> | `<code>code</code>` | `code`
`![text](assets/img/icon.png)` | `<img alt="text" src="assets/img/icon.png">` | ![text](assets/img/icon.png)

**Now you know basic Markdown!** 🎉  

The following instructions will help you learn Git, editing this `.md` file in the process. Use the [github markdown cheatsheet](reference-sheets/github-markdown-cheatsheet.pdf) to check your syntax.

Other Markdown tools

- [Paste (RTF or rendered HTML) to Markdown](https://euangoddard.github.io/clipboard2markdown/)
- [HTML to Markdown](https://codebeautify.org/html-to-markdown)







## 4 - Fork this repository

Create a Github account and make your first commit on Github.com

1. [Create a Github account](https://github.com/join)
1. Fork this [learn-git-milestones](https://github.com/omundy/learn-git-milestones) repository (click the Fork button, top right).
1. ✏️ Edit this `README.md` file (click the pencil icon on the Github.com page) and add your *1st* favorite emoji to the [Completions](#completions) table, in the **Completed** column in appropriate row in the [completions](#completions), below.
1. Commit changes to README.md to the `main` branch with the message `commit #1 from Github.com`.
1. ✏️ Use [Markdown documentation](https://guides.github.com/features/mastering-markdown/) to add a link in [completions](#completions). The link text should be the same as the commit message, and the url should point to the Github.com page showing the above commit.
1. ✏️ Tables can be a little tricky in Markdown. Find a good link explaining how to use markdown tables. Paste the link in the [Completions](#completions) table.
1. View the commit history and confirm your edits
1. ✏️ What does `log` do? Add your answer to [completions](#completions).





## 5 – Git Workflow > Github Desktop

Perform a basic Git workflow using Github Desktop. This is the first of four different interfaces to give you practice with Git. You've already forked and made a commit on Github.com so let's move to Github Desktop ...


### Setup

1. Install [Github Desktop](https://desktop.github.com/)
1. Connect your Github account in Github Desktop
1. In Github Desktop, clone the fork (you made above) [learn-git-milestones](https://github.com/omundy/learn-git-milestones) ...
1. File > Clone Repository > Github.com and select it ...
1. Local Path: Click "Choose" and add a new folder on your computer. This will be the base folder for your work in this class (e.g. `critical-web-design`, `game-development` )
1. Click "Clone" to make a local copy

### Open in VS COde

1. Install [VS Code](https://code.visualstudio.com/)) and connect your Github account
1. Open the repo in VS Code: Repository > Open in VS Code (see preferences to change your editor)
1. ✏️ In VS Code, edit this README file and add your *2nd* favorite emoji to [completions](#completions).
1. In Github Desktop, view/confirm your edits to the README file on the Changes tab
1. ✏️ Commit your changes directly to the main branch with the message `commit #2 from Github Desktop`. 
1. Find a link to the above commit on Github.com and use VS Code to add it to [completions](#completions). Commit your change.
1. Click Push origin to push your new commit to remote repo
1. Confirm the changes to the README file were pushed: Choose Repository > View on Github
1. Click on the README file and then click on History to see the history of this file



## 6 – Git Workflow > Command line 

Some folks use the CLI as their default tool for editing and publishing source code, but Github Desktop makes it much easier.

### Setup

1. In Github Desktop, ensure you are currently in the [learn-git-milestones](https://github.com/omundy/learn-git-milestones) repo you cloned above.
1. Click Repository > Open in Terminal ("Bash" in Windows?)

### Use the CLI to navigate directories


1. List files in this directory: `ls`
1. List files in this directory, including hidden: `ls -la`
1. Confirm the existence of the `.git` directory (where Git versions and config are stored)
1. ✏️ View your current working directory and copy the full path: `pwd`
1. Open this README file in VS Code and paste that path in [completions](#completions).

### Use Git on the CLI

1. [Confirm](https://docs.github.com/en/github/using-git/setting-your-username-in-git) your name and email is correct in the Git config
1. View the status of your repo: `git status`
1. View the changed files of your repo: `git diff`
1. Add all changed files to the staging area `git add .`
1. View the status of your repo `git status` to confirm it has been staged
1. ✏️ Commit your changes with the message `commit #3 from CLI`. Add a link to this commit to [completions](#completions).
1. Use `git push` to [push those changes to your remote repo](https://docs.github.com/en/github/using-git/pushing-commits-to-a-remote-repository)



You've used most of these already through a GUI (e.g. `git status`, `git add`, `git commit`, `git push`) ...





## 7 - Git Workflow > VS Code

1. From Github Desktop, you can open the [learn-git-milestones](https://github.com/omundy/learn-git-milestones) repo in VS Code using: Repository > Open in VS Code
1. ✏️ In VS Code, edit this README file and add your *3rd* favorite emoji to [completions](#completions).
1. ✏️ Create a new file `hello.txt`, add some text and save it.
1. Display the Git panel (click the small Git button at the bottom right).
1. Select on your file(s) in Unstaged changes and confirm your changes match what you expect to see
1. Double click on each file with changes to stage them
1. ✏️ Commit your changes directly to the main branch with the message `commit #4 from VS Code`. Add a link to this commit to [completions](#completions).


<img src="assets/img/editor-git-menu-vs-code.png" width="400">



## 8 – Create a new repository

1. ✏️ In Github Desktop, create a new repository with the name: `first-website`
1. Make sure the repository is public *not private* 
1. Local Path: Click "Choose" and create a new folder `first-website` inside the `<your-class-name-here>` folder you made above
1. Click Create Repository
1. This should now be your class folder's directory structure.

```html
<your-class-name-here>
|-- first-website
|-- learn-git-milestones
```

1. Open your new repository in VS Code (with Github Desktop or drag the `first-website` project folder onto the VS Code icon in your dock)
1. ✏️ Add a README file: `README.md`
1. ✏️ In the README write your name and the date
1. ✏️ Use some [Markdown tags](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
1. ✏️ Commit your changes and add a link to this repo to [completions](#completions).




## 9 – Publish a web site with Github Pages

[Github Pages](https://pages.github.com/) is a free and easy way to host a website from your repository. 

1. ✏️ Create a file called `index.html` in your new repo and add the following code

```html
<!DOCTYPE html>
<html>
<head>
<title>My first github.io website</title>
</head>
<body>

<h1>Hello world!</h1>
<p>🙌</p>

</body>
</html>
```

1. On Github.com, go to your repo > Settings > Pages
1. Select the main branch source and click save
1. Do not use a theme. Start from scratch
1. Visit your project site at http://*username*.github.io/first-website
1. Update your project, push a new commit, and confirm your updates (note: [deployments](https://github.com/omundy/learn-git-milestones/deployments/github-pages) sometimes take a bit)
1. ✏️ Paste this link to [completions](#completions).






## 10 – Turn in this Assignment

Now that we have basic Git commands out of the way use Git to create and turn in your assignment ...

1. Complete all of the items on this README, making sure all the rows in the "Completed" column contain your information below.
1. Test your file(s) in a web browser
1. Commit and push the files to Github
1. Paste the github.io link into the appropriate Moodle forum



<!-- 
## Git Advanced

That is all that is required for this milestone. See the `ADVANCED.md` file if you would like to continue learning Git.
 -->




## Completions

Item # | Description | Completed
--- | --- | ---
4a | 1st Favorite emoji | ADD_TEXT_TO_THIS_COLUMN
4b | Link to `commit #1 from Github.com` |
4c | Link to markdown tables docs |
4d | What does `log` do? |
5a | 2nd Favorite emoji |
5b | Link to `commit #2 from Github Desktop` |
6a | Full path to your working directory |
6b | Link to `commit #3 from CLI` |
7 | 3rd Favorite emoji |
8 | Link to `commit #4 from VS Code` |
9a | Link to `first-website` github.com repo page |
9a | Link to `first-website` github.io "project site" |





## Resources

Here are some popular tutorials/guides. You should **still look for other ones that you might like better**!

- The class [Git & Github lectures](https://docs.google.com/presentation/d/1vtK6LoqwF4rQQZZy-ovuEgsYUwwMRXsqDVMOjAPSBt0/edit#slide=id.p)
- [Github Desktop Documentation](https://docs.github.com/en/desktop)
- Github Cheatsheet [HTML](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/) and [PDF](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
- [Github Learning Lab](https://lab.github.com/) which contains tutorials like [Introduction to Github](https://lab.github.com/githubtraining/introduction-to-github) and others
- View forks of this repo http://gitpop2.herokuapp.com/omundy/learn-git-milestones


## Credits

Thanks to [Jesse Farmer](https://github.com/jfarmer) for inspiring this milestone assignment.

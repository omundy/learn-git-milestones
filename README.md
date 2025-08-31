<!-- 
<img width="400" src="assets/img/logo-git-github.png"> -->

# Git Milestones

An introduction to Git and Github.

- [PART 1 - Git Basics](#part-1---git-basics)
- [PART 2 - Git Collaboration](#part-2---git-collaboration)

## Instructions

1. Complete the below steps, adding content in the [completions](#completions) table when prompted with ✏️ 
1. Review course content as needed. You may need to read the documentation as well.
1. Insert your own class name when prompted, for example: `critical-web-design`
1. After you finish, celebrate your Git proficiency! 🙌





# PART 1 - Git Basics

Install, configure, and perform basic operations while creating a simple website


## 1. Install and Configure Git

Follow [these instructions](./install-configure.md)




## 2. Markdown Introduction

Markdown is a lightweight markup language for creating rich text.

- It has a [simple syntax](https://www.markdownguide.org/cheat-sheet/) similar to [HTML](https://en.wikipedia.org/wiki/Markdown#Example)
- It is the standard language for formatting README files (what you are currently viewing!)
- Files use the `.md` extension and can be edited with any plain text editor (e.g. VS Code).
- Preview using the VS Code or the [Markdown Viewer](https://chrome.google.com/webstore/detail/markdown-viewer/ckkdlimhmcjmikdlpkmbgfkaikojcbjk/related?hl=en) browser extension 

Markdown | Output | HTML of output
--- | --- | ---
`[link](https://davidson.edu)` | [link](https://davidson.edu) | `<a href="https://davidson.edu">link</a>`
`**bold text**` | **bold text** | `<b>bold text</b>`
`*italicized text*` | *italicized text* | `<i>italicized text</i>`
<code>\`code`</code> | `code` | `<code>code</code>`
`![text](assets/img/icon.png)` | ![text](assets/img/icon.png) | `<img alt="text" src="assets/img/icon.png">`

🎉 Now you know basic Markdown! Continue with following instructions to learn Git, editing this `.md` file in the process. Use the [github markdown cheatsheet](reference-sheets/github-markdown-cheatsheet.pdf) to check your syntax.



<details>
<summary>Other handy Markdown tools</summary>

<ol>
<li><a href="https://euangoddard.github.io/clipboard2markdown/" target="_blank">Paste (RTF or rendered HTML) to Markdown</a></li>
<li><a href="https://codebeautify.org/html-to-markdown" target="_blank">HTML to Markdown</a></li>
</ol>

</details>





## 3. Fork this repository

Now that you know markdown, create a Github account and make your first commit on Github.com

1. [Create a Github account](https://github.com/join)
1. Fork this [learn-git-milestones](https://github.com/omundy/learn-git-milestones) repository (click the Fork button, top right).
1. ✏️ Edit this `README.md` file (click the pencil icon on the Github.com page) and add your *1st* favorite emoji to the **Completed** column in appropriate row in the [completions [3-1]](#completions) section, below.
1. Commit your changes to this file to the `main` branch with the message `commit #1 from Github.com`.
1. ✏️ Use [Markdown documentation](https://guides.github.com/features/mastering-markdown/) to add a link in [completions [3-2]](#completions). The link text should be the same as the commit message, and the url should point to the Github.com page showing the above commit.
1. ✏️ Tables can be a little tricky in Markdown. Use a search engine to find a good link explaining how to use markdown tables and paste it in the [completions [3-3]](#completions) table.
1. View the commit history and confirm your edits
1. ✏️ What does `git log` do? Add your answer to [completions [3-4]](#completions).





## 4. Git Workflow > Github Desktop

With Git installed on your computer you can perform a basic Git workflow using Github Desktop. This is the first of a few different interfaces to give you practice with Git. You've already forked and made a commit on Github.com so let's move to Github Desktop ...


### Install Github Desktop

1. Install [Github Desktop](https://desktop.github.com/) on your computer
1. Connect your Github account in Github Desktop

### Clone the repository

In Github Desktop, clone the fork of this repository that you made above...

1. Select File > Clone Repository > Github.com and select it ...
1. Local Path: The default location is usually fine: `/Users/<username>/Documents/Github/` (or the equivilant on Windows). You can also use a folder specific to your class name, as long as it doesn't have spaces (e.g. `critical-web-design`)
1. Click "Clone" to finish. This will save a local copy of the repository on your computer and make it available to Github Desktop.

### Use Github Desktop with VS COde

1. Install [VS Code](https://code.visualstudio.com/) on your computer
1. In Github Desktop, open the repo in VS Code: Repository > Open in VS Code (see preferences to change your editor)
1. ✏️ In VS Code, edit this README file and add your *2nd* favorite emoji to [completions [4-1]](#completions) and save the file.
1. In Github Desktop, view/confirm your edits to the README file on the Changes tab
1. Commit your changes directly to the main branch with the message `commit #2 from Github Desktop`. 
1. Click Push origin to push your new commit to the remote repo
1. Choose Repository > View on Github.
1. Click on the README file and then click History to see the history of this file
1. Click on the above commit (`#2`) and copy the URL. Use VS Code to add it to [completions [4-2]](#completions) . Commit your change in Github Desktop.




## 5. Git Workflow > Command line 

Some folks use the CLI as their default tool for editing and publishing source code, but Github Desktop makes it much easier.

### Setup

1. In Github Desktop, ensure you are currently in the [learn-git-milestones](https://github.com/omundy/learn-git-milestones) repo you cloned above.
1. Click Repository > Open in Terminal ("Bash" in Windows?)

### Use the CLI to navigate directories

1. List files in this directory: `ls`
1. List files in this directory, including hidden: `ls -la`
1. Confirm the existence of the `.git` directory (where Git versions and config are stored)
1. View your current working directory and copy the full path: `pwd`
1. ✏️ Open this README file in VS Code and paste that path in [completions [5-1]](#completions).


### Use Git on the CLI

1. [Confirm](https://docs.github.com/en/github/using-git/setting-your-username-in-git) your name and email is correct in the Git config
1. View the status of your repo: `git status`
1. View the changed files of your repo: `git diff`
1. Add all changed files to the staging area `git add .`
1. View the status of your repo `git status` to confirm it has been staged
1. ✏️ Commit your changes with the message `commit #3 from CLI`. Add a link to this commit to [completions [5-2]](#completions).
1. Use `git push` to [push those changes to your remote repo](https://docs.github.com/en/github/using-git/pushing-commits-to-a-remote-repository)



You've used most of these already through a GUI (e.g. `git status`, `git add`, `git commit`, `git push`) ...




<!-- 
## 7. Git Workflow > VS Code

1. From Github Desktop, you can open the [learn-git-milestones](https://github.com/omundy/learn-git-milestones) repo in VS Code using: Repository > Open in VS Code
1. ✏️ In VS Code, edit this README file and add your *3rd* favorite emoji to [completions](#completions).
1. Create a new file `hello.txt`, add some text and save it.
1. Display the Git panel (click the small Git button at the bottom right).
1. Select on your file(s) in Unstaged changes and confirm your changes match what you expect to see
1. Double click on each file with changes to stage them
1. ✏️ Commit your changes directly to the main branch with the message `commit #4 from VS Code`. Add a link to this commit to [completions](#completions). 


<img src="assets/img/editor-git-menu-vs-code.png" width="400">  
-->



## 6. Create a website with Git


### Create a new repository in Github Desktop

1. Select File > New repository to create a new repository with the following... 
2. Name: `first-website`
3. Local Path: Click "Choose" and select the parent folder of the repository you cloned above (so that the new repository folder will be created next to `learn-git-milestones`, not inside of it!)

```html
<parent-folder> <-THIS!
|-- first-website 
|-- learn-git-milestones
```

4. Initialize this resository with a README? `yes`
5. Git Ignore: Select any option (we will overwrite below)
6. License: `MIT`
7. Click Create Repository



### Add a README.md

1. In Github Desktop choose Repository > Open in VS Code
1. Add a README file: `README.md`
1. In the README write your name and the date
1. Use some [Markdown tags](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)


### Add a .gitignore file

A `.gitignore` file will prevent git from adding unwanted files to your repository.

1. In VS Code, add a new file named `.gitignore`. The period in front will hide the file from the Finder (or Explorer) but it will still be visible in VS Code.
1. Copy the contents of either the [MacOS](https://github.com/github/gitignore/blob/33243d9491911332228307c915ff95707791a91f/Global/macOS.gitignore) or [Windows](https://github.com/github/gitignore/blob/33243d9491911332228307c915ff95707791a91f/Global/Windows.gitignore) `.gitignore` files and paste it into your own.
1. Commit your changes using Github Desktop. 


### Add an index.html file

1. In VS Code, create a file named `index.html` in your new repo 
2. Add the following code

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title>My first github.io website</title>
	</head>
	<body>
		<h1>Hello, World!</h1>
		<p>🙌</p>
	</body>
</html>
```

3. Commit your changes using Github Desktop.


### Publish this repository on Github.

1. In Github Desktop, click "Publish this repository on Github"
1. Make sure the repository is public *not private* 
1. Click Publish Repository
1. Choose Repository > View on Github
1. ✏️ Add a link to this repo on Github to [completions [6-1]](#completions).




## 7. Publish a website with Github Pages

Now that your files are on Github you can use [Github Pages](https://pages.github.com/), a free and easy way to host a website from your repository. 

1. On Github.com, go to your repository > Settings > Pages
1. Source: Deploy from Branch
1. Branch: Select the `main` and `/(root)` folder and click Save
1. Do not use a theme. Start from scratch
1. Wait about 60 seconds and refresh the page. You will see a link at the top that says "Your site is live at..." with a URL that looks like `http://*username*.github.io/first-website`
1. Update your index.html page with VS Code, push a new commit with Github Desktop, and confirm your updates are live. You can see the status of your deployments from the link on your main repo page.
1. ✏️ Paste a link to the ***live*** (github.io) website in [completions [7-1]](#completions).



🎉 Congratulations! 🎉 You just built a website with Git and Github!!




## Turn in this Assignment

Now that we have basic Git commands out of the way use Git to create and turn in your assignment ...

1. Complete all of the items on this README, making sure all the rows in the "Completed" column contain your information below.
1. Test your file(s) in a web browser
1. Commit and push the files to Github
1. Paste the github.io link into the appropriate Moodle forum



## Completions

Row | Step | Description | Completed
--- | --- | --- | ---
1 | 3-1 | 1st Favorite emoji | 😂
2 | 3-2 | Link to `commit #1 from Github.com`| [commit #1 from Github.com](https://github.com/anushrimodi/learn-git-milestones/commit/61a0dc89ea405da9c7c1636e90b582c8e6aeb154)
3 | 3-3 | Link to markdown tables docs | [GitHub Docs: Organizing information with tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables)
4 | 3-4 | What does `log` do? | It shows the history of commits in our repository. For each commit, it also displays the commit ID, author, and date.
5 | 4-1 | 2nd Favorite emoji | ❤️
6 | 4-2 | Link to `commit #2 from Github Desktop` | [commit #2 from Github.com](https://github.com/anushrimodi/learn-git-milestones/commit/f18a59de10a9dd01b43c28094fcb19e7c9e10fe3)
7 | 5-1 | Full path to your working directory | /Users/apple/Documents/GitHub/learn-git-milestones
8 | 5-2 | Link to `commit #3 from CLI` | [commit #3 from CLI](https://github.com/anushrimodi/learn-git-milestones/commit/c82dbb92ddcfdfd224d5a67dfd2491ecf5cf4f4e)
9 | 6-1 | Link to `first-website` github.com repo page | [first-website](https://github.com/anushrimodi/first-website)
10 | 7-1 | Link to `first-website` github.io "project site" | [Anushri's First Website](https://anushrimodi.github.io/first-website/)







# PART 2 - Git Collaboration

Forking, branching, pull requests


<details>
<summary>Steps 8-11</summary>






## 8. Create a branch in Github Desktop

1. Save all your work in VS Code and close your files (this is not required to switch branches, but is a good practice so you don't lose work!). There should be no changes in your repo.
2. In Github Desktop, click Fetch and then Pull to make sure you are synced with the remote

![branch btn](assets/img/github-desktop-branch-btn.png)

3. Click the Branch dropdown (pictured above) to see the other branches in this repo. You should see `main` (your current branch) and one other. Switch to the other branch.
4. ✏️ Look in VS Code to see the contents of the other `owen-cool-new-feature` branch. Summarize the contents of the `cool-new-feature` file in the [completions [8-1]](#completions) column.



## 9. Create a branch in Github Desktop

1. Use Github Desktop to switch back to the `main` branch.
1. Click Branch > New Branch... (or use the dropdown)
1. Name the branch (using no spaces or special characters) using your name + `-changes` (e.g. `owen-changes`)
1. Add a new file (a graphic or text file) with the same name to the repo.
1. Commit your changes
1. Publish your new branch and changes to the Github server
1. Open your repo on https://github.com and find the branches page.
1. ✏️ Click on your branch and paste the URL into the [completions [9-1]](#completions) column.


## 10. Create a pull request

> *A pull request (PR) is the method to move commits from one branch or repo into another branch or repo. This could be used to sync commits across two branches in the same repository or ask another project owner to merge commits from your fork into theirs. Below, you will use a PR to sync changes from your new branch to the `main` branch.*

1. On your repo Github.com page, click Pull Request. 
2. Click New pull request. 
3. Compare changes between `main` and your new branch. You should see at least one commit listed, as well as any new or changed files.
4. Click Create pull request. Then add a message and click Create pull request again.
5. On the next page, click Merge pull requests to merge the commits into your `main` branch.
6. ✏️ On your repo Github.com page, click Insights > Network to see the branch flowchart of your project. Paste the link into the [completions [10-1]](#completions) below.


![pr](assets/img/github-new-pr.png)



## 11. Suggest changes to a partner's project using a PR

1. Find a partner and discuss a small improvement to their `first-website` (or another) project repo (design, code, functionality).
1. Fork their repository and clone your fork to your computer.
1. Create a new branch with your name + the name of the improvement.
1. Make the improvement.
1. Commit your work to your new branch in your fork.
1. On on your fork on Github.com click Pull requests > New pull request. This will take you to their repo page where you can see a diff comparing your changes in your `fork:repo` to their base `fork:repo`. 
1. ✏️ Create the pull requst as you did above. They will receive an email to accept the change. Copy the link to the pull request to the [completions [11-1]](#completions) table.
1. Turn in this assignment on Moodle!






## Completions (pt.2)

Row | Step | Description | Completed
--- | --- | --- | ---
11 | 8-1 | What is in Owen's dev branch? | A music video of people dancing and singing
12 | 9-1 | Link to your new branch on github.com | [anushri-changes branch](https://github.com/anushrimodi/learn-git-milestones/tree/anushri-changes)
13 | 10-1 | Link to your network graph | 
14 | 11-1 | Link to the PR you made on a partner's github.com repo | 


</details>



## Resources

Here are some popular tutorials/guides. You should **still look for other ones that you might like better**!

- The Git & Github lectures found in the schedule
- Simple Git commands [cheatsheet](commands.md)
- [Github Desktop Documentation](https://docs.github.com/en/desktop) and [cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/) ([PDF](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf) format)
- [Github Learning Lab](https://lab.github.com/) which contains tutorials like [Introduction to Github](https://lab.github.com/githubtraining/introduction-to-github) and others
- View forks of this repo http://gitpop2.herokuapp.com/omundy/learn-git-milestones


<!-- 
## Git Advanced

That is all that is required for this milestone. See the `advanced.md` file if you would like to continue learning Git. 
-->


## Credits

Thanks to [Jesse Farmer](https://github.com/jfarmer) for inspiring this milestone assignment.

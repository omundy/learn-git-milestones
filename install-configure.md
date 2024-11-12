# Install Git 

Use the below instructions to install and configure Git on your computer. 




## Install Git on Windows

1. Download the installer at <a href="https://gitforwindows.org/" target="_blank">gitforwindows.org</a>
1. Run the installer. Use the default settings, making sure to install <a href="https://www.atlassian.com/git/tutorials/git-bash" target="_blank">Git BASH</a>
1. Proceed to [Configure Git](#configure-git)



## Install Git on Mac

<a href="https://brew.sh/" target="_blank">Homebrew</a> is a software package management system that simplifies the installation of software on macOS



1. Copy and run this whole line to Install Homebrew. 

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

> If offered to "Install Command Line Developer Tools", choose <code>yes</code>, then continue. The Terminal won't show characters while typing passwords. Backspace several times if you make a mistake.

2. Confirm that Homebrew was installed. It will print the current version (e.g. `Homebrew 4.4.3...`)

```bash
brew --version
```

3. Then install git using Homebrew 

```bash
brew install git
```

4. Proceed to [Configure Git](#configure-git)




## Install Git on Linux

> Most Linux systems – including Ubuntu and Raspberry Pi OS – are Debian-based.

Use the Advanced package tool (APT) to install Git then proceed to [Configure Git](#configure-git).

```bash
sudo apt update
sudo apt upgrade
sudo apt install git
```










## Configure Git

1. Verify Git is installed by outputing the current version.

```bash
git --version
# -> git version 2.38.1
```



2. Add your name

> Replace ***Your Name*** (inside the quotes). Press return after each line

```bash
git config --global user.name "Your Name"
```

3. Add your email

```bash
git config --global user.email youraddress@example.com
```




4. Set the [default branch to main](https://www.zdnet.com/article/github-to-replace-master-with-alternative-term-to-avoid-slavery-references/)

```bash
git config --global init.defaultBranch main
```



5. Set pull to merge ([recommended](https://stackoverflow.com/a/36587353/441878) over rebase for new users)

```bash
git config --global pull.rebase false
```

<details>
<summary>Merge vs. Rebase</summary>

> Merging is nice because it’s a non-destructive operation. The existing branches are not changed in any way. This avoids all of the potential pitfalls of rebasing. [...] On the other hand, this also means that the feature branch will have an extraneous merge commit every time you need to incorporate upstream changes
https://www.atlassian.com/git/tutorials/merging-vs-rebasing

</details>



6. Mac or Linux should [convert line endings](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration) to `LF` (see also [Configuring Git to handle line endings](https://docs.github.com/en/get-started/getting-started-with-git/configuring-git-to-handle-line-endings))

```bash
git config --global core.autocrlf input
```

Windows users should use the following to auto-convert `CRLF` line endings into `LF` when you commit

```bash
git config --global core.autocrlf true
```

7. Confirm your global settings were saved

```bash
git config --list
```


<details>
<summary>Other Git configuration tips</summary>

<h2>Other tips</h2>

- [View settings and location of other config files](https://stackoverflow.com/a/46986031/441878) (system, global, local)

```bash
git config --list --show-origin
```

- Display the contents of the configuration file

```bash
cat ~/.gitconfig
```

</details>










## References

- [First-Time Git Setup](https://git-scm.com/book/ms/v2/Getting-Started-First-Time-Git-Setup) 
- [Installing Git – the easy way](https://gist.github.com/derhuerst/1b15ff4652a867391f03)
- [Merging vs. rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)

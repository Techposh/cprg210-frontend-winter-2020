# CRPG 210 Day 5
## Command Line Interface: Navigating the file system
[CLI (command line interface) Cheat Sheet](https://www.git-tower.com/blog/command-line-cheat-sheet/)

### The 3 commands you will use 80% of the time
- `pwd`: displays your 'present working directory'. This will usually default to your home folder when you first open your terminal.
- `ls`: lists the contents of your current directory. The `-l` flag lists extra information and `-a` lists hidden files. `-la` will list extra information and also all hidden files.
- `cd`: changes your directory based on the path you provide after the command (separated by a space). Examples:
  - `$ cd Documents/fast-track`
  - `$ cd /h/sait/fast-track`
  - `$ cd ../..`

Quality of life cli tips
- tab: auto-completes file names and directories
- up arrow: browse through command history

## Activity: [Configuring Git](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
- Setting your name
- Setting your email
- Setting up your keys (optional)
  - [Why does GitHub recommend HTTPS over SSH?](https://stackoverflow.com/questions/11041729/why-does-github-recommend-https-over-ssh)
  - [Generating a new SSH key and adding it to the ssh-agent](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

### Top Git commands
- `$ git init` - used only once to create a repo
- `$ git status`
- `$ git add`
- `$ git commit`
- `$ git push`
- `$ git pull`

### Creating a local repo

### Cloning a remote repo into a local repo

**Important: Do not create a repo inside another repo**

### Activity: Fork and clone the course repo to your system
1. Clone repo to your filesystem

## Live demo and Activity: GitHub pages

## Cloning a repo
### Option 1: Upload files to GH repo and clone to local repo
1. Create empty GH repo with initialized README.md
2. Click 'Upload Files' and drag/drop files into your repo
4. Clone repo to a new folder on your local system with `git clone`

### Option 2: Push existing local repo to empty GH repo
1. Create empty GH repo WITHOUT initialized README.md
2. Follow listed instructions for "*…or push an existing repository from the command line*"
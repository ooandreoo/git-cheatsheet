# Git cheatsheet

## Get git version
`git --version`

## Configure username and email

### Set name globally
`git config --global user.name "my name"`
### Set mail globally
`git config --global user.mail "myemail@mail.com`

## Help
`git help`

## Initialize a repository

### Initialize a new repository in current directory
`git init`

### Create new git repository in specified directory
`git init <directory>`

### Clone a repository from a remote server to local machine
`git clone <repository_url>`

### Clones a specific branch from a repository
`git clone --branch <branch_name> <repository_url>


## Basic Git Commands

### Add files to staging area

`git add <file>`
`git add .`
`git add -all`

### Shows current state of repository
`git status`
`git status --ignored`

### Shows changes between working directory and the staging area
`git diff`

### Show difference between 2 commits
`git diff <commit1> <commit2>`

### Show difference between staging area (index) and last commit
`git diff --staged`
`git diff --cached`

### Display difference between current directory and last commit
`git diff HEAD`

### Creates a new commit with the changes in the staging area and specifies commit message
`git commit -m "<message>"`

### Commits all modified and deleted files in the repository without explicitly using git add
`git commit -a`



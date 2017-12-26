# Git Cheat Sheet

## Clone the existing repositoty

```bash
git clone <CLONE_URL>

# Example
git clone https://github.com/JinnaBalu/GitCheatSheet.git
```

## Init the local git

```bash
git init
```

## Local Changes

##### Changed files in your working repo

```bash
git status
```

##### Chnages in tracked files

```bash
git status
```

##### Add all current changes 

```bash
git add --all
```

OR

```bash
git add .
```

##### commit all local changes in tracked files

```bash
git commit -am "my commit message"
```

**a-** all

**m-** message

## Commit History

##### Show all commits, starting with the newest

```bash
git log
```

##### Commit history of specific file

```bash
git log -p <file_name>

# EXAMPLE
git log -p README.md
```

##### Commit hitory by user

```bash
git blame <file_name>

#Example
git blame README.md
```

## Branches

##### List all local brnahces

```bash
git branch
```

##### List all local and remote brnahces

```bash
git branch -av
```

##### Switch to existing branch

```bash
git checkout <branch_name>

# Example
git checkout jinnabalu/testBranchName
```

##### Create a new branch

```bash
git checkout -b <brach_name>

# Example
git checkout -b jinnabalu/myNewBranchName
```

##### Delete local branch

```bash
git branch -d <branch_name>

# Example
git branch -d jinnabalu/myNewBranchName

## Force delete if not merged
git branch -D jinnabalu/myNewBranchName
```

##### Delete remote/origin branch

```bash
git push origin --delete <branch_name>

# Example
git push origin --delete jinnabalu/myNewBranchName
```

## Pull and Push


##### Get latest from remote

pull: gets latest pushed by someone to the branch

```bash
git pull
```

##### Push local changes

push: push local cahnges to the remote branch

```bash
git push -u origin <branch_name>

# Example
git push -u origin jinnabalu/myNewBranchName
```

## GIT MERGE

## GIT UNDO
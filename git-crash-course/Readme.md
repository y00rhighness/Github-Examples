
## Git Hidden Folder

There is a hidden folder called `.git` which tells you that our project is a git repo.

If we wanted to create a git repo in a new project we create the folder and then initialize that repo using `git init`

```
mkdir /workspaces/tmp/new-project
cd /workspaces/tmp/new-project
git init
touch Readme.md
open Readme.md
# makes changes to readme.md
git commit -a -m "add readme file"
```



## Cloning

We can clone three ways: HTTPS, SSH, Github CLI

Since we are using GitHub Codespaces, we'll create a temporary directory in our workspace

```sh
mkdir /workspace/tmp
cd /workspace/tmp
```

### HTTPS

```sh
git clone https://github.com/y00rhighness/Github-Examples.git
```

## Commits

When we want to commit code we can write git commit which will
open up the commit edit message in the editor of choice.

```
git commit
```

Set the global editor
```
git config --global core.editor emacs
```

Make a commit and commit message without opening an editor
```sh
git commit -m "add another exclamation"

## Branches

## Remotes

## Stashing

## Merging

## Add

When we want to stage changes that will be included in the commit
We can use the . to add all possible files.

## Reset


Reset allows you to move staged changes to be unstaged.
This is useful when you want to revert all files nt to be not committed

```
git add .
git reset
```

## Status

Git status shows you what files will or will not be committed.

```
git status
```

## Gitconfig file
The Gitconfig file is what stores your global configurations for
such as email, name, editor and more 

Showing the contents of our .gitconfig file
```
git config --1ist

```

When you first install Git on a machine you are supposed to set up 
your name and email

```sh
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

## Log

git log will show recent git commits to the git tree

## Push

When  we want to push a repo to our remote origin

```
git push
```

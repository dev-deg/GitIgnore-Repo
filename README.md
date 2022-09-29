# GitIgnore-Repo

Private GitIgnore Repo For Students

Include the releavant .gitignore file depending on your project.

# Notes

## Common Git Files

```bash
.git
.gitkeep
.gitignore
```

## Setting Default Branch to be Main

```bash
git config --global init.defaultBranch main
```

## Create local git repo

```bash
git init
```

## First Commit and Push to Main branch

```bash
git add *
git commit -a -m "commit desc"
git push -u origin main
```

## Subsequent Commit and Push to Main branch

```bash
git add *
git commit -a -m "commit desc"
git push
```

## Connecting your local repo to main branch in remote repo

```bash
git init
git remote add origin [url of repo]
git pull origin main
```

## Creating a GitIgnore File Using CLI

To create a .gitignore using Terminal, you can

Step1: Open PowerShell / Terminal and input the following:

```bash
cd [path where the gitignore file needs to be generated]
nano .gitignore
```

Step2: Paste the contents of the gitignore file.

Step3: Save the file.

```bash
CTRL + O
```

Press Enter key.

Step4: Exit.

```bash
CTRL + X
```

## Switching branch

To switch branch use git checkout. This command changes the default branch and updates the HEAD/origin.

```bash
git checkout name
```

## Creating a branch

To create branch and switch to it use checkout -b. Capital -B resets branch if it already exists.

```bash
git checkout -b name
```

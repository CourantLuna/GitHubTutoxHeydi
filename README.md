# GitHubTutoxHeydi
This repository keep files for example in video tutorial about basics of GitHub

Welcome to the git tuorial using Powershell from Windows

## Objetives

- Learn to create and manage repositories with Git.
- Understand the basic Git Workflow: `add`, `commit`, `push`, `fetch`, `pull`

## Creating a Repository

To start a new repository, use the command:

```bash
git init your_repository_name
```

#Adding Files
```bash
git add .

git add filename
```

## Committing Changes
Save your changes with:

```bash
git commit -m "My first commit"
```

## Connecting with Github
Link your local repository with a remote one:

```bash
git remote add origin <URL_of_the_remote_repository>
```

## Fetch changes of remote repository

```bash
git fetch origin master
```

## Pushing Changes
To push your changes to the remote repository, use:

```bash
git push -u origin master
```

## Updating Your Local Repository
To update your local repository with the last changes from the remote:

```bash
 git pull origin master
```




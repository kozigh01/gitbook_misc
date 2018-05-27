# Helpful Git Commands

### Github Flow

1. Create the git repository on github, such as:  
    https://github.com/kozigh01/introduction\_to\_es6.git
2. In local directory, initialize local git repository:
    `git init`
3. 
### Clone a repository

```text
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

### Create a new repository on command line:

```text
echo "# projectlist" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/kozigh01/projectlist.git
git push -u origin master
```

### Push existing repository on command line:

```text
git remote add origin https://github.com/kozigh01/projectlist.git
or
git remote add origin https://username:password@github.com/kozigh01/projectlist.git
or
git remote add origin https://username@github.com/kozigh01/projectlist.git

git push -u origin master
```

### Set tracking information for branch

```text
git branch --set-upstream-to=origin/<branch> master
or
git push --set-upstream origin master
```

### Checkout a branch

```text
git checkout -b test origin/test
```

### Fetch a branch

```text
git fetch origin
```

### Replace a remote

```text
git remote -v
git remote remove origin

git remote add origin https://username:password@github.com/kozigh01/projectlist.git
or
git remote add origin https://username@github.com/kozigh01/projectlist.git

git remote -v
```

### Github authentication on Windows using VS Code

```text
git config --global credential.helper wincred
  then restart VS Code
```

### Fork

[Syncing a fork](https://help.github.com/articles/syncing-a-fork/)


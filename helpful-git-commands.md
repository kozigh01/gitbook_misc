# Helpful Git Commands

### Connect local repo to Github

1. Create the git repository on github (using account 'myacct'), such as:  
    https://github.com/kozigh01/my-repository.git
2. In local directory:
    1. Initialize local git repository: `git init`
    2. Add remote (for github account 'myacct'): `git remote add origin https://myacct@github.com/kozigh01/my-repository.git`
    3. If needed, commit first local changes: 'git add .', 'git commit -m "Initial commit"
    4. Set tracking information: `git branch --set-upstream-to=origin/master master`
    5. Pull changes from remote: `git pull'
    6. Push changes to remote: `git push`
3. 
### Clone a repository

```text
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
roughly equivalent to:
```
mkdir repo
cd repo
git init
git remote add origin <url>
git fetch origin
git checkout master
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


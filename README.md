# GitHub tutorial
## Mostly used git commands

### Connect to github:
```bash
git config --global user.name <user name>
git config --global user.email <user email>
```

### To clone any GitHub repository:
```bash
git clone <repository link>
```

### Initialize the git in the local workspace and connect with the github:
```bash
git init
git add 'README.md'
git commit -m 'readme_file'
git branch -M main
git remote add origin <repository link>
```

### Adding a file to staging area:
```bash
# add single file:
git add <file name>
# add multiple file:
git add .
```

### Remove the file from the staging area:
```bash
# single file:
git reset <file name>
# multiple file:
git reset .
```

### Check the status:
```bash
git status
```

### Commiting the change:
```bash
git commit -m <'commit message'>
```

### To view all the versions of the commit:
```bash
# entire log message:
git log
# first line of the log message:
git log --oneline
```

### To show the particular commit change:
```bash
git show <particular commit id>
```

### Delete the file which is committed:
```bash
git revert <commit id>
```

### Check which branch you are working:
```bash
# current branch and list of all the branch:
git branch
```

### Creating a new branch:
```bash
git branch <new branch name>
```

### Switching to another branch:
```bash
git checkout <branch name>
```

### Merging two branch:
```bash
# Always merge the newly created branch with the main:
git merge <newly created branch name>
```

### To delete a branch:
```bash
git branch -d <branch name>
```

### Stash the code:
```bash
git stash
```

### List all the stash:
```bash
git stash list
```

### To retrive stached code from stash:
```bash
# you can get the stash id by executing "git stash list":
git stash apply <stash id of higgen code>
```

### To clear stash memory:
```bash
git stash clear
```

### Push all the changes to the github:
```bash
git push -u origin main
```

### Pull all the changes that happened in the github:
```bash
git pull
```
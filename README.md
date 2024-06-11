# GitHub tutorial:

## Mostly used git commands

1. Connect to github:
```bash
git config --global user.name <user name>
git config --global user.email <user email>
```

2. To clone any GitHub repository:
```bash
git clone <repository link>
```

3. Initialize the git in the local workspace and connect with the github:
```bash
git init
git add 'README.md'
git commit -m 'readme_file'
git branch -M main
git remote add origin <repository link>
```

4. Adding a file to staging area:
```bash
git add <file name>
```

5. Check the status
```bash
git status
```

6. Commiting the change:
```bash
git commit -m <'commit message'>
```

7. 
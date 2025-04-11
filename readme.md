Git Demo

# Commands

```
git init
git status
git add <file>
git commit -m "message"
clear
git log
git branch
git checkout -b <branch_name>
git merge <branch_name>
```
Common Commands
```
git add -A      # Add all files
```
## First Time Setup Process
1. Create a new repository on Github
    - ```git init```
2. Create and add an ignore file
    - ```touch .gitignore```
    - ```git add .gitignore```
3. Commit the changes
    - ```git commit -m "Initial Commit"```
    - ```git tag -a <tag_name> -m "message"```
4. Add the remote repository
    - ```git remote add origin <url>```
5. Push the changes to the remote repository
    - ```git push origin <branch_name>```

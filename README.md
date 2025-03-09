# Complete details to create and push code

# First create repo in your github account. 

## Quick setup ---if you've done this kind of thing before

## Select HTTPS link (if you not create readme.md file):

![as](https://github.com/user-attachments/assets/d1beb0cb-460d-4ca5-9451-dd216313b44a)

OR

![Screenshot 2025-03-10 000838](https://github.com/user-attachments/assets/77cca758-16cd-4d29-942d-3179a5b80309)

Now open you (Git bash) windows baseed software 
First time bash install you need to run this ***2*** commands
1. git config --global user.name InaamKhan11
2. git config --global user.email inaam1817@gmail.com

# create a new repository on the command line

1. echo "# github-reop-create-and-push" >> README.md  ***(if you want to create readme.md file OPTIONAL)***
2. git init
3. git add . ***(if you want to add all file then you can use . or you can type file name)***
4. git commit -m "first commit"  ***(you can type any thing in comment, this is a reminder, what purpose for push this files and code)***
5. git branch -M main
6. git remote add origin https://github.com/InaamKhan11/github-reop-create-and-push.git
7. git push -u origin main

# Push an existing repository from the command line
1. git remote add origin https://github.com/InaamKhan11/github-reop-create-and-push.git
2. git branch -M main
3. git push -u origin main

# Push updated code in repository you created
1. git add .
2. git commit -m "***Enter message here***"
3. git push

## done


-------------------
-------------------
-------------------

# Git Usefull Commands For Beginners


## 1. Git Configuration
git config --global user.name "YourName"
git config --global user.email "your-email@example.com"
git config --global --list  # Check current config settings

👉 Sets up your Git username and email globally.
________
## 2. Initialize a Git Repository
git init

👉 Initializes a new Git repository in the current folder.
___________
## 3. Clone a Repository
git clone <repo-url>

👉 Copies a remote repository to your local machine.
_______________
## 4. Check Repository Status
git status

👉 Shows the current state of your working directory (modified, staged, or untracked files).
________________
## 5. Add Files to Staging Area
git add <filename>    # Add a specific file  
git add .             # Add all changed files  

👉 Stages changes for the next commit.
______________

## 6. Commit Changes
git commit -m "Your commit message"

👉 Saves the staged changes with a message describing what was changed.
_____________

## 7. View Commit History
git log

👉 Shows the commit history.
_________

## 8. View Changes (Before Commit)
git diff

👉 Shows changes made to files before committing.
_______________

## 9. Create and Switch Branches
git branch <branch-name>  # Create a new branch  
git checkout <branch-name>  # Switch to another branch  
git checkout -b <branch-name>  # Create and switch to new branch  
git branch -d <branch-name>  # Delete a branch  

👉 Helps manage multiple versions of your project.
___________

## 10. Merge Branches
git checkout main  
git merge <branch-name>  

👉 Merges another branch into the main branch.
_____________

## 11. Push to Remote Repository (GitHub, etc.)
git push origin <branch-name>
👉 Uploads commits to the remote repository.
________________________

## 12. Pull Latest Changes from Remote
git pull origin <branch-name>
👉 Updates your local repository with the latest changes from the remote repository.
______________________

## 13. Reset and Undo Changes
git reset --hard <commit-id>  # Reset to a previous commit (removes changes permanently)
git reset --soft <commit-id>  # Reset to a previous commit but keep changes staged  
git checkout -- <filename>  # Discard changes in a specific file  
👉 Used to undo changes in different ways.
______________________

## 14. Stash Changes (Temporarily Save Uncommitted Changes)
git stash  
git stash pop  # Apply stashed changes back  
👉 Saves your uncommitted changes temporarily without committing them.
______________________

## 15. Remove Files from Git
git rm <filename>  # Remove a file from tracking and delete it  
git rm --cached <filename>  # Remove from tracking but keep it locally  
👉 Removes files from Git tracking.
______________________
## 16. Add Remote Repository
git remote add origin <repo-url>
👉 Links your local repository to a remote one.
______________________

## 17. Check Remote URL
git remote -v
👉 Shows the remote repository URL.
______________________

## 18. Set Upstream Branch for Pushing
git push --set-upstream origin <branch-name>
👉 Sets up tracking for a branch, so you don’t have to specify the remote every time.
______________________

## 19. Rename Last Commit (Before Pushing)
git commit --amend -m "New commit message"
👉 Updates the last commit message.
______________________

## 20. Delete a Git Repository (Be Careful!)
rm -rf .git
👉 Removes Git tracking from a folder.

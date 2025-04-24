### **Basic Git Concepts** 

1.  **Repository (Repo)**
    A project folder that git is tracking . Can be **Local** or **remote**
2. **Version Control**
    A system that tracks changes to code over time, letting you revert to previous versions 
3. **Commit**
    A snapshot of your changes.
4. **Working Directory**
    The current stat of your files on disk.
5. **Staging Area**
    Where you prepare changes before committing 

---

### **Common Commands**

6. `git init`
    Initializes a new Git repository in a folder.
7.  `git status`
    Shows the current state of the working directory and staging area
8. `git add <file>`
    Stages changes in a file for the next commit.
9. `git commit -m "message" `
    Saves the staged changes with a commit message 
10. `git push` 
    Sends local commit to the remote repo
11. `git pull ` 
    Fetches and merges changes from the remote to local repo
12. `git fetch`
    Dowloads changes from the remote
13. `git clone <repo>`
    clones a reomte repo to local machine
14. `git merge`
    Merges changes from one branch into another
---
### **git.ignore**
    Use `git.ignore` to specify files that shouldnt be tracked/commited by git.
    Once a file is tracked by git, adding it to .gitignore wont remove it. You need to untrack it with git rm--cached
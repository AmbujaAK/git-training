# 1) git config
### **Utility :** To set your user name and email in the main configuration file.

**How to :** To check your name and email 
```
git config --global user.name
git config --global user.email
```
And to set your new email or name 
```
git config --global user.name = “Dhruv Nenwani” 
git config --global user.email = “nendhruv@gmail.com”
```
# 2) git init
### **Utility :** To initialise a git repository for a new or existing project.
**How to :** git init in the root of your project directory.
```
git init
```

# 3) git clone
### **Utility :** To copy a git repository from remote source, also sets the remote to original source so that you can pull again.
**How to :** clone any git repo
```
git clone "https://github.com/AmbujaAK/HelloAzure.git"
```
# 4) git status
### **Utility :** To check the status of files you’ve changed in your working directory, i.e, what all has changed since your last commit.
**How to :** git status in your working directory. lists out all the files that have been changed.
```
git status
```

# 5) git add
### **Utility :** adds changes to stage/index in your working directory.
**How to :** 
```
git add .
git add --all
git add fileName.txt
git add -u //without new files
```

# 6) git commit
### **Utility :** commits your changes and sets it to new commit object for your remote.
**How to :** 
```
git commit -m "some message"
```
# 7) git push/git pull
### **Utility :** Push or Pull your changes to remote. If you have added and committed your changes and you want to push them. Or if your remote has updated and you want those latest changes.
**How to :** 
```
git pull <:remote:> <:branch:>
git push <:remote:> <:branch:>
```

# 8) git branch
### **Utility :** Lists out all the branches.
**How to :** git branch or git branch -a to list all the remote branches as well.
```
git branch
git branch -a
git branch <:new branch:>
git branch -d <:old branch:>
```

# 9) git checkout/switch
### **Utility :** Switch to different branches
**How to :** git checkout <:branch:> or **_git checkout -b <:branch:> if you want to create and switch to a new branch.
```
git checkout <:branch:>
git switch <:branch:>
```

# 10) git stash
### **Utility :** Save changes that you don’t want to commit immediately.
**How to :** git stash in your working directory. git stash apply if you want to bring your saved changes back.
```
git stash
```

# 11) git merge
### **Utility :** Merge two branches you were working on. (Three types)
**How to :** Switch to branch you want to merge everything in. 
```
git merge <:branch_you_want_to_merge:>
```

# 12) git reset
### **Utility :** You know when you commit changes that are not complete, this sets your index to the latest commit that you want to work on with.
**How to :** 
```
git reset <:mode:> <:COMMIT:>
```

# 13) git remote
### **Utility :** To check what remote/source you have or add a new remote.
**How to :** git remote to check and list. And 
```
git remote add <:remote_url:>
```

# 14) git ignore
### **Utility :** untracked files that Git should ignore. 
**How to :** 
```
cat .gitignore
.class
targets/
**/.war
```
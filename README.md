# Task1esm
🧾 ALL IMPORTANT GIT BASH COMMANDS
# 🔹 Basic System / Bash Commands
pwd          # show current directory
ls           # list files and folders
ls -a        # list all files (including hidden)
cd folder    # move into folder
cd ..        # go back one folder
mkdir name   # create folder
touch file   # create file
rm file      # delete file
rm -r folder # delete folder
clear        # clear terminal

# 🔹 Git Configuration Commands
git --version
git config --global user.name "Your Name"
git config --global user.email "you@email.com"
git config --list

# 🔹 Repository Setup
git init
git clone <repository-url>

# 🔹 Status & Tracking
git status
git add file
git add .
git reset file
git reset

# 🔹 Commit Commands
git commit -m "message"
git commit -am "message"
git log
git log --oneline

# 🔹 Branch Commands
git branch
git branch abt
git checkout abt
git checkout -b bash
git branch -d abt

# 🔹 Remote (GitHub) Commands
git remote -v
git remote add origin <url>
git remote remove origin

# 🔹 Push & Pull
git push origin main
git push origin abt
git pull origin main
git pull origin abt
git pull origin abt --rebase

# 🔹 Merge & Rebase
git merge abt
git merge --abort
git rebase abt
git rebase --continue

# 🔹 Stash Commands
git stash
git stash list
git stash apply
git stash drop

# 🔹 Undo / Fix Mistakes
git checkout -- file
git reset --hard
git revert <commit-id>

# 🔹 Delete from GitHub (but keep local)
git rm --cached file
git commit -m "remove file from repo"

# 🔹 Helpful Shortcuts
git diff
git show
git fetch

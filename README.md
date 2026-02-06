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

# About Me

## 👋 Introduction
Hello! My name is Krish Durugkar.  
I am a student learning Git, GitHub, and basic development tools.  
This repository is created to practice version control, branching, and command usage.

---

## 🎯 Objective
- Learn Git and GitHub basics
- Understand branching and merging
- Practice writing README files in each folder
- Improve command-line skills

---

## 🛠️ Basic & Important Git Commands

### 1. Check Git version

```bash
git --version

#2. Initialize a Git repository
git init

#3. Check current status
git status
#4. Add files to staging area
git add .

#5. Commit changes
git commit -m "about me updated"

#6. Create a new branch
git branch abt

#7. Switch to branch
git checkout abt

#8. Pull latest changes from GitHub
git pull origin abt

#9. Push changes to GitHub
git push origin abt
# hello krishu
# kkkk
<h1> krish <h1>
THESE WAS Final change 
# # Industrial Training – Web Technology & MERN Stack

This repository is created as part of the Industrial Training program
conducted by **ESM Company** at our college.

The purpose of this repository is to practice Git and GitHub operations
such as cloning, pulling, pushing, and managing repositories while
learning Web Technology and the MERN Stack.

---

## 👨‍🎓 Student Information
- Name: Krish Durugkar
- Course: Engineering Student
- Training Program: Web Technology & MERN Stack
- Company: Elixer

---

## 🎯 Training Objectives
- Understand basics of Web Technology
- Learn MERN Stack fundamentals
- Practice Git and GitHub workflow
- Perform clone, pull, push operations
- Maintain proper README files

---

## 🛠️ Tasks Performed
- Created GitHub repository
- Cloned repository to local system
- Added and modified files
- Committed changes using Git
- Pushed changes to GitHub
- Pulled updates from remote repository

---

## 🔧 Technologies Introduced
- HTML
- CSS
- JavaScript
- Git & GitHub
- MERN Stack (MongoDB, Express, React, Node.js)

---

## 📌 Note
This repository is maintained for learning and practice purposes
as part of the Industrial Training program. 


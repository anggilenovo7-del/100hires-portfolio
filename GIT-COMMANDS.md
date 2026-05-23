# Git Commands Used in This Project

This document explains the Git commands used throughout this portfolio project,
including what each command does and why it was used.

---

## What is Git?
Git is a version control system that tracks changes in files over time.
It allows developers to save progress, collaborate with others, and
maintain a history of all changes made to a project.

---

## What is GitHub?
GitHub is a cloud-based platform that hosts Git repositories online.
It makes it easy to share code publicly and collaborate with other developers.

---

## Commands Used

### 1. `git clone`
```bash
git clone https://github.com/username/100hires-portfolio.git
```
**What it does:** Downloads a copy of the remote repository to your computer.
**When I used it:** After creating the repository on GitHub, I cloned it
to my local machine so I could edit files in Cursor.

---

### 2. `git add`
```bash
git add .
```
**What it does:** Stages all changed files, preparing them to be committed.
The `.` means "add everything in the current folder".
**When I used it:** Before every commit, to include all new or edited files.

---

### 3. `git commit`
```bash
git commit -m "Add README with screenshots"
```
**What it does:** Saves a snapshot of the staged changes with a message
describing what was changed.
**When I used it:** After adding or editing files, to save progress locally.

> 💡 Tip: Write commit messages that clearly describe what changed.

---

### 4. `git push`
```bash
git push
```
**What it does:** Uploads your local commits to the remote repository on GitHub,
making your changes visible online.
**When I used it:** After committing, to sync my local changes to GitHub.

---

### 5. `git status`
```bash
git status
```
**What it does:** Shows which files have been changed, staged, or are
untracked. Useful for checking the current state before committing.
**When I used it:** To verify which files were ready to be committed.

---

## Full Workflow Used in This Project

```bash
# 1. Clone the repository
git clone https://github.com/username/100hires-portfolio.git

# 2. Make changes to files in Cursor

# 3. Check what changed
git status

# 4. Stage all changes
git add .

# 5. Save a snapshot with a message
git commit -m "Your commit message here"

# 6. Upload to GitHub
git push
```

---

## Result
Successfully used Git to clone, commit, and push files to a public
GitHub repository.

---

*Part of the 100Hires Portfolio Project — [Back to Main README](README.md)*
# **Git Commands Cheat Sheet**

This file contains commonly used Git commands with brief explanations.

---

## **1. Getting Started with Git**

- **Initialize a Git repository**:

  `git init`

- **Clone an existing repository**:

  `git clone <repository_url>`

- **Add a remote repository**:

  `git remote add origin <repository_url>`

---

## **2. Basic Git Commands**

- **Check the status of files**:

  `git status`

- **Stage files for commit**:

  `git add <file>`      # Add specific file

  `git add .`           # Add all changes

- **Commit changes**:

  `git commit -m "Commit message"`

- **Push commits to a remote repository**:

  `git push origin <branch_name>`

- **Pull changes from a remote repository**:

  `git pull`

---

## **3. Branching and Merging**

- **Create a new branch**:

  `git branch <branch_name>`

- **Switch to a branch**:

  `git checkout <branch_name>`

- **Create and switch to a new branch**:

  `git checkout -b <branch_name>`

- **Merge a branch into the current branch**:

  `git merge <branch_name>`

- **Delete a branch**:

  `git branch -d <branch_name>`

---

## **4. Viewing History and Logs**

- **View commit history**:

  `git log`

- **View commit history in a single line**:

  `git log --oneline`

- **View commit history with a graph**:

  `git log --graph --oneline`

---

## **5. Undoing Changes**

- **Unstage a file**:

  `git reset <file>`

- **Revert a commit**:

  `git revert <commit_hash>`

- **Discard local changes to a file**:

  `git checkout -- <file>`

---

## **6. Working with Remotes**

- **List remote repositories**:

  `git remote -v`

- **Show information about a remote**:

  `git remote show origin`

- **Push tags to a remote repository**:

  `git push origin --tags`

---

## **7. Stashing**

- **Save uncommitted changes temporarily**:

  `git stash`

- **Apply stashed changes**:

  `git stash apply`

---

## **8. Tagging**

- **Create a tag**:

  `git tag <tag_name>`

- **Push tags to a remote repository**:

  `git push origin <tag_name>`

  `git push --tags`   # Push all tags

---

## **9. Git Help**

- **Get help on Git commands**:

  `git help <command>`

---

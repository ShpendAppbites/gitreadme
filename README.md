# Comprehensive Git and GitHub Commands Guide

This guide provides a complete list of **Git** and **GitHub** commands, from the basics to advanced functionality. Perfect for learning or as a quick reference!

---

## **Basic Git Commands**

### **1. Initializing and Configuring**

- `git init` - Initialize a new Git repository in the current directory.
- `git config --global user.name "Your Name"` - Set the username for all repositories on the system.
- `git config --global user.email "you@example.com"` - Set the email for all repositories on the system.

### **2. Checking Status and Logs**

- `git status` - Show the working tree status.
- `git log` - Display commit history for the repository.

### **3. Staging and Committing**

- `git add <file>` - Stage a specific file for commit.
- `git add .` - Stage all changed files.
- `git commit -m "commit message"` - Commit staged changes with a message.
- `git commit --amend` - Edit the last commit message.

---

## **Branching and Merging**

### **1. Creating and Switching Branches**

- `git branch <branch-name>` - Create a new branch.
- `git checkout <branch-name>` - Switch to an existing branch.
- `git checkout -b <branch-name>` - Create and switch to a new branch.

### **2. Merging Branches**

- `git merge <branch-name>` - Merge a branch into the current branch.
- `git merge --no-ff <branch-name>` - Force a merge commit even if it’s a fast-forward merge.

### **3. Rebase (Advanced)**

- `git rebase <branch>` - Reapply commits on top of another branch.
- `git rebase -i <branch>` - Interactively rebase, allowing you to edit commits.

---

## **Remote Repositories**

### **1. Connecting and Managing Remotes**

- `git remote add origin <url>` - Connect a local repo to a remote repository.
- `git remote -v` - View all remote URLs.

### **2. Fetching and Pulling Changes**

- `git fetch` - Download changes from the remote without merging.
- `git pull` - Fetch and merge changes from the remote branch into the current branch.

### **3. Pushing Changes**

- `git push origin <branch>` - Push changes to the remote repository.

---

## **Stashing and Cleaning**

### **1. Stashing Changes**

- `git stash` - Save uncommitted changes for later use.
- `git stash list` - List all stashed changes.
- `git stash pop` - Apply the latest stash and remove it from the stash list.

### **2. Cleaning the Working Directory**

- `git clean -f` - Remove untracked files.
- `git clean -fd` - Remove untracked files and directories.

---

## **Viewing Differences**

### **1. Comparing Changes**

- `git diff` - Show changes in the working directory.
- `git diff --staged` - Show changes between the staging area and the last commit.

### **2. Blame (See who changed each line)**

- `git blame <file>` - Show who last modified each line of a file.

---

## **Undoing Changes**

### **1. Resetting Changes**

- `git reset <file>` - Unstage a file without discarding changes.
- `git reset --hard <commit>` - Reset the repository to a specific commit, discarding changes.

### **2. Reverting Commits**

- `git revert <commit>` - Create a new commit that undoes a specific commit.

---

## **Advanced GitHub Commands (GitHub CLI)**

### **1. Pull Requests**

- `gh pr create` - Create a new pull request.
- `gh pr list` - List all pull requests.
- `gh pr merge <PR-number>` - Merge a pull request.

### **2. Issue Management**

- `gh issue create` - Create a new issue.
- `gh issue list` - List all issues.

### **3. Cloning and Forking Repositories**

- `git clone <url>` - Clone a remote repository to your local machine.
- `gh repo fork <repo>` - Fork a repository on GitHub.

---

## **Git Tagging**

- `git tag <tag-name>` - Create a new tag.
- `git tag -a <tag-name> -m "message"` - Create an annotated tag.
- `git push origin <tag-name>` - Push a tag to the remote repository.

---

This guide should cover all essential Git and GitHub commands you may need. Happy coding and experimenting with version control!

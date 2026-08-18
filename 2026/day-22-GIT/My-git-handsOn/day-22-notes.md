## Challenge Tasks

### Task 1: Install and Configure Git
1. Verify Git is installed on your machine
2. Set up your Git identity — name and email
3. Verify your configuration

![alt text](../images/Task1.png)

---

### Task 2: Create Your Git Project
1. Create a new folder called `devops-git-practice`
2. Initialize it as a Git repository
3. Check the status — read and understand what Git is telling you
4. Explore the hidden `.git/` directory — look at what's inside

![alt text](../images/Task2.png)

---

### Task 3: Create Your Git Commands Reference
1. Create a file called `git-commands.md` inside the repo
2. Add the Git commands you've used so far, organized by category:
   - **Setup & Config**
   - **Basic Workflow**
   - **Viewing Changes**
3. For each command, write:
   - What it does (1git config --global user.email "you@example.com"
Sets your email for commits.

Example:

bash
git config --global user.email "jeet@example.com"
git config --list
Displays all Git configuration.

Example:

bash
git config --list
Basic Workflow
git init
Initializes a new Git repository.

Example:

bash
git init
git clone <repo-url>
Clones an existing repository.

Example:

bash
git clone https://github.com/user/repo.git
git add <file>
Stages changes for commit.

Example:

bash
git add file.txt
git commit -m "message"
Saves staged changes with a commit message.

Example:

bash
git commit -m "Initial commit"
git push origin main
Pushes commits to the remote repository.

Example:

bash
git push origin main
git pull origin main
Fetches and merges changes from remote.

Example:

bash
git pull origin main
Viewing Changes
git status
Shows the working directory status.

Example:

bash
git status
git log
Displays commit history.

Example:

bash
git log
git log --oneline --graph --decorate
Shows compact commit history with branch graph.

Example:

bash
git log --oneline --graph --decorate
git diff
Shows changes between commits or working directory.

Example:

bash
git diff
Quick Summary
Setup: git config

Start: git init, git clone

Work: git add, git commit

Remote: git push, git pull

View: git status, git log, git diff line)
   - An example of how to use it



---

### Task 4: Stage and Commit
1. Stage your file
2. Check what's staged
3. Commit with a meaningful message
4. View your commit history

---

### Task 5: Make More Changes and Build History
1. Edit `git-commands.md` — add more commands as you discover them
2. Check what changed since your last commit
3. Stage and commit again with a different, descriptive message
4. Repeat this process at least **3 times** so you have multiple commits in your history
5. View the full history in a compact format

---

### Task 6: Understand the Git Workflow
Answer these questions in your own words (add them to a `day-22-notes.md` file):
1. What is the difference between `git add` and `git commit`?
2. What does the **staging area** do? Why doesn't Git just commit directly?
3. What information does `git log` show you?
4. What is the `.git/` folder and what happens if you delete it?
5. What is the difference between a **working directory**, **staging area**, and **repository**?

---

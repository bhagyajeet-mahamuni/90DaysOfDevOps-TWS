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

# Git Commands

## Setup & Config

### git init
- Initializes a new Git repository.
- **Example**:
```bash
git init
```

### git config

* Configures Git username or email.
* **Example**:

```bash
git config --global user.name "Your Name"
git config --global user.email "Your Email"
```

* View Config Values
* **Example**:

```bash
git config --global --list
```

---

## Basic Workflow

### git add

* Stages changes for commit.
* **Example**:

```bash
git add file.txt
```

### git commit

* Saves staged changes with a commit message.
* **Example**:

```bash
git commit -m "Initial commit"
```

### git push

* Uploads local commits to the remote repository.
* **Example**:

```bash
git push origin main
```

### git pull

* Fetches and merges changes from the remote repository.
* **Example**:

```bash
git pull origin main
```

---

## Viewing Changes

### git status

* Shows the working directory status.
* **Example**:

```bash
git status
```

### git log

* Displays commit history.
* **Example**:

```bash
git log
```

### git log --oneline --graph --decorate

* Shows compact commit history with branch graph.
* **Example**:

```bash
git log --oneline --graph --decorate
```

### git diff

* Shows changes between commits or working directory.
* **Example**:

```bash
git diff
```

```

---------------------


## Task 3: Create Your Git Commands Reference

Here is a concise Git commands reference to help you quickly recall essential commands:

### Setup & Configuration
- `git init`: Initialize a new Git repository.
- `git config --global user.name "Your Name"`: Set your Git username.
- `git config --global user.email "Your Email"`: Set your Git email.
- `git config --global --list`: View all global Git configurations.

### Basic Workflow
- `git add <file>`: Stage changes for commit.
- `git commit -m "message"`: Commit staged changes with a message.
- `git push origin <branch>`: Push commits to remote branch.
- `git pull origin <branch>`: Fetch and merge changes from remote.

### Branching
- `git branch`: List all branches.
- `git branch <branch>`: Create a new branch.
- `git checkout <branch>`: Switch to a branch.
- `git checkout -b <branch>`: Create and switch to a new branch.
- `git merge <branch>`: Merge a branch into the current branch.

### Viewing Changes
- `git status`: Show working directory status.
- `git log`: Show commit history.
- `git log --oneline --graph --decorate`: Show compact commit history with graph.
- `git diff`: Show changes between commits or working directory.

### Undo & Stash
- `git reset --hard`: Discard all local changes.
- `git stash`: Temporarily save changes.
- `git stash pop`: Apply stashed changes and remove stash.

This reference covers the most common Git commands you’ll use daily. Keep it handy for quick lookup!

```


### Task 4: Stage and Commit
1. Stage your file
2. Check what's staged
3. Commit with a meaningful message
4. View your commit history

![alt text](../images/Task3.png)
![alt text](../images/Task3-1.png)

---

### Task 5: Make More Changes and Build History
1. Edit `git-commands.md` — add more commands as you discover them
2. Check what changed since your last commit
3. Stage and commit again with a different, descriptive message
4. Repeat this process at least **3 times** so you have multiple commits in your history
5. View the full history in a compact format

![alt text](../images/Task4.png)

---

### Task 6: Understand the Git Workflow
Answer these questions in your own words (add them to a `day-22-notes.md` file):

1. What is the difference between `git add` and `git commit`?
  . git add is used to move the file from untrack area to staging area so it will move further to local repo and remote repo accordingly.
    git commit is used to move the files from staging area to track area , once the file is added in it, we will able to track it or able to recover it if its get deleted.

2. What does the **staging area** do? Why doesn't Git just commit directly?
  . staging is the area where files has been kept before actual commit haapens, where we will see what is going to be commited and if anything is unwanted then we can reassign back to the untrack stage. This will may be an extra check point before commit happens.
  . Git will not perfrom any commit by it's own, rather we have to manually perfrom it according to our requirements and its benficial for us to avaoid any accidental or unwanted commit.

3. What information does `git log` show you?
  . git log will give all the information of the changes which we have performed on that folder also is included commit ids which uses Crypographic hasing algorith to get unique commit id, also we will be able to see local and remote repo levels like they are on same level or up and down also we will able to see the comment message,author,date,brach details etc etc to track the acitivities.

4. What is the `.git/` folder and what happens if you delete it?
  . .git folder is kind of monitor of the class, who monitors all the details happening on the repository it tracts all the activiy like file creation, modification, deletion, restoration of files and folder which are inside the git directory.
  If we delete the .git folder , git will not perfrom their task like it will not monitor the any updation , deletion, retention of files under that direcoty. 

5. What is the difference between a **working directory**, **staging area**, and **repository**?
  
     **working directory** : This is the directory where all changes happens.

     **staging area** : This is the area where we keep all our files before commit.

     **repository** : This is the area where your all files inside it get tracked so anything intentially or unintentially happened with them we are in palce to recover them successfully.

---

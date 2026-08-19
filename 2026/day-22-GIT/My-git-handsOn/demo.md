
# Git Commands Reference

## Repository Setup
### git init
- Initialize a new Git repository.
- **Example**: `git init`

### git remote -v
- Show remote repositories linked to your local repo.
- **Example**: `git remote -v`

### git remote set-url origin <url>
- Change the URL of the remote named `origin`.
- **Example**:  
  `git remote set-url origin git@github.com:user/repo.git`

---

## Configuration (After completing this step, Git will correctly identify the author for each commit record.)
### git config --global user.name "Name"
- Set global username for commits.

### git config --global user.email "email@example.com"
- Set global email for commits.

### git config --global --list
- Show all global Git configuration settings.

### git config user.name
- Show the local repo’s username.

### git config user.email
- Show the local repo’s email.

---

## Basic Workflow
### git status
- Show working directory status (staged/unstaged changes).

### git add .
- Stage all changes in the current directory.

### git add <file>
- Stage a specific file.
- **Example**: `git add demo_file.txt`

### git commit -m "message"
- Save staged changes with a commit message.
- **Example**: `git commit -m "Initial commit"`

### git push origin main
- Push commits to the remote `main` branch.

### git push origin master
- Push commits to the remote `master` branch.

### git push
- Push commits to the default remote branch.

---

## Viewing History & Differences
### git log
- Show commit history.

### git log --oneline
- Show compact commit history.

### git log --oneline -N
- Show last N commits in compact form.
- **Example**: `git log --oneline -4`

### git diff
- Show differences between working directory and last commit.

---

# ✅ Quick Notes
- **Setup:** `git init`, `git remote`, `git config`
- **Workflow:** `git add`, `git commit`, `git push`
- **Viewing:** `git status`, `git log`, `git diff`

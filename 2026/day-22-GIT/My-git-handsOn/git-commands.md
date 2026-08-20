# Git Revision Cheat Sheet

## Module 1 — Foundations
- `git init` → Start a new repository  
  *Example:* `git init`
- `git config` → Set user details  
  *Example:* `git config --global user.name "Jeet"`
- `git status` → Show current changes  
  *Example:* `git status`
- `git add` → Stage files for commit  
  *Example:* `git add A.txt`
- `git commit` → Save changes to repo  
  *Example:* `git commit -m "Added A.txt"`
- `git rm` → Remove tracked file  
  *Example:* `git rm B.txt`
- `.gitignore` → Ignore files from tracking  
  *Example:* add `*.log` in `.gitignore`

---

## Module 2 — Branching
- `git branch` → List branches  
  *Example:* `git branch`
- `git checkout -b` → Create & switch branch  
  *Example:* `git checkout -b feature/login`
- `git switch -c` → Modern way to create & switch  
  *Example:* `git switch -c bugfix`
- `git branch -d` → Delete branch  
  *Example:* `git branch -d old-feature`

---

## Module 3 — GitHub Basics
- `git clone` → Copy repo from remote  
  *Example:* `git clone https://github.com/user/repo.git`
- `git push` → Upload commits to remote  
  *Example:* `git push origin main`
- `git pull` → Download changes from remote  
  *Example:* `git pull origin main`
- `git push -u` → Set tracking branch  
  *Example:* `git push -u origin feature/login`

---

## Module 4 — Integrating Work
- `git merge` → Combine branches  
  *Example:* `git merge feature/login`
- `git rebase` → Replay commits on another branch  
  *Example:* `git rebase main`
- `git merge --squash` → Squash multiple commits into one  
  *Example:* `git merge --squash feature/login`

---

## Module 5 — Undoing & Recovering
- `git reset --soft` → Move HEAD back, keep changes staged  
  *Example:* `git reset --soft HEAD~1`
- `git reset --hard` → Move HEAD back, discard changes  
  *Example:* `git reset --hard HEAD~1`
- `git revert` → Undo commit safely (new commit created)  
  *Example:* `git revert HEAD`
- `git reflog` → Show HEAD history  
  *Example:* `git reflog`
- `git commit --amend` → Edit last commit  
  *Example:* `git commit --amend -m "Updated message"`

---

## Module 6 — Surgical & Saving Work
- `git cherry-pick` → Apply specific commit to branch  
  *Example:* `git cherry-pick abc123`
- `git stash` → Save changes temporarily  
  *Example:* `git stash`
- `git stash pop` → Restore stashed changes  
  *Example:* `git stash pop`

---

## Module 7 — Collaboration & Safety
- Pull Request → Request to merge on GitHub  
- Conflict resolution → Fix merge conflicts  
  *Example:* resolve `<<<<<<< HEAD ... ======= ... >>>>>>> branch`
- `git push --force-with-lease` → Safe force push  
  *Example:* `git push --force-with-lease`
- Branching strategies → GitHub Flow, trunk‑based development

---

### 🎯 Revision Mantra
*Init → Config → Add → Commit → Branch → Merge/Rebase → Push/Pull → Undo → Stash → Collaborate*

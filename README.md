# 📘 Git Commands Guide

## 🔧 Setup & Configuration

```bash
git config --global user.name "Your Name"       # Set Git username
git config --global user.email "you@example.com" # Set Git email
git config --global core.editor code             # Set VSCode as default editor
git config --list                                 # View current config
```

---

## 📁 Repository Initialization & Info

```bash
git init                  # Initialize a new Git repository
git clone <repo-url>     # Clone an existing repository
git status               # Show file status
git log                  # Show commit history
git show                 # Show details of latest or specific commit
```

---

## 🧑‍💻 Working with Files

```bash
git add <file>           # Stage a file
git add .                # Stage all changes
git reset <file>         # Unstage a file
git checkout -- <file>   # Discard local changes to a file
```

---

## ✅ Commit Changes

```bash
git add .                # Stage all changes
git commit -am "Message"     # Add and commit tracked files in one step
```

---

## 🔄 Branching

```bash
git branch                    # List all branches
git branch <name>            # Create a new branch
git switch <branch>          # Newer way to switch branches
git <name>       # Create and switch to new branch
git merge <branch>           # Merge branch into current branch
git branch -d <name>         # Delete a branch
```

---

## ⬆️ Push & ⬇️ Pull

```bash
git remote add origin <url>     # Add remote repository
git push -u origin <branch>     # Push branch for the first time
git push                        # Push changes
git pull                        # Pull latest changes
git fetch                       # Fetch changes without merging
```

---

## 🕵️ Undo & Fix

```bash
git revert <commit>             # Revert a specific commit
git reset --soft <commit>       # Reset to commit (keep changes staged)
git reset --hard <commit>       # Reset to commit (discard all changes)
git stash                       # Save uncommitted changes
git stash pop                   # Reapply last stashed changes
```

---

## 🌍 Tagging

```bash
git tag                         # List all tags
git tag <name>                  # Create a new tag
git push origin <tag>           # Push tag to remote
```

---

## 🔎 Useful Extras

```bash
git diff                        # Show file differences
git diff --staged              # Show staged file differences
git log --oneline              # One-line summary of commits
git reflog                     # Show history of HEAD and branches
```

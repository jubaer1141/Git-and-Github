# ⚡ Common Git Commands (Quick Cheat Sheet)

This is a quick reference of the most commonly used **Git commands**.

---

## 🚀 Basic Workflow

```bash id="a1b2c3"
git init
git add .
git commit -m "your message"
git push
```

---

## 📌 Repository Setup

```bash id="d4e5f6"
git init                     # Initialize Git in a folder
git remote add origin URL   # Connect to GitHub repository
git branch -M main          # Set branch name to main
```

---

## ➕ Adding Files

```bash id="g7h8i9"
git add .        # Add all files
git add file.txt # Add specific file
```

---

## 💾 Commit Changes

```bash id="j1k2l3"
git commit -m "message"
```

---

## 🚀 Push & Pull

```bash id="m4n5o6"
git push                 # Upload changes
git push -u origin main  # First push
git pull                 # Get latest updates
```

---

## 🔍 Check Status

```bash id="p7q8r9"
git status   # Show current changes
git log      # Show commit history
```

---

## 🔄 Branch Commands

```bash id="s1t2u3"
git branch            # Show branches
git branch new-branch # Create new branch
git checkout branch   # Switch branch
```

---

## ❌ Undo Changes

```bash id="v4w5x6"
git restore file.txt     # Undo file changes
git reset HEAD file.txt  # Unstage file
```

---

## 🧹 Clean & Reset (Use Carefully)

```bash id="y7z8a9"
git clean -f        # Remove untracked files
git reset --hard    # Reset everything
```

---

## 💡 Tips

* Use `git status` often to understand what’s happening
* Write clear commit messages
* Don’t use `reset --hard` unless you understand it

---

## 🎯 Quick Reminder

```bash id="b1c2d3"
git add .
git commit -m "update"
git push
```

---

Keep this file as your **daily Git reference** 🚀

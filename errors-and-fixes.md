# ⚠️ Git & GitHub Errors and Fixes

This guide helps you solve common errors faced by beginners while using Git and GitHub.

---

## ❌ 1. Git is not recognized

### 🔴 Error:

```bash id="a9b1c2"
'git' is not recognized as an internal or external command
```

### ✅ Fix:

* Restart your computer
* Reinstall Git from: https://git-scm.com/
* Make sure **“Add Git to PATH”** is selected during installation

---

## ❌ 2. Permission denied (GitHub)

### 🔴 Error:

```bash id="d3e4f5"
Permission denied (publickey)
```

### ✅ Fix:

* Use **GitHub Personal Access Token (PAT)** instead of password
* Or configure SSH properly

---

## ❌ 3. Nothing to commit

### 🔴 Error:

```bash id="g6h7i8"
nothing to commit, working tree clean
```

### ✅ Fix:

* Make sure you edited or added files
* Then run:

```bash id="j9k0l1"
git add .
```

---

## ❌ 4. src refspec main does not match any

### 🔴 Error:

```bash id="m2n3o4"
error: src refspec main does not match any
```

### ✅ Fix:

Run these commands:

```bash id="p5q6r7"
git branch -M main
git push -u origin main
```

---

## ❌ 5. Remote already exists

### 🔴 Error:

```bash id="s8t9u0"
remote origin already exists
```

### ✅ Fix:

```bash id="v1w2x3"
git remote remove origin
git remote add origin <your-repo-url>
```

---

## ❌ 6. Authentication failed

### 🔴 Error:

```bash id="y4z5a6"
Authentication failed
```

### ✅ Fix:

* Use **Personal Access Token (PAT)**
* Not your GitHub password

---

## 💡 Tips to Avoid Errors

* Always run `git status` before pushing
* Commit regularly with small changes
* Double-check repository URL
* Use GitHub token for authentication

---

## 🎯 Quick Recovery Commands

```bash id="b7c8d9"
git status
git add .
git commit -m "fix"
git push
```

---

## 🚀 Final Note

Most Git errors are normal for beginners.
Don’t panic—just follow the fix and try again 💪

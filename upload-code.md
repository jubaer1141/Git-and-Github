# 📤 Upload Code to GitHub (First Time)

This guide will help you upload your **local project/code to GitHub for the first time**.

---

## 📁 Step 1: Open Your Project Folder

* Go to your project folder (where your code is saved)
* Example: `Desktop/my-project`

---

## 💻 Step 2: Open Git Bash

* Right-click inside your project folder
* Click **"Git Bash Here"**

---

## ⚙️ Step 3: Initialize Git

```bash
git init
```

This will start Git in your project folder.

---

## ➕ Step 4: Add Files

```bash
git add .
```

This command adds all files to Git.

---

## 💾 Step 5: Commit Your Code

```bash
git commit -m "first commit"
```

This saves your code with a message.

---

## 🔗 Step 6: Connect to GitHub Repository

Go to your GitHub repository and copy the repository link.

Then run:

```bash
git remote add origin https://github.com/your-username/repo-name.git
```

---

## 🚀 Step 7: Push Code to GitHub

```bash
git push -u origin main
```

---

## ⚠️ Important Note

If you get an error like:

```bash
error: src refspec main does not match any
```

Try this command first:

```bash
git branch -M main
```

Then run:

```bash
git push -u origin main
```

---

## 🔐 Authentication Note

GitHub may ask for login:

* Username: your GitHub username
* Password: use **Personal Access Token (not your GitHub password)**

---

## 🎉 Done!

Your code is now uploaded to GitHub successfully 🚀

You can refresh your repository page and see your files.

---

## 🔄 Next Step

Now learn how to update your code:

👉 [Update Code](update-code.md)

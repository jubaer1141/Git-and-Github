# 🧩 Install Git (Git Bash)

This guide will help you install **Git** on your computer so you can use Git commands and connect with GitHub.

---

## 📥 Step 1: Download Git

1. Go to the official website:
   👉 https://git-scm.com/

2. Click on **Download for Windows**

---

## ⚙️ Step 2: Install Git

1. Open the downloaded file
2. Click **Next**
3. Keep the default settings (recommended)
4. Click **Next** until you see **Install**
5. Click **Install**
6. After installation, click **Finish**

---

## 💻 Step 3: Open Git Bash

* Right-click on your desktop or folder
* Click **Git Bash Here**

---

## 🔍 Step 4: Verify Installation

Type the following command:

```bash id="g7k2l9"
git --version
```

If you see a version like `git version 2.xx.x` → ✅ Git is installed successfully.

---

## ⚙️ Step 5: Configure Git (Important)

Set your name and email (required for commits):

```bash id="k3p8x1"
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Example:

```bash id="n2v7d4"
git config --global user.name "Md. Jubaer Hossain"
git config --global user.email "mdjubaer1141@email.com"
```

---

## 🔍 Step 6: Check Configuration

```bash id="z8q1w5"
git config --list
```

You should see your name and email in the list.

---

## 🎉 Done!

You have successfully installed and configured Git.
Now move to the next step:

👉 [Create GitHub Account](github-account.md)

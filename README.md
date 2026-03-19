# 🚀 AI-Adventure — Learn AI/ML from Scratch!

> **A hands-on, beginner-friendly AI/ML learning program for 160+ students at IIIT Basar**

Welcome aboard, adventurer! 🎉

This repository is your learning ground. Whether you've never written a single line of code or you're already a coding enthusiast — this is where your **AI journey begins**.

---

## 🧭 What is AI-Adventure?

**AI-Adventure** is a structured, step-by-step learning program designed to take you from **absolute beginner** to someone who can build with **AI Agents and Large Language Models (LLMs)**.

### 🗺️ The Learning Roadmap

| Stage | Topic | Status |
|-------|-------|--------|
| 🟢 Stage 1 | **Git & GitHub** — Version control, collaboration, open source | ✅ In Progress |
| 🟡 Stage 2 | **Python Fundamentals** — Variables, loops, functions, OOP | ⏳ Coming Soon |
| 🟡 Stage 3 | **Large Language Models (LLMs)** — How ChatGPT-like models work | ⏳ Coming Soon |
| 🟡 Stage 4 | **AI Agents** — Building intelligent, autonomous systems | ⏳ Coming Soon |

Each stage builds on the previous one. **No shortcuts. No skipping. Trust the process.** 💪

---

## 📁 Repository Structure

```
ai-adventure/
│
├── README.md              ← You are here!
├── notes/                 ← Resources, books, and learning materials shared by the trainer
│   └── .gitkeep
├── submissions/           ← YOUR work goes here!
│   └── .gitkeep
```

### 📂 `notes/` — Learning Resources

This folder contains **books, PDFs, reference links, cheat sheets**, and any material shared during sessions. Check this folder regularly — new resources will be added as we progress through each stage.

### 📂 `submissions/` — Your Assignments

This is where **you** submit your work. Each student creates their **own folder** inside `submissions/` and uploads assignments there.

---

## 📝 How to Submit Your Work (Step-by-Step Guide)

> ⚠️ **Read every step carefully.** Do NOT skip anything. If you get stuck, ask for help — that's what learning is about!

### Step 0: Install Git (One-Time Setup)

If you haven't installed Git yet:
- **Windows:** Download from [git-scm.com](https://git-scm.com/) and install (keep all defaults)
- **Mac:** Open Terminal and type `git --version` (it will prompt you to install if needed)
- **Linux:** Run `sudo apt install git`

Configure your identity (run these once):
```bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

### Step 1: Fork This Repository

1. Click the **"Fork"** button at the top-right corner of this page
2. This creates your own copy of the repository on your GitHub account

### Step 2: Clone Your Forked Repository

Open your terminal (Command Prompt / Git Bash / Terminal) and run:

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/ai-adventure.git
```

> 🔁 Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username.

### Step 3: Navigate Into the Project

```bash
cd ai-adventure
```

### Step 4: Go to the Submissions Folder

```bash
cd submissions
```

### Step 5: Create Your Personal Folder

Create a folder using this **exact naming convention**:

```
FirstName_LastName_RollNumber
```

**Rules for folder naming:**
- Use **PascalCase** (first letter of each word capitalized)
- Separate Name and Roll Number with an **underscore** `_`
- **No spaces**, no special characters, no emojis in folder names

✅ **Correct Examples:**
```
Rahul_Kumar_B230001
Priya_Sharma_B230045
Mohammed_Ali_B230112
```

❌ **Wrong Examples:**
```
rahul kumar b230001     ← has spaces, no underscores, no capitals
RAHUL_KUMAR_b230001     ← ALL CAPS is not PascalCase
rahul-kumar-B230001     ← hyphens instead of underscores
Rahul Kumar_B230001     ← space in name
```

Create the folder:
```bash
mkdir FirstName_LastName_RollNumber
```

Example:
```bash
mkdir Rahul_Kumar_B230001
```

### Step 6: Add Your Assignment File

Navigate into your folder and add your work:

```bash
cd Rahul_Kumar_B230001
```

You can create a file directly from the terminal:
```bash
echo "This is my first assignment!" > assignment1.txt
```

Or simply copy/paste your assignment file into this folder using your file explorer.

### Step 7: Stage Your Changes

Go back to the root of the project:
```bash
cd ../..
```

Now tell Git to track your new files:
```bash
git add .
```

> 💡 `git add .` stages **all** new and changed files. You can also add specific files: `git add submissions/Rahul_Kumar_B230001/assignment1.txt`

### Step 8: Commit Your Changes

```bash
git commit -m "Add assignment 1 - Rahul Kumar B230001"
```

> 💡 The commit message should be short and descriptive. Always include your name and roll number.

### Step 9: Push to Your Fork

```bash
git push origin main
```

> This uploads your work to **your** GitHub fork.

### Step 10 (Optional): Create a Pull Request

1. Go to **your forked repo** on GitHub
2. Click **"Contribute"** → **"Open Pull Request"**
3. Add a title like: `Submission: Rahul Kumar B230001 - Assignment 1`
4. Click **"Create Pull Request"**

> 🎓 A Pull Request (PR) is how you propose your changes to the main repository. The trainer will review and merge it.

---

## 🔄 Quick Reference — Git Commands Cheat Sheet

| Command | What It Does |
|---------|-------------|
| `git clone <url>` | Download a repository to your computer |
| `cd <folder>` | Navigate into a folder |
| `mkdir <name>` | Create a new folder |
| `git status` | Check what files have changed |
| `git add .` | Stage all changes for commit |
| `git commit -m "message"` | Save your changes with a description |
| `git push origin main` | Upload your commits to GitHub |
| `git pull origin main` | Download latest changes from GitHub |

---

## ⚠️ Rules — Read This Carefully!

> Breaking these rules may result in your submission being rejected.

### 📌 Rule 1: Stay in Your Folder
- **Only** add/edit files inside `submissions/YourName_RollNumber/`
- Do **NOT** touch the `notes/` folder, `README.md`, or anyone else's folder

### 📌 Rule 2: Follow the Naming Convention
- Folder name must be: `FirstName_LastName_RollNumber`
- Use **PascalCase** with **underscores**
- Double-check before creating — renaming later causes unnecessary complications

### 📌 Rule 3: Do Not Edit Others' Work
- Never modify, delete, or copy files from another student's folder
- This is a trust-based system — respect your peers' work

### 📌 Rule 4: Write Meaningful Commit Messages
- Bad: `git commit -m "update"`
- Good: `git commit -m "Add assignment 1 - Priya Sharma B230045"`

### 📌 Rule 5: Ask Before You Guess
- Stuck? Ask the trainer or a peer
- It's better to ask a "silly" question than to break the repo

---

## 🌟 Why Does This Repository Exist?

This isn't just a classroom assignment repo — **this is meant to become the BEST open-source AI/ML learning resource on GitHub.** Built by 160+ students, for their juniors, and for **anyone in the world** who wants to learn AI from scratch.

> **Imagine:** Someone in another country finds this repo, follows the notes, reads student submissions, and learns AI — all from one single place. **That's the vision. You are building that.**

### 🎯 1. Real-World Git Practice
You're not just learning Git commands from a textbook. You're using Git the way **professional developers** use it every day — cloning, branching, committing, pushing, and collaborating on a shared codebase.

### 🤝 2. One Repo to Learn It All
Everything lives here — notes, resources, assignments, projects. Anyone can come to this single repository and find **everything** they need to start their AI/ML journey. Your contributions make this possible.

### 📋 3. Building Your Public Portfolio
Every commit you make here is **public** and visible on your GitHub profile. Future recruiters and companies **will** check your GitHub. This is the beginning of your developer portfolio.

### 🏫 4. Leave a Legacy for Your Juniors
The students who come after you will look at this repo to learn. Your well-written assignments, clean code, and helpful notes will **guide the next batch**. Be the senior you wish you had.

### 🌍 5. Make It the Best — Together
The more you contribute, the better this repo becomes. Add quality work. Help each other. Share useful resources. Let's make this the kind of repo that people **star, fork, and share** across the world.

### ⭐ 6. Star This Repository!
If you find this repo helpful, **give it a star!** ⭐ Stars help this repo reach more people. It takes one click:

> Click the **"⭐ Star"** button at the **top-right corner** of this page.

**Every student should star this repo.** Let's get 160+ stars and show the world what IIIT Basar students can do! 🚀

---

## 🎯 Your First Task

> **Complete this before the next session!**

1. ✅ Create a GitHub account (if you don't have one)
2. ✅ Install Git on your machine
3. ✅ Fork this repository
4. ✅ Clone it to your computer
5. ✅ Create your folder inside `submissions/` with the correct naming convention
6. ✅ Add a file called `hello.txt` with one line: `Hello, AI-Adventure! I am [Your Name] and I am ready to learn.`
7. ✅ Commit and push your changes
8. ✅ (Bonus) Open a Pull Request

---

## 📚 Resources & Learning Materials

Check the **`notes/`** folder regularly! It will be updated with:
- 📖 Recommended books and PDFs
- 🔗 Useful links and tutorials
- 📝 Session notes and cheat sheets
- 🎥 Video references

---

## 🏆 Hall of Highlights

> *This section will be updated as students complete milestones!*

As you progress through the program, outstanding contributions, creative solutions, and helpful peers will be highlighted here. **Your work matters — make it count!**

---

## 📬 Need Help?

- Raise your hand in class (yes, seriously — it's the fastest way!)
- Ask in the group chat
- Open a GitHub Issue on this repository
- Google your error message (a skill every developer needs 🔍)

---

<p align="center">
  <b>🌟 Every expert was once a beginner. Your adventure starts NOW. 🌟</b>
</p>

---

<p align="center">
  Made with ❤️ at <b>IIIT Basar</b> | AI-Adventure 2026
</p>

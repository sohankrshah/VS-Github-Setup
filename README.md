# 💻 VS-Github-Setup

## 🧰 Overview
This repository documents the complete workflow for connecting **Visual Studio Code (VS Code)** with **GitHub** — from cloning and initializing to committing and pushing changes. Perfect for beginners and developers setting up reproducible environments 🚀

## 🚀 Steps Covered
✅ Git installation and verification  
✅ Cloning a GitHub repository  
✅ Initializing a local Git repo  
✅ Creating and editing files (e.g., `README.md`)  
✅ Staging, committing, and pushing changes  
✅ Using VS Code’s Source Control panel  

## 🔧 Prerequisites
Before you start, make sure you have the following installed 👇  
- 🧩 [Git](https://git-scm.com/downloads)  
- 🧠 [Visual Studio Code](https://code.visualstudio.com/download)  
- 🐙 [GitHub account](https://github.com/join)  
- 🔑 GitHub CLI or browser authentication  

## 📦 Setup Instructions

### 🌀 Case 1: Clone an Existing Repository

If your project already exists on GitHub, clone it using the following commands:

```bash
git clone https://github.com/your-username/VS-Github-Setup.git
cd VS-Github-Setup
code .
# Make changes, then commit and push
git add .
git commit -m "Updated project files"
git push
```


🏗️ Case 2: Initialize a New Repository
If you’re starting a new project from scratch, follow these steps:

```bash
mkdir VS-Github-Setup
cd VS-Github-Setup
git init
touch README.md
code .
git add .
git commit -m "Initial commit with README"
git branch -M main
git remote add origin https://github.com/your-username/VS-Github-Setup.git
git push -u origin main
```
🧭 Git Workflow

```
git status          # Check file changes
git add .           # Stage all modified files
git commit -m "Message"  # Commit changes locally
git push            # Push commits to GitHub
git pull            # Pull latest changes from remote
```
🧠 VS Code Tips
```
💡 Source Control Panel: Use the Source Control tab in VS Code to stage, commit, and push changes visually.
🔌 Recommended Extensions:

GitHub Pull Requests & Issues

GitLens — Git supercharged

⚙️ Customize Settings: You can create .vscode/settings.json to add auto-formatting and linting:

{
  "editor.formatOnSave": true,
  "files.autoSave": "afterDelay",
  "git.enableSmartCommit": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode"
}
```

📁 Project Structure
VS-Github-Setup/
├── .git/                  # Git version control folder
├── .vscode/               # VS Code workspace settings
├── README.md              # Documentation file
└── your-code-files-here   # Project files

💬 Common Git Commands
Command	Description
```git status	Check current changes
git log --oneline	View concise commit history
git branch -M main	Rename current branch to main
git pull origin main	Fetch and merge changes
git push origin main	Push commits to GitHub
```
🧑‍💻 Author
Sohan Kumar Shah
🌏 From: Nepal 🇳🇵

💖 Support & Contribute

If you found this helpful, please give it a ⭐ on GitHub!
Feel free to fork, improve, and open a pull request. Let’s make development smoother together 🤝

## 💬 Developer Motto
```
> “Code. Commit. Push. Repeat.” 🔁  
> Keep coding, keep creating, and keep contributing 💪```

# 🚀 Git & GitHub Complete Guide

## 📌 Introduction
Git and GitHub are essential tools for **version control**, **collaboration**, and **code management** in software development. This guide will help you understand Git concepts, commands, and best practices for using GitHub efficiently.

---

## 🔹 What is Git?
Git is a **distributed version control system** that helps track changes in code, collaborate with others, and maintain different versions of a project.

### ✨ Key Features:
- Track and manage code changes
- Work with multiple branches
- Collaborate with team members
- Revert to previous versions

---

## 🔹 What is GitHub?
GitHub is a **cloud-based Git repository hosting service** that allows developers to store, manage, and collaborate on projects.

### ✨ Key Features:
- Remote repository storage
- Issue tracking & project management
- Pull requests & code reviews
- CI/CD integration
- GitHub Actions for automation

---

## 🔧 Installation & Setup
### ✅ Install Git
Download and install Git from [Git's official website](https://git-scm.com/).

### ✅ Configure Git
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

---

## 🔥 Basic Git Commands

### ✅ Initialize a Repository
```bash
git init
```

### ✅ Clone a Repository
```bash
git clone https://github.com/username/repository.git
```

### ✅ Check Status
```bash
git status
```

### ✅ Add Files to Staging Area
```bash
git add filename  # Add a specific file
git add .         # Add all changes
```

### ✅ Commit Changes
```bash
git commit -m "Your commit message"
```

### ✅ Push Changes to Remote Repository
```bash
git push origin main
```

### ✅ Pull Latest Changes from Remote Repository
```bash
git pull origin main
```

### ✅ Create & Switch to a New Branch
```bash
git branch new-branch
git checkout new-branch
```

### ✅ Merge Branches
```bash
git checkout main
git merge new-branch
```

### ✅ View Commit History
```bash
git log --oneline
```

---

## 🌍 Working with GitHub

### ✅ Create a Repository on GitHub
1. Go to [GitHub](https://github.com/) and log in.
2. Click on **New Repository**.
3. Name your repository and select **Public/Private**.
4. Click **Create Repository**.

### ✅ Connect Local Repository to GitHub
```bash
git remote add origin https://github.com/username/repository.git
git push -u origin main
```

### ✅ Create a Pull Request (PR)
1. Fork a repository.
2. Make changes and push them to your forked repo.
3. Click **New Pull Request** in the original repository.
4. Compare changes and submit PR.

### ✅ Resolve Merge Conflicts
- Use `git status` to check conflicts.
- Open conflicting files and edit manually.
- Use `git add .` and `git commit` to finalize the resolution.

---

## 🎯 Best Practices
✅ Commit frequently with meaningful messages.  
✅ Use branches for new features.  
✅ Keep your `main` branch clean.  
✅ Pull changes before pushing.  
✅ Review code using PRs.

---

## 📚 Additional Resources
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com/)
- [Pro Git Book](https://git-scm.com/book/en/v2)

---

## ✨ Conclusion
Mastering Git & GitHub will make you a more efficient and collaborative developer. Keep practicing and explore advanced topics like **rebasing, stashing, and GitHub Actions**!

🚀 **Happy Coding!** 🚀


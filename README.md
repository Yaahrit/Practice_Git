# 📘 Git Cheat Sheet

A quick and practical reference guide for commonly used Git commands.
Perfect for beginners and developers who want fast access to essential Git workflows.

---

## 🚀 Features

* 📌 Easy-to-understand Git commands
* 🔁 Covers daily workflows (clone, commit, push, pull)
* 🌿 Branching & merging explained
* ⚡ Quick reference format
* 💡 Beginner-friendly

---

## 🛠️ Basic Commands

```bash
git init                # Initialize a new repository
git clone <repo-url>   # Clone a repository
git status             # Check status of changes
git add .              # Stage all changes
git commit -m "msg"    # Commit changes
git push origin main   # Push to GitHub
git pull origin main   # Pull latest changes
```

---

## 🌿 Branching

```bash
git branch                  # List branches
git branch <name>           # Create new branch
git checkout <name>         # Switch branch
git checkout -b <name>      # Create & switch
git merge <name>            # Merge branch
git branch -d <name>        # Delete branch
```

---

## 🔄 Remote Repositories

```bash
git remote add origin <url>   # Add remote repo
git remote -v                # Show remotes
git push -u origin main      # Push first time
```

---

## ⚠️ Undo Changes

```bash
git restore <file>           # Discard changes
git reset HEAD <file>        # Unstage file
git reset --hard             # Reset everything (danger!)
```

---


## ⚡ Advanced Git Commands

### 🔍 Viewing History

```bash
git log                     # Full commit history
git log --oneline           # Compact view
git log --graph --oneline   # Visual branch graph
```

---

### 🧭 Stashing Changes

```bash
git stash                   # Save changes temporarily
git stash list              # View stashes
git stash apply             # Apply last stash
git stash pop               # Apply & remove stash
```

---

### 🔀 Rebase (Clean History)

```bash
git pull --rebase           # Rebase instead of merge
git rebase <branch>         # Reapply commits on another branch
```

---

### 🧹 Cleaning Files

```bash
git clean -f                # Remove untracked files
git clean -fd               # Remove files + folders
```

---

### ⏪ Undo Commits

```bash
git reset --soft HEAD~1     # Undo commit (keep changes)
git reset --hard HEAD~1     # Undo commit (delete changes)
```

---

### 🔎 Show Changes

```bash
git diff                    # Show unstaged changes
git diff --staged           # Show staged changes
```

---

### 🏷️ Tags (Versioning)

```bash
git tag v1.0                # Create tag
git tag                     # List tags
git push origin v1.0        # Push tag
```

---

### 🔗 Remote Management

```bash
git remote remove origin    # Remove remote
git remote rename origin upstream
```

---

### 🧠 Pro Tips

* Use `rebase` for clean history instead of merge
* Use `stash` when switching branches with unfinished work
* Avoid `--hard` unless you're sure (data loss risk ⚠️)
* Always pull before pushing to avoid conflicts

---


## 📂 Project Structure

```
Git-CheatSheet/
│── README.md
│── index.html
│── Style.css
```

---

## 🎯 Use Case

This cheat sheet helps you:

* Quickly recall Git commands
* Practice version control
* Improve your workflow efficiency

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a Pull Request

---

## 📄 License

This project is open-source and free to use.

---

## ⭐ Support

If you find this helpful, consider giving it a ⭐ on GitHub!

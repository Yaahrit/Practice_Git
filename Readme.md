# 💻 Terminal Commands Guide (Windows & macOS)

A complete list of essential terminal commands from beginner to advanced for both Windows (CMD/PowerShell) and macOS/Linux.

---

## 🟢 Basic Navigation

| Action           | Windows (CMD/PowerShell) | macOS / Linux  |
| ---------------- | ------------------------ | -------------- |
| List files       | dir                      | ls             |
| Change directory | cd folder_name           | cd folder_name |
| Go back          | cd ..                    | cd ..          |
| Clear screen     | cls                      | clear          |
| Show path        | cd                       | pwd            |

---

## 📁 File & Folder Management

| Action        | Windows              | macOS / Linux     |
| ------------- | -------------------- | ----------------- |
| Create folder | mkdir folder_name    | mkdir folder_name |
| Delete folder | rmdir folder_name    | rm -r folder_name |
| Create file   | echo text > file.txt | touch file.txt    |
| Delete file   | del file.txt         | rm file.txt       |
| Copy file     | copy a.txt b.txt     | cp a.txt b.txt    |
| Move file     | move a.txt folder    | mv a.txt folder   |

---

## 📄 File Viewing

| Action          | Windows       | macOS / Linux |
| --------------- | ------------- | ------------- |
| View file       | type file.txt | cat file.txt  |
| View large file | more file.txt | less file.txt |

---

## 🔍 Search & Find

| Action      | Windows              | macOS / Linux         |
| ----------- | -------------------- | --------------------- |
| Search text | find "text" file.txt | grep "text" file.txt  |
| Find files  | dir /s filename      | find . -name filename |

---

## 🌐 Network Commands

| Action           | Windows         | macOS / Linux   |
| ---------------- | --------------- | --------------- |
| Check connection | ping google.com | ping google.com |
| Show IP          | ipconfig        | ifconfig / ip a |

---

## ⚙️ System Commands

| Action         | Windows            | macOS / Linux |
| -------------- | ------------------ | ------------- |
| Show processes | tasklist           | ps            |
| Kill process   | taskkill /PID 1234 | kill 1234     |

---

## 🔥 Advanced Commands

### 🧠 PowerShell (Windows Advanced)

```powershell
Get-ChildItem            # List files (like ls)
Set-Location folder      # Change directory
Remove-Item file.txt     # Delete file
```

---

### 🧠 macOS/Linux Advanced

```bash
chmod +x script.sh       # Make file executable
sudo command             # Run as admin
history                  # Show command history
```

---

## 🔁 Git + Terminal Workflow Example

```bash
cd project-folder
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin <repo-url>
git push -u origin main
```

---

## ⚠️ Tips for Beginners

* Use `Tab` for auto-complete
* Use ↑ arrow for previous commands
* Be careful with `rm -rf` (deletes permanently ⚠️)
* Use `clear` or `cls` to keep terminal clean

---

## 🎯 Summary

* Windows → `dir`, `copy`, `del`
* macOS/Linux → `ls`, `cp`, `rm`
* Git works same on both platforms



# 🧑‍💻 Real Developer Workflows

## 🚀 1. Starting a New Project

```bash
mkdir my-project
cd my-project
git init
touch index.html style.css
git add .
git commit -m "Initial project setup"
```

---

## 🔄 2. Daily Work Routine

```bash
git pull origin main        # Get latest changes
# make changes in code
git add .
git commit -m "Updated feature"
git push origin main
```

---

## 🌿 3. Feature Branch Workflow (Best Practice)

```bash
git checkout -b feature-login
# work on feature
git add .
git commit -m "Added login feature"
git push origin feature-login
```

Then:

* Create Pull Request on GitHub
* Merge into `main`

---

## 🔥 4. Fixing Mistakes

```bash
git restore file.txt            # Undo changes
git reset --soft HEAD~1         # Undo commit (keep code)
git reset --hard HEAD~1         # Delete commit (danger ⚠️)
```

---

## 🧳 5. Switching Work (Stash)

```bash
git stash
git checkout another-branch
git stash pop
```

---

# 📊 Mini Practice Projects

## 💡 Project Ideas

* 📝 Notes App (HTML + CSS)
* 📋 To-Do List
* 🌐 Personal Portfolio
* 🎨 Landing Page

---

## 📁 Suggested Structure

```
project-name/
│── index.html
│── style.css
│── script.js
│── README.md
```

---

# ⚡ Productivity Tips

* Press `Tab` → auto-complete commands
* Use `↑` → repeat last command
* Use `history` → see all commands
* Keep commits small & meaningful

---

# 🧩 Common Mistakes (Avoid These)

❌ Pushing without pulling
❌ Using `--force` without understanding
❌ Working directly on `main`
❌ Not writing commit messages

---

# 🏆 Pro Level Tips

* Use branches for every feature
* Write clean commit messages
* Keep repo organized
* Practice daily using Git

---

# 🎯 Final Goal

✔ Understand Git basics
✔ Work with branches
✔ Collaborate using GitHub
✔ Build real projects

---

## ⭐ Bonus

If this helped you:

* Star ⭐ the repo
* Share with friends
* Keep practicing Git daily 🚀



Mastering terminal commands = faster development 🚀

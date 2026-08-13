# Geetlit

> A lightweight LeetCode progress logger that lets you record solved problems and sync their basic metadata to a GitHub repository.

Geetlit is a small browser-based utility built to make maintaining a GitHub-based LeetCode solving log easier.

Instead of manually creating a Markdown file and committing it every time you solve a problem, you can enter the problem number and title, and Geetlit can create a small Markdown log and push it to your configured GitHub repository.

It also includes a bulk import feature for adding problems that you solved before using Geetlit.

---

## ✨ Features

- 📝 **Log solved LeetCode problems**
  - Add a problem number
  - Optionally add the problem title
  - Record the date and time

- 🚀 **GitHub synchronization**
  - Push logged problems directly to GitHub
  - Creates a Markdown file for each problem
  - Tracks whether an entry has been synchronized successfully

- 📁 **Custom GitHub configuration**
  - Choose GitHub username/organization
  - Choose repository
  - Choose branch
  - Choose folder/path for your logs

- 🔄 **Bulk import**
  - Import previously solved problems
  - Useful when starting Geetlit with an existing LeetCode history

- 📦 **Two import modes**
  - Combine imported problems into one Markdown file and commit
  - Create a separate Markdown file and commit for each problem

- 📊 **Sync status tracking**
  - Pending
  - Synced
  - Failed

- 💾 **Browser-based storage**
  - Problem logs and configuration are stored locally in the browser
  - No external database is required

- 🌐 **No installation required**
  - Runs directly in the browser
  - No backend server is required for the current version

---

# 🎯 Why Geetlit?

Maintaining a LeetCode GitHub repository manually can become repetitive.

For every problem, you may have to:

1. Create a file
2. Add the problem information
3. Put it in the correct folder
4. Commit the change
5. Push it to GitHub

Geetlit reduces this repetitive process.

### Without Geetlit

```text
Solve Problem
     ↓
Create Markdown File
     ↓
Write Problem Information
     ↓
Save File
     ↓
Git Add
     ↓
Git Commit
     ↓
Git Push

# ⚠️ Important Things to Know

Before using Geetlit, it is important to understand what it actually automates.

### 🚀 Geetlit Automates the GitHub Commit & Push Process

Once GitHub is configured, you do **not** need to manually:

- Create the Markdown file
- Run `git add`
- Run `git commit`
- Run `git push`

Geetlit handles the GitHub file creation and commit operation automatically through the GitHub API.

The basic workflow is:

```text
Solve a problem on LeetCode
          ↓
Enter the problem number/title in Geetlit
          ↓
Geetlit creates the log file
          ↓
Geetlit sends it to GitHub
          ↓
GitHub commit is created
          ↓
Your repository is updated

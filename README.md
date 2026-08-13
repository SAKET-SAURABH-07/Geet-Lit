# Geetlit

> A lightweight LeetCode progress logger that automatically records solved problems and syncs them to GitHub.

Geetlit is a simple browser-based tool built to make maintaining a GitHub-based LeetCode solving log easier.

Instead of manually creating a Markdown file and committing it every time you solve a problem, you can enter the problem number and title, and Geetlit handles the logging and GitHub sync for you.

It also includes a bulk import feature for adding problems you solved before using Geetlit.

---

## ✨ Features

- 📝 **Log solved problems**
  - Add a LeetCode problem number
  - Optionally add the problem title
  - Record the date and time

- 🚀 **Automatic GitHub sync**
  - Automatically pushes new entries to your repository
  - Creates a Markdown file for each problem
  - Tracks whether an entry has been synced successfully

- 📁 **Custom GitHub configuration**
  - Choose GitHub username/organization
  - Choose repository
  - Choose branch
  - Choose the folder where problem files should be stored

- 🔄 **Bulk import**
  - Import previously solved problems
  - Useful when starting Geetlit with an existing LeetCode history

- 📦 **Two import modes**
  - Combine all imported problems into one Markdown file and commit
  - Create a separate Markdown file and commit for each problem

- 📊 **Sync status tracking**
  - Pending
  - Synced
  - Failed

- 💾 **Local storage**
  - Problem logs and configuration are stored in the browser
  - No separate database is required

- 🌐 **Browser-based**
  - Runs directly in the browser
  - No installation required

---

## 🎯 Why Geetlit?

Keeping a LeetCode GitHub repository updated manually can become repetitive.

For every problem, you normally have to:

1. Create a file
2. Add the problem information
3. Save it in the correct folder
4. Commit the change
5. Push it to GitHub

Geetlit reduces this process to essentially:

**Enter problem → Log → Sync**

The goal is not to replace LeetCode or manage your actual solutions. It is simply a small utility for keeping a consistent GitHub activity log.

---

## ⚠️ What Geetlit Does

Geetlit creates small Markdown files containing information such as:

```text
Problem 1. Two Sum

Date: 2026-08-13
Time: 18:30
Title: Two Sum

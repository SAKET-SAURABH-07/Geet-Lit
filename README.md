# 🚀 Geetlit

> A lightweight, browser-based LeetCode progress logger that automatically records your solved problems and syncs their metadata directly to a configured GitHub repository.

Maintaining a GitHub-based LeetCode solving log manually can be tedious and repetitive. Geetlit eliminates the friction of creating Markdown files, formatting them, and committing them via the command line. Simply enter the problem number and title, and Geetlit will generate the log and push it to GitHub for you.

---

## ✨ Features

*   **📝 Effortless Logging:** Quickly add problem numbers, optional titles, and record the exact date and time of completion.
*   **🚀 Direct GitHub Synchronization:** Push logged problems directly to GitHub via the GitHub API, automatically generating a beautifully formatted Markdown file for each entry.
*   **📁 Fully Customizable Configuration:** Define your target GitHub username or organization, specific repository, branch, and folder path. 
*   **🔄 Flexible Bulk Import:** Easily transition your existing LeetCode history into Geetlit. Choose between combining all imported problems into a single commit or creating separate Markdown files for each problem.
*   **📊 Visual Status Tracking:** Keep track of your syncing progress with intuitive status indicators: Synced (green), Pending (amber), and Error (red).
*   **💾 Secure Local Storage:** All problem logs and configurations are stored entirely locally in your browser—no external databases or backend servers are required.
*   **✨ Animated UI Experience:** The interface features clean CSS animations, such as a blinking terminal-style caret in the header, smooth button scaling on click, and responsive toast notifications.

---

## 🎯 Why Geetlit?

Without automation, updating your repository for every solved problem is a repetitive, multi-step chore. Geetlit reduces this entire workflow down to a single step.

| Without Geetlit (Manual Workflow) | With Geetlit (Automated Workflow) |
| :--- | :--- |
| 1. Solve Problem | 1. Solve Problem |
| 2. Create Markdown File | **2. Enter Problem Number in Geetlit** |
| 3. Write Problem Information | *Geetlit automatically creates the file* |
| 4. Save File to Correct Folder | *Geetlit formats the information* |
| 5. Run `git add .` | *Geetlit pushes to your GitHub repo* |
| 6. Run `git commit -m "..."` | |
| 7. Run `git push` | |

---

## ⚠️ Important Things to Know & Cautions

Before diving into Geetlit, please keep the following operational details and constraints in mind to ensure you don't lose any data:

*   **Automated Git Operations:** Geetlit handles the entire file creation and commit operation automatically through the GitHub API. Once configured, you do **not** need to manually run `git add`, `git commit`, or `git push`.
*   **Local Storage Dependency:** Because Geetlit runs entirely in the browser without a backend server, your un-synced logs and configurations are stored in your local browser cache. **Caution:** Clearing your browser's site data or cache will permanently delete any locally stored configurations and pending logs.
*   **Configuration Validation:** When setting up your repository path, pay attention to the real-time URL preview and verification messages. A green validation message indicates a correct setup, while a red message means your path or repository details need fixing.
*   **Monitor Your Sync Status:** Always check the toast notifications that pop up at the bottom of the screen. If a sync fails (indicated by a red status dot), the log remains in your pending list so you can try pushing it again.

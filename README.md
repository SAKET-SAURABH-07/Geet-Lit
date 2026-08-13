<p align="center">
  <img src="logo.png" width="220" alt="Geetlit Logo">
</p>

# <p align="center">🚀 Geetlit</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-blueviolet?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/GitHub-API-black?style=for-the-badge&logo=github" alt="GitHub API">
  <img src="https://img.shields.io/badge/Storage-Local-green?style=for-the-badge" alt="Local Storage">
  <img src="https://img.shields.io/badge/UI-Animated-orange?style=for-the-badge" alt="UI">
</p>

<p align="center">
  <strong>A lightweight, browser-based LeetCode progress logger that automatically records your solved problems and syncs their metadata directly to a configured GitHub repository.</strong>
</p>

<p align="center">
  <a href="#-features">Features</a> • 
  <a href="#-why-geetlit">Why Geetlit?</a> • 
  <a href="#-important-things-to-know---cautions">Cautions</a>
</p>

---

## 🌟 The Vision

Maintaining a GitHub-based LeetCode solving log manually is a chore. Creating Markdown files, formatting them, and running Git commands is repetitive. 

**Geetlit eliminates the friction.** Simply enter the problem number and title, and Geetlit handles the generation, formatting, and pushing to GitHub in one click. ✨

---

## ✨ Features

<table width="100%">
  <tr>
    <td width="50%">
      <h4>📝 Effortless Logging</h4>
      <p>Quickly add problem numbers, optional titles, and record the exact date and time of completion.</p>
    </td>
    <td width="50%">
      <h4>🚀 Direct GitHub Sync</h4>
      <p>Push logs via GitHub API, automatically generating beautifully formatted Markdown files.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4>📁 Fully Customizable</h4>
      <p>Define your target username/org, specific repository, branch, and folder path.</p>
    </td>
    <td width="50%">
      <h4>🔄 Flexible Bulk Import</h4>
      <p>Transition existing history. Choose between a single commit or individual files per problem.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4>📊 Visual Status Tracking</h4>
      <p>Intuitive indicators: <span style="color:green">●</span> Synced, <span style="color:orange">●</span> Pending, <span style="color:red">●</span> Error.</p>
    </td>
    <td width="50%">
      <h4>💾 Secure Local Storage</h4>
      <p>No external databases. All data stays in your browser's local storage.</p>
    </td>
  </tr>
</table>

> [!TIP]
> **UI Experience:** Geetlit features clean CSS animations, including a blinking terminal-style caret in the header and smooth toast notifications for a premium feel.

---

## 🎯 Why Geetlit?

Stop fighting with your terminal and start focusing on the code.

| ❌ Without Geetlit (Manual) | ✅ With Geetlit (Automated) |
| :--- | :--- |
| 1. Solve Problem | 1. Solve Problem |
| 2. Create Markdown File | **2. Enter Problem Number in Geetlit** |
| 3. Write Problem Information | $\rightarrow$ *Geetlit creates the file* |
| 4. Save File to Correct Folder | $\rightarrow$ *Geetlit formats the data* |
| 5. `git add .` | $\rightarrow$ *Geetlit pushes to GitHub* |
| 6. `git commit -m "..."` | |
| 7. `git push` | |

---

## ⚠️ Important Things to Know & Cautions

> [!IMPORTANT]
> Please read these operational details to ensure you don't lose any data.

*   **⚙️ Automated Git Operations:** Geetlit handles the entire file creation and commit operation via the GitHub API. You do **not** need to run manual Git commands.
*   **💾 Local Storage Dependency:** Since there is no backend, your un-synced logs are stored in your browser cache. 
    *   **CAUTION:** Clearing your browser's site data or cache will permanently delete any locally stored configurations and pending logs.
*   **🔍 Configuration Validation:** Pay attention to the real-time URL preview. 
    *   🟢 **Green:** Your setup is correct.
    *   🔴 **Red:** Your path or repository details need fixing.
*   **🔔 Monitor Sync Status:** Always check the toast notifications. If a sync fails (red status dot), the log remains in your pending list so you can retry.

---

<p align="center">
  Made by Saket Saurabh 
</p>

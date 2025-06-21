# macOS `.gitignore`

<p>
  <img src="https://img.shields.io/badge/License-MIT-green" alt="MIT License" style="vertical-align:middle; margin-right:8px;" />
  <img src="https://img.shields.io/badge/macOS-Compatible-blue?logo=apple&logoColor=white" alt="macOS compatible" style="vertical-align:middle; margin-right:8px;" />
  <img src="https://img.shields.io/badge/Template-Repository-success?logo=github" alt="GitHub Template" style="vertical-align:middle; margin-right:8px;" />
  <img src="https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20on-macOS-blue?logo=apple" alt="Made with macOS" style="vertical-align:middle; margin-right:8px;" />
  <img src="https://img.shields.io/badge/Unofficial_Template_for_macOS-grey?logo=apple" alt="Unofficial Template" style="vertical-align:middle;" />
</p>

## 📖 Table of Contents

- [macOS `.gitignore`](#macos-gitignore)
  - [📖 Table of Contents](#-table-of-contents)
  - [🤓 Overview](#-overview)
  - [🧾 Use Case](#-use-case)
  - [📄 Contents of `.gitignore`](#-contents-of-gitignore)
  - [✅ Files You Can Still Track](#-files-you-can-still-track)
  - [📦 How to Use](#-how-to-use)
  - [📜 Licence](#-licence)
  - [🙋‍♂️ Contributions](#️-contributions)

## 🤓 Overview

A simple `.gitignore` template optimised for macOS users who work primarily with Word, Excel, and Affinity applications. This setup excludes system files, temporary backups, and autosaves, while keeping your main project files (`.docx`, `.xlsx`, `.afphoto`, etc.) safely tracked in Git.

## 🧾 Use Case

This is ideal if:

- You're creating non-code projects with Markdown, documents, or images.
- You use Git to version notes, docs, or artwork.
- You want to avoid polluting your commits with `.DS_Store` and temp files.

## 📄 Contents of `.gitignore`

This template covers:

- **macOS system files**  
  `.DS_Store`, `._*`, `.AppleDouble`, `.Spotlight-V100`, etc.

- **Temporary and backup files**  
  `*.tmp`, `*.bak`, `*~`, `*.swp`, etc.

- **Microsoft Office temp files**  
  `~$*`, `*.wbk`, `*.xlk`, etc.

- **Affinity autosave/preview files**  
  `*.autosave`, `*.afdesign-preview`, etc.

## ✅ Files You Can Still Track

This `.gitignore` **does not exclude** the following, so they’ll still be tracked in Git:

- `.docx`, `.xlsx`
- `.afphoto`, `.afdesign`, `.afpub`
- `.md`, `.jpg`, `.png`, `.pdf`, etc.

## 📦 How to Use

1. Copy the contents of [`macos.gitignore`](./macos.gitignore) into your project's `.gitignore` file.
2. If you already committed some ignored files, run:

    ```bash
    git rm -r --cached .
    git add .
    git commit -m "Apply .gitignore"
    ```

## 📜 Licence

This project is licensed under the [MIT License](LICENSE).

## 🙋‍♂️ Contributions

Suggestions or additions are welcome, especially if you use other macOS-native apps with known temp file formats.

---

Made with 💻 on macOS by [Karl Horning](https://github.com/Karl-Horning)

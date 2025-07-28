# macOS `.gitignore`

---

<p>
  <img src="https://img.shields.io/badge/License-MIT-green" alt="MIT License" style="vertical-align:middle; margin-right:8px;" />
  <img src="https://img.shields.io/badge/macOS-Compatible-blue?logo=apple&logoColor=white" alt="macOS compatible" style="vertical-align:middle; margin-right:8px;" />
  <img src="https://img.shields.io/badge/Template-Repository-success?logo=github" alt="GitHub Template" style="vertical-align:middle; margin-right:8px;" />
  <img src="https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20on-macOS-blue?logo=apple" alt="Made with macOS" style="vertical-align:middle; margin-right:8px;" />
  <img src="https://img.shields.io/badge/Unofficial_Template_for_macOS-grey?logo=apple" alt="Unofficial Template" style="vertical-align:middle;" />
</p>

---

## 📖 Table of Contents

- [macOS `.gitignore`](#macos-gitignore)
  - [📖 Table of Contents](#-table-of-contents)
  - [🤓 Overview](#-overview)
  - [🧾 Use Case](#-use-case)
  - [📄 Contents of `.gitignore`](#-contents-of-gitignore)
  - [✅ Files You Can Still Track](#-files-you-can-still-track)
  - [📦 Installation](#-installation)
  - [🤝 Contributing](#-contributing)
  - [📄 Licence](#-licence)
  - [👤 Author](#-author)

---

## 🤓 Overview

A simple `.gitignore` template optimised for macOS users working primarily with Word, Excel, and Affinity apps. It excludes system files, temporary backups, and autosaves, while keeping your main project files (such as `.docx`, `.xlsx`, `.afphoto`) tracked in Git.

---

## 🧾 Use Case

This template is ideal if you:

- Create non-code projects using Markdown, documents, or images.
- Use Git to version notes, documentation, or artwork.
- Want to avoid cluttering commits with `.DS_Store` and temporary files.

---

## 📄 Contents of `.gitignore`

This template excludes:

- **macOS system files**  
  `.DS_Store`, `._*`, `.AppleDouble`, `.Spotlight-V100`, and others.

- **Temporary and backup files**  
  `*.tmp`, `*.bak`, `*~`, `*.swp`, etc.

- **Microsoft Office temporary files**  
  `~$*`, `*.wbk`, `*.xlk`, etc.

- **Affinity autosave and preview files**  
  `*.autosave`, `*.afdesign-preview`, and similar.

---

## ✅ Files You Can Still Track

This `.gitignore` does **not** exclude the following, so these will remain tracked:

- `.docx`, `.xlsx`
- `.afphoto`, `.afdesign`, `.afpub`
- `.md`, `.jpg`, `.png`, `.pdf`, and other common document/image formats

---

## 📦 Installation

1. Copy the contents of [`macos.gitignore`](./macos.gitignore) into your project's `.gitignore` file.  
2. If you've already committed files you want ignored, run:

```bash
git rm -r --cached .
git add .
git commit -m "Apply .gitignore"
```

---

## 🤝 Contributing

Pull requests and suggestions are welcome, especially if you use other macOS-native apps with known temporary file formats.

---

## 📄 Licence

MIT © 2025 Karl Horning

---

## 👤 Author

Made with ❤️ by [Karl Horning](https://github.com/Karl-Horning)

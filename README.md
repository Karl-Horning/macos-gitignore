# macOS `.gitignore`

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

# macOS `.gitignore`

![MIT License](https://img.shields.io/badge/License-MIT-green)
![macOS compatible](https://img.shields.io/badge/macOS-Compatible-blue?logo=apple&logoColor=white)

A `.gitignore` template for macOS users working with Word, Excel, and Affinity apps. Excludes system files, temporary backups, and autosaves while keeping your actual project files tracked.

## Use case

Useful if you:

- Version non-code projects—notes, documentation, or artwork
- Want to avoid committing `.DS_Store` and other macOS noise

## What's excluded

- **macOS system files**—`.DS_Store`, `._*`, `.AppleDouble`, `.Spotlight-V100`, and more
- **Temporary and backup files**—`*.tmp`, `*.bak`, `*~`, `*.swp`, and more
- **Microsoft Office temp files**—`~$*`, `*.wbk`, `*.xlk`, and more
- **Affinity autosave files**—`*.autosave`, `*.afdesign-preview`, and more

## Installation

1. Copy the contents of [`.gitignore`](./.gitignore) into your project's `.gitignore`.
2. If you've already committed files you want ignored, run:

```bash
git rm -r --cached .
git add .
git commit -m "Apply .gitignore"
```

## Licence

MIT © 2025 [Karl-Horning](https://github.com/Karl-Horning)

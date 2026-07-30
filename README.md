# 🛠️ Easy Binary (Auto Compiler & Runtime Provisioner)

> **Never worry about installing GCC, MinGW, Python, JDK, or Go manually again.**

![VS Code Marketplace Version](https://img.shields.io/badge/VS%20Code%20Marketplace-v0.1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 🚀 What does Easy Binary do?

Setting up compilers on Windows (PATH variables, MinGW downloads, JDK configurations) is notoriously tedious for students and beginners.

**Easy Binary** automatically detects missing language runtimes or compilers when you run your code and provisions them silently in the background using Windows Package Manager (`winget`).

---

## ⚡ Supported Auto-Installers via Winget

| Language / Tool | Automatically Installed Package |
| :--- | :--- |
| **C / C++** | WinLibs MinGW (gcc / g++) (`BrechtSanders.WinLibs.POSIX.UCRT`) |
| **Python** | Python 3 (`Python.Python.3`) |
| **Java** | Oracle JDK 21 (`Oracle.JDK.21`) |
| **Go** | Go SDK (`GoLang.Go`) |
| **JavaScript / TS** | Node.js (`OpenJS.NodeJS`) |
| **C#** | .NET SDK 8 (`Microsoft.DotNet.SDK.8`) |
| **Rust** | Rustup (`Rustlang.Rustup`) |

---

## 📦 Part of the F5 Anything Suite

- **[F5 Anything](https://github.com/loerei/f5-anything)**: Press F5 to build & run any code file instantly.
- **[No More .vscode](https://github.com/loerei/no-more-vscode)**: Keep your workspace 100% clean by isolating binary outputs away from your code folders.
- **[F5 Anything Suite](https://github.com/loerei/f5-anything-suite)**: Install the complete zero-config package in 1 click!

---

## 📄 License

[MIT License](LICENSE) © [loerei](https://github.com/loerei)

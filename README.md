<div align="center">

# MyTermX

**跨平台 SSH / SFTP 终端客户端 · Cross-platform SSH / SFTP terminal client**

[![Release](https://img.shields.io/github/v/release/RuyimgByCN/MyTermX-Releases?label=Release&color=blue)](https://github.com/RuyimgByCN/MyTermX-Releases/releases)
[![License](https://img.shields.io/badge/license-Proprietary-red)](./LICENSE)
[![Platforms](https://img.shields.io/badge/platforms-macOS%20%7C%20Windows%20%7C%20Linux%20%7C%20Android%20%7C%20iOS-lightgrey)](#下载-downloads)

</div>

> 🌐 **[English](#english)** · **[中文](#中文)**

---

## English

MyTermX is a cross-platform SSH / SFTP terminal client for macOS, Windows,
Linux, Android, and iOS. It brings a modern, polished terminal experience
to every device you use — manage remote hosts, transfer files over SFTP,
and keep your connections in sync.

> **This repository is the public release channel** for MyTermX installers
> and update notes. **Source code is NOT distributed here** — it lives in
> private development repositories. This repo contains only release-facing
> documentation, screenshots, and GitHub Release attachments.

### ✨ Features

- **SSH terminal** — full interactive sessions powered by a Rust SSH runtime.
- **SFTP file transfer** — browse and transfer remote files with a WinSCP-style UI.
- **Cross-platform** — one product, native builds for desktop and mobile.
- **Vault** — encrypted storage for your credentials.
- **Connection history & sync** — manage hosts across devices.

### 📥 Downloads

Grab the latest build from GitHub Releases:

➡️ **[Latest Release](https://github.com/RuyimgByCN/MyTermX-Releases/releases/latest)**

| Platform | Artifact | Notes |
|---|---|---|
| macOS (Apple Silicon) | `MyTermX-<version>-arm64.dmg` | M-series Macs |
| macOS (Intel) | `MyTermX-<version>-x64.dmg` | Intel Macs |
| Windows | `MyTermX-Setup-<version>.exe` | Windows 10 / 11 |
| Linux | `MyTermX-<version>.AppImage` | Most distributions |

> Binaries are attached to GitHub Releases only — they are **not** committed
> to this repository's git tree.

### 📦 Installation

#### macOS
1. Download the matching `.dmg`.
2. Open it and drag **MyTermX** into **Applications**.
3. If macOS blocks the first launch: open *System Settings → Privacy & Security*
   and click **Open Anyway**.

#### Windows
1. Download the `.exe` installer.
2. Run it and follow the prompts.
3. If SmartScreen warns, click **More info → Run anyway**.

#### Linux
```bash
chmod +x MyTermX-*.AppImage
./MyTermX-*.AppImage
```

### 🔄 Updates

MyTermX checks for new versions automatically. You can also revisit the
[Releases page](https://github.com/RuyimgByCN/MyTermX-Releases/releases)
to download the latest build manually.

### 📝 Reporting Issues

Found a bug or want to request a feature?
[Open an issue](https://github.com/RuyimgByCN/MyTermX-Releases/issues).

---

## 中文

MyTermX 是一款跨平台 SSH / SFTP 终端客户端，支持 macOS、Windows、Linux、
Android 与 iOS。它为你的每一台设备带来现代、精致的终端体验 —— 管理远程主机、
通过 SFTP 传输文件，并在多设备间同步你的连接。

> **本仓库是公开的发布渠道**，仅包含 MyTermX 安装包与更新说明。
> **源代码不在本仓库公开** —— 它存放在私有开发仓库中。本仓库只包含面向用户的
> 文档、截图与 GitHub Release 附件。

### ✨ 功能特性

- **SSH 终端** —— 基于 Rust SSH 运行时的完整交互式会话。
- **SFTP 文件传输** —— WinSCP 风格的远程文件浏览与传输。
- **跨平台** —— 同一产品，覆盖桌面与移动端原生构建。
- **保险库（Vault）** —— 凭据加密存储。
- **连接历史与同步** —— 跨设备管理主机。

### 📥 下载

从 GitHub Releases 获取最新版本：

➡️ **[最新版本](https://github.com/RuyimgByCN/MyTermX-Releases/releases/latest)**

| 平台 | 文件名 | 说明 |
|---|---|---|
| macOS（Apple Silicon） | `MyTermX-<version>-arm64.dmg` | M 系列芯片 Mac |
| macOS（Intel） | `MyTermX-<version>-x64.dmg` | Intel 芯片 Mac |
| Windows | `MyTermX-Setup-<version>.exe` | Windows 10 / 11 |
| Linux | `MyTermX-<version>.AppImage` | 主流发行版 |

> 安装包仅附在 GitHub Releases 中 —— **不会**提交到本仓库的 git 树。

### 📦 安装

#### macOS
1. 下载对应的 `.dmg` 文件。
2. 打开并将 **MyTermX** 拖入 **应用程序（Applications）**。
3. 首次启动若被 macOS 拦截：打开 *系统设置 → 隐私与安全性*，点击 **仍要打开**。

#### Windows
1. 下载 `.exe` 安装包。
2. 运行并按提示安装。
3. 若 SmartScreen 提示风险，点击 **更多信息 → 仍要运行**。

#### Linux
```bash
chmod +x MyTermX-*.AppImage
./MyTermX-*.AppImage
```

### 🔄 更新

MyTermX 会自动检查新版本。你也可以随时访问
[Releases 页面](https://github.com/RuyimgByCN/MyTermX-Releases/releases)
手动下载最新版本。

### 📝 反馈问题

发现 Bug 或希望提出功能建议？
[提交 Issue](https://github.com/RuyimgByCN/MyTermX-Releases/issues)。

---

## 📄 License · 许可协议

Copyright © 2026 MyTermX (Ruyimg). All rights reserved.

The Software is **proprietary**. You may download and use the binaries
for personal, educational, or internal business purposes, but you may
**not** use it commercially, redistribute, reverse engineer, or modify it.
See the full terms in [LICENSE](./LICENSE).

本软件为**专有软件**。你可以下载并出于个人、教育或企业内部使用目的使用本二进制
产物，但**不得**用于商业用途、再分发、逆向工程或修改。完整条款见
[LICENSE](./LICENSE)。

---

<div align="center">

<sub>Built with ❤️ by Ruyimg · MyTermX © 2026</sub>

</div>

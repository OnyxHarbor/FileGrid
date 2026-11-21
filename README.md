<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/filegrid-horizontal-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="docs/filegrid-horizontal.svg">
    <img src="docs/filegrid-horizontal.svg" width="420" alt="FileGrid Logo" />
  </picture>

  <p><strong>The Modern Power-User File Manager for Windows</strong><br>
  Engineered for extreme speed, multi-pane precision, keyboard workflows, and total privacy.</p>

  <p>
    <a href="https://onyxharbor.github.io/FileGrid/"><img src="https://img.shields.io/badge/Website-GitHub%20Pages-3b82f6?style=flat-square" alt="Website" /></a>
    <img src="https://img.shields.io/badge/Platform-Windows%2011%20%7C%2010-0078d4?style=flat-square&logo=windows" alt="Platform" />
    <img src="https://img.shields.io/badge/Framework-WinUI%203%20%2F%20Windows%20App%20SDK-512bd4?style=flat-square" alt="Framework" />
    <img src="https://img.shields.io/badge/Runtime-.NET%208%20%7C%20.NET%209-512bd4?style=flat-square" alt="Runtime" />
    <img src="https://img.shields.io/badge/Telemetry-Zero%20%28100%25%20Local%29-10b981?style=flat-square" alt="Telemetry" />
    <a href="EULA.txt"><img src="https://img.shields.io/badge/License-Proprietary%20%28Unlimited%20Use%29-f59e0b?style=flat-square" alt="License" /></a>
  </p>
</div>

---

## 🌟 Overview & Philosophy
**FileGrid** is a modern, high-performance file manager built from the ground up using **WinUI 3** and the **Windows App SDK**. Designed for developers, power users, and system administrators, FileGrid prioritizes instantaneous directory traversal, deep keyboard ergonomics, multi-pane productivity, and zero telemetry.

- **Official Website & Showcase:** [https://onyxharbor.github.io/FileGrid/](https://onyxharbor.github.io/FileGrid/)
- **Privacy Policy:** [https://onyxharbor.github.io/FileGrid/privacy.html](https://onyxharbor.github.io/FileGrid/privacy.html)
- **Plugin Development Guide:** [docs/PLUGIN_DEVELOPMENT.md](docs/PLUGIN_DEVELOPMENT.md)
- **Issue Tracker & Feature Requests:** [https://github.com/OnyxHarbor/FileGrid/issues](https://github.com/OnyxHarbor/FileGrid/issues)

> **Repository Notice:** This repository serves as the official public project hub, documentation, GitHub Pages landing site, issue tracker, and plugin SDK manual for FileGrid. FileGrid is commercial proprietary software; the core application binaries are distributed through the official Microsoft Store.

---

## 🛒 Distribution & Voluntary Developer Support

FileGrid is distributed exclusively through the **Microsoft Store** to guarantee verified cryptographic signatures, seamless installation, sandboxed security, and silent background updates.

- **Voluntary Support Model:** FileGrid is offered on the Microsoft Store for a small one-time developer support fee. There are zero subscriptions, zero ads, and zero DRM activation hurdles.
- **Complete Core Experience:** All core file management capabilities—multi-pane workspaces, inline visual diff, staging basket, kinematic instant search, and full theme personalization—are 100% unlocked out of the box without artificial paywalls. Optional modular plugins (`.fgpkg`) can be added independently to tailor specialized workflows.
- **Direct Developer Funding:** Purchasing FileGrid acts as a direct sponsorship, empowering the author to actively maintain, optimize, and engineer upcoming features over the long term.
- **Unlimited Freedom of Deployment:** You pay once and enjoy unlimited installations across all personal and commercial computers within your organization or home.

---

## 🚀 Core Key Features (Built-in Capabilities)

Every feature below is 100% built into the core FileGrid application out of the box:

### 🗂️ Advanced Grid Workspaces & Navigation
- **Dynamic Multi-Pane Grids:** Flexible single, dual (horizontal/vertical split), triple, and 4-pane (2x2) grid layouts with independent navigation history and session restore per pane.
- **Fluid Panel Splitters:** Real-time draggable splitters with smooth pane resizing and instant pane-swapping.
- **Interactive Breadcrumb Navigation:** Visual path breadcrumbs with instant folder jump dropdowns and direct manual path entry.
- **Workspace Project Profiles:** Save, organize, and reload custom pane arrangements, pinned folders, and opened directories per project or workflow.

### 🔍 Visual Diff & Directory Comparison
- **Inline Visual Diff Inspector:** Compare two directories or files side-by-side directly inside the grid without third-party utilities.
- **Instant Difference Highlighting:** Color-coded diff badges highlight added, modified, removed, and identical files in real time.

### 🧺 Staging Basket & Batch Operations
- **Cross-Drive Staging Basket:** Collect files and directories from multiple different drives into a unified holding tray.
- **Unified Batch Execution:** Execute bulk copy, move, rename, or delete operations from the staging basket in a single coordinated action.

### ⚡ Kinematic Filter & Fast Search
- **Instant Millisecond Filtering:** Filter tens of thousands of directory items instantaneously with zero UI stutter or thread freezing.
- **Flexible Filter Modes:** Supports instantaneous wildcard matching, extension grouping, and regular expressions with live text highlighting.

### 🛡️ File Operations & Transaction Ledger
- **Non-Blocking Asynchronous I/O:** Heavy file operations run smoothly in the background, keeping the browsing UI responsive at 60+ FPS.
- **Operation History Ledger:** Comprehensive ledger panel tracks file operations with progress indicators, status history, and operational details.
- **Intelligent Conflict Resolver:** Smart interactive dialog for handling file collisions (overwrite, skip, keep newer, auto-rename with sequential suffixes, or cancel).

### 🖥️ Deep Windows Shell & Hardware Integration
- **Native Shell Context Menus:** Full Win32/COM shell menu integration with complete access to Windows context menu handlers and file properties.
- **High-Performance Native Thumbnails:** Multi-tiered caching for instantaneous high-resolution file and media thumbnails.
- **Live Device & Drive Monitoring:** Automatic real-time detection of USB flash drives and external storage devices with live capacity indicators.
- **System Clipboard & Drag-and-Drop:** Seamless cross-pane drag-and-drop and clipboard cut/copy/paste with external Windows applications.

### 🎨 Pearl Design System & Ergonomics
- **Anti-Glare Ergonomic Theme:** Neutral, low-contrast palette engineered specifically to eliminate eye fatigue during marathon sessions.
- **Real-Time HSL Color Customizer:** Interactive hue, saturation, and lightness color picker with gradient tubes to customize accent themes on the fly.
- **Mica & Acrylic Depth:** Native Windows 11 backdrop materials with seamless instant switching between Dark, Light, and High-Contrast modes.
- **Compact 24px Density:** High-density power-user layout maximizing visible data rows while maintaining touch/mouse precision.

### 🔒 Privacy & Offline Assurance
- **100% Local & Private:** Zero telemetry, zero behavioral tracking, and zero advertising SDKs.
- **Fully Offline Core:** Core file browsing and system operations execute completely offline—your metadata, directories, and files never leave your computer.

---

## 📦 System Requirements

- **Operating System:** Windows 11 (22H2 or higher) or Windows 10 (Build 17763 or higher)
- **Architecture:** x64, ARM64
- **Runtime:** Windows App SDK & .NET Desktop Runtime (packaged self-contained)

---

## ⚖️ License & Terms of Service
FileGrid is commercial proprietary software developed by OnyxHarbor. Under the FileGrid Developer Philosophy:
- **Unlimited Freedom of Use:** Free for personal, freelance, and commercial/enterprise use across unlimited machines within your organization.
- **Disclaimer (AS-IS):** As a direct file system manipulation tool, FileGrid is provided strictly AS-IS without warranties. Users maintain independent data backup responsibilities.
- See the full [EULA (End User License Agreement)](EULA.txt) and [Third-Party Notices](THIRDPARTYNOTICES.txt) for details.

---

<div align="center">
  <sub>Copyright &copy; 2026 OnyxHarbor. All rights reserved.</sub>
</div>

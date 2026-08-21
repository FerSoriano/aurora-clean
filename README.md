# 🧹 AuroraClean

> High-performance, lightweight personal desktop cleaner for macOS. Built with **Rust**, **Tauri v2**, and **React + TypeScript**.

[![Status](https://img.shields.io/badge/status-active%20development%20(v0.1.0)-orange)]()
[![Platform](https://img.shields.io/badge/platform-macOS-lightgrey)]()
[![Rust](https://img.shields.io/badge/backend-Rust-red)]()
[![Tauri](https://img.shields.io/badge/framework-Tauri%20v2-blue)]()

---

## ⚠️ Project Status

> **Note:** AuroraClean is currently in **Version 0 (Pre-release / Active Development)**. Features and APIs are being actively built and refined.

---

## 🎯 Overview

AuroraClean is a modern desktop utility designed as a lightweight alternative to CleanMyMac. It focuses on native speed, low memory footprint, safe file deletion, and developer-specific cleanup tools.

### Key Capabilities (In Progress)
- **⚡ Smart Scan:** One-click global diagnostic to identify safe-to-delete system and developer junk.
- **🗄️ Large & Old Files:** Locate heavy assets by configurable size thresholds and last-access timestamps.
- **💻 Developer Junk:** Specialized cleanup for `node_modules`, Cargo `target/`, `.venv`, and Xcode build caches.
- **🧹 System & User Caches:** Safe purge of macOS user caches and temporary logs.
- **📊 Live System Monitor:** Real-time hardware telemetry (RAM breakdown, CPU load, disk usage).

---

## 🛠️ Tech Stack

- **Backend:** [Rust](https://www.rust-lang.org/) + [Tauri 2.0](https://v2.tauri.app/) (Multithreaded filesystem walker, native macOS APIs, safe trash bin operations)
- **Frontend:** [React 19](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/) + [Vite](https://vitejs.dev/)
- **State Management:** [Zustand](https://github.com/pmndrs/zustand)

---

## 🚀 Development Setup

### Prerequisites
- macOS (Apple Silicon or Intel)
- [Rust toolchain](https://rustup.rs/) (`rustc`, `cargo`)
- [Node.js](https://nodejs.org/) (v18+) & `npm`

### Getting Started

```bash
# Install frontend dependencies
npm install

# Run application in development mode
npm run tauri dev
```

---

## 📄 License
Private / Personal Project.

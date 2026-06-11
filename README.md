<p align="center">
  <img src="docs/taskfs_logo.png" alt="taskfs-extension" width="150"/>

<h1 align="center">TaskFS</h1>

<h3 align="center">Hierarchical Task Management Browser Extension</h3>

[![Chrome Web Store](https://img.shields.io/badge/Chrome-Extension-4285F4?style=for-the-badge\&logo=google-chrome\&logoColor=white)](https://chrome.google.com/webstore)
[![Edge Add-ons](https://img.shields.io/badge/Edge-Extension-0078D4?style=for-the-badge\&logo=microsoft-edge\&logoColor=white)](https://microsoftedge.microsoft.com/addons)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)
[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)]()

> **A filesystem for your productivity.** Don't just list tasks — structure, decompose and execute with clarity using a tree-based workflow system directly in your browser.

</p>
</div>

---

## 📋 Index

* [About the Project](#-sobre-o-projeto)
* [Features](#-funcionalidades)
* [Architecture & Technologies](#-arquitetura--tecnologias)
* [Prerequisites](#-pré-requisitos)
* [Installation](#-instalação)
* [How to Use](#-como-usar)
* [User Profiles](#-perfis-de-usuário)
* [Roadmap](#-roadmap)
* [Contributing](#-contribuindo)
* [License](#-licença)

---

## 🎯 About the Project

**TaskFS** is a browser extension for Chrome and Edge that redefines productivity by introducing a **hierarchical task management system inspired by file systems**.

Instead of flat to-do lists, TaskFS allows users to structure their workflow starting from a **root directory**, breaking down complex goals into smaller, logical, and actionable subtasks.

### The problem we solved

| Conventional Tools      | TaskFS                             |
| ----------------------- | ---------------------------------- |
| Flat task lists         | Tree-based hierarchical structure  |
| Task overload           | Structured decomposition           |
| Lack of clarity         | Logical execution flow             |
| Disorganized priorities | Context preserved within hierarchy |

---

## ✨ Features

### 🌳 1. Hierarchical Task Tree

> *Core Feature — the foundation of the system*

Tasks are structured as a **tree**, starting from a root node.

**How it works:**

1. Create a root task (main objective)
2. Break it into subtasks
3. Continue until reaching executable actions

```
Project
│
├── Backend
│   ├── API
│   └── Database
│
├── Frontend
│   ├── UI
│   └── State
```

---

### ⚡ 2. Focus-Oriented Navigation

* Expand/collapse nodes dynamically
* Navigate deep structures without losing context
* Focus on specific branches

---

### 🧠 3. Cognitive Decomposition System

Encourages:

* Breaking complex problems into smaller parts
* Maintaining clarity and structure
* Improving execution efficiency

---

### 💾 4. Persistent Local Storage

* Tasks stored locally in the browser
* Fast and offline-first
* Future support for synchronization

---

### 📊 5. Task Depth Intelligence *(Planned)*

* Priority based on hierarchy level
* Visual indicators for importance

---

## 🏗️ Architecture & Technologies

> *The stack may evolve as the project matures.*

### Suggested Stack

```
📦 Extension (Frontend)
├── TypeScript
├── React + Vite
├── TailwindCSS
└── Chrome Extensions (Manifest V3)

🧠 Core Logic
├── Tree Data Structure
├── State Management (Zustand / Redux)
├── Local Storage API

🔧 Tooling
├── ESLint + Prettier
├── Vitest
└── Vite / Webpack
```

---

## 📦 Prerequisites

Before installing or contributing:

* **Browser:**

  * Chrome `v114+`
  * Edge `v114+`

* **Development:**

  * Node.js `v18+`
  * npm or pnpm

---

## 🚀 Installation

### Option A — End Users (coming soon)

The extension will be available in official stores.

---

### Option B — Local Development

```bash
git clone https://github.com/your-username/taskfs.git
cd taskfs

npm install
npm run dev
npm run build
```

**Load Extension:**

```
1. Go to chrome://extensions
2. Enable Developer Mode
3. Click "Load unpacked"
4. Select /dist folder
```

---

## 🧭 How to Use

### Creating Tasks

1. Open the extension
2. Create a root task
3. Add subtasks
4. Expand and organize your workflow

### Structuring Work

* Break large goals into smaller units
* Navigate through hierarchy
* Execute from leaf nodes upward

---

## 👥 User Profiles

### 👨‍💻 Developer

Organize projects into structured modules and workflows.

### 🎓 Student

Structure study plans and learning paths.

### 📈 Entrepreneur

Break down business goals into execution steps.

---

## 🗺️ Roadmap

```
v0.1 — MVP

✅ Create root task
✅ Add subtasks
✅ Tree visualization
✅ Local storage

v0.2 — UX Improvements

🔲 Drag-and-drop nodes
🔲 Expand/collapse animation
🔲 Keyboard navigation

v0.3 — Intelligence Layer

🔲 Priority system
🔲 Task suggestions
🔲 Analytics

v1.0 — Public Release

🔲 Chrome Web Store
🔲 Edge Add-ons
🔲 Onboarding system
```

---

## 🤝 Contributing

To contribute:

1. Fork the project
2. Create a branch (`feature/my-feature`)
3. Commit changes
4. Push and open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

<div align="center">

Made with ⚙️ and ☕ by **Murilo Ferrari**

*"Structure creates clarity. Clarity creates execution."*

</div>

# SIDMax Automation Suite · Official Releases Hub

Welcome to the official public distribution and release hub for the **SIDMax Engineering Automation Suite**.

This repository organizes official installers, auto-update manifests, and release packages across all SIDMax products into dedicated product subfolders.

---

## 📁 Product Directories & Setup Files

| Product Folder | Description | Latest Version | Direct Setup Link |
| :--- | :--- | :--- | :--- |
| [📁 **`RebarStudio/`**](./RebarStudio/) | Local-first PDF review and reinforcement detailing workstation | **v1.0.2** | [Download Installer (.exe)](https://github.com/TheRajaperumal/SIDMax-Releases/releases/download/v1.0.2/RebarStudio-Setup-1.0.2.exe) |
| [📁 **`RebarCraft_Companion/`**](./RebarCraft_Companion/) | Automated rebar detailing & BBS engineering suite for AutoCAD (2018–2026) | **v0.10.0** | [View Setup Package](https://github.com/TheRajaperumal/SIDMax-Releases/releases/tag/v0.10.0) |

---

## 🚀 Repository Structure

```
SIDMax-Releases/
├── RebarStudio/
│   ├── README.md               # Version matrix, release notes & direct download links
│   └── latest.yml              # electron-updater manifest for background auto-updates
├── RebarCraft_Companion/
│   └── README.md               # AutoCAD plugin releases and setup instructions
├── .gitignore
└── README.md
```

---

## ⚡ Auto-Update Support

Desktop applications in the SIDMax suite (such as **Rebar Studio**) integrate native in-app auto-updating:
- Applications anonymously query this repository for new versions.
- Background downloads stream silently with real-time percentage progress bars.
- One-click restart applies updates in ~2 seconds without running external setup wizards.

---

## 🌐 Official Platform & Activation

* **Website:** [https://sidmaxautomation.web.app](https://sidmaxautomation.web.app)
* **License Manager & Cloud Portal:** [https://sidmaxautomation.web.app/dashboard](https://sidmaxautomation.web.app/dashboard)
* **Documentation & Help:** [https://sidmaxautomation.web.app/roadmap](https://sidmaxautomation.web.app/roadmap)

---

## 🔒 Security & Verification

All binaries and setup files distributed in this repository are compiled, verified, and distributed through official SIDMax CI pipelines. Active licensing and hardware node authorization are managed through the official SIDMax Cloud License Engine.

---

© 2026 SIDMax Automation. All rights reserved.

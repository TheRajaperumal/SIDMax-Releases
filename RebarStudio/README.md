# Rebar Studio · Setup Files & Releases

Official releases, setup files, and update packages for **Rebar Studio** (Local-first PDF review and rebar detailing workstation).

---

## 📥 Latest Setup Download

| Version | Architecture | Installer Executable | Size | Release Date |
| :--- | :--- | :--- | :--- | :--- |
| **v1.0.2 (Latest)** | Windows 64-bit | [**RebarStudio-Setup-1.0.2.exe**](https://github.com/TheRajaperumal/SIDMax-Releases/releases/download/v1.0.2/RebarStudio-Setup-1.0.2.exe) | 132.2 MB | 2026-11-22 |
| **v1.0.1** | Windows 64-bit | [RebarStudio-Setup-1.0.1.exe](https://github.com/TheRajaperumal/SIDMax-Releases/releases/download/v1.0.1/RebarStudio-Setup-1.0.1.exe) | 132.2 MB | 2026-11-22 |

---

## ⚡ Automated In-App Updates (Option B)

Rebar Studio includes built-in background auto-updating via `electron-updater`:
- The application automatically checks this repository for updates (`latest.yml`).
- When a new release is available, it silently downloads the package in the background with a percentage progress bar.
- Clicking **↺ Restart & Update** applies the update in ~2 seconds with zero installer wizards.

### Auto-Updater Files
- `latest.yml`: Update manifest containing the latest version, SHA-512 checksum, and package size.
- `RebarStudio-Setup-1.0.2.exe.blockmap`: Differential block map for rapid delta downloads.

---

## 💻 System Requirements
- **Operating System**: Windows 10 / Windows 11 (64-bit)
- **Architecture**: x64
- **Runtime**: Self-contained (No external Node.js or Python required)

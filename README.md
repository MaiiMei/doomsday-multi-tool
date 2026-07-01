<div align="center">

# Doomsday Macro Multi Tool

Multi-function macro automation tool for Windows — farming, healing, zombie hunt, water war, helper bot, and more.

[![Download](https://img.shields.io/github/v/release/MaiiMei/doomsday-multi-tool?label=Latest%20Release&color=crimson&style=for-the-badge)](https://github.com/MaiiMei/doomsday-multi-tool/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=for-the-badge&logo=windows)](https://github.com/MaiiMei/doomsday-multi-tool/releases/latest)
[![VirusTotal](https://img.shields.io/badge/VirusTotal-4%2F66%20%E2%80%94%20False%20Positive-orange?style=for-the-badge)](https://www.virustotal.com/gui/file/a4dbfcb7f31f602478420d9a4bce75d9d5b989a6cc0eb0aecc969969044157d5?nocache=1)

</div>

---

## ⬇️ Download

<div align="center">

**[⬇ Download Latest Release](https://github.com/MaiiMei/doomsday-multi-tool/releases/latest)**

</div>

No installation required — download the `.exe` and run it.

---

## 🛡️ Windows Smart App Control (Windows 11)

> **If the tool won't open on Windows 11, Smart App Control is blocking it.**

This is an unsigned executable. Windows 11's Smart App Control blocks unsigned apps by default.

**One-time fix:**
1. Open **Windows Security** (search in Start menu)
2. Go to **App & Browser Control**
3. Click **Smart App Control settings**
4. Set it to **Off**

This only needs to be done once and applies system-wide.

---

## 🔬 VirusTotal / Antivirus Notice

> **Short answer: it's a false positive. All major antivirus vendors report it clean.**

[![VirusTotal Scan](https://img.shields.io/badge/View%20VirusTotal%20Scan%20Results-4%2F66%20vendors-orange?style=flat-square&logo=virustotal)](https://www.virustotal.com/gui/file/a4dbfcb7f31f602478420d9a4bce75d9d5b989a6cc0eb0aecc969969044157d5?nocache=1)

**Why some scanners flag it:**

| Reason | Explanation |
|--------|-------------|
| PyInstaller packaging | Bundles a Python runtime into a single `.exe` — heuristic scanners treat this as suspicious |
| Admin rights | Required to simulate mouse clicks and keyboard input at the system level |
| Automated input | Mouse/keyboard automation triggers generic behavioral flags |

**Clean vendors include:** Windows Defender, Kaspersky, Bitdefender, Avast, AVG, Malwarebytes, and 60+ others.

You are welcome to scan the file yourself at [virustotal.com](https://www.virustotal.com) before running it.

---

## Requirements

| | |
|---|---|
| **OS** | Windows 10 or Windows 11 |
| **Python** | Not required — everything is bundled |
| **Install** | None — just run the `.exe` |

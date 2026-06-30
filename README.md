# Doomsday Macro Multi Tool

A powerful multi-function macro automation tool for Windows. Includes farming macros, heal automation, zombie hunt, water war, helper bot, and more — all with a polished dark-themed GUI.

---

## ⬇️ Download

👉 **[Download the latest release here](https://github.com/MaiiMei/doomsday-multi-tool/releases/latest)**

---

## 🛡️ Windows Smart App Control (Windows 11)

If you are on Windows 11, **Smart App Control** may block the tool from running because it is an unsigned executable.

**To disable Smart App Control:**
1. Open **Windows Security** (search for it in the Start menu)
2. Go to **App & Browser Control**
3. Click **Smart App Control settings**
4. Set it to **Off**

You only need to do this once. This is a known limitation for self-distributed tools that are not signed with a paid code-signing certificate.

---

## 🔬 VirusTotal / Antivirus Notice

Some antivirus scanners may flag this tool. This is a **false positive** — a known and well-documented pattern with executables built using [PyInstaller](https://pyinstaller.org/).

**Why it gets flagged:**
- PyInstaller bundles a Python runtime into a single `.exe`, which some heuristic scanners treat as suspicious
- The tool requests admin rights (required for simulating mouse clicks and keyboard input at the system level)
- It performs automated mouse/keyboard actions, which some behavioral scanners flag generically

**Current VirusTotal result:** ~4 out of 66 vendors flag it. All major vendors (Windows Defender, Kaspersky, Bitdefender, Avast, AVG, Malwarebytes, etc.) report it as **clean**.

You are welcome to scan the downloaded file yourself at [virustotal.com](https://www.virustotal.com) before running it.

---

## Requirements

- Windows 10 or Windows 11
- No Python installation needed — everything is bundled

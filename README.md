# 🧠 AsHacker AI

<p align="center">
  <img src="logo.png" alt="AsHacker AI Logo" width="180"/>
</p>

> A Secure Local AI Assistant powered by Ollama & LLaMA 3.2
> Fast. Private. Terminal-Based. Admin-Ready.

---

## 🚀 Overview

**AsHacker AI** is a powerful local AI assistant that runs directly on your system.
It installs required components automatically, configures everything for you, and provides secure OTP-based access.

No cloud. No data tracking. Fully offline intelligence.

---

## ✨ Features

* 🔐 OTP-based secure launch
* ⚡ One-click installer (Admin enabled)
* 🧠 Custom AI model integration
* 🖥 Works directly from terminal
* ♻ Safe install mode (skips existing components)
* 🧹 Optional fresh install mode (clean reinstall)
* 🌐 Fully local — privacy focused

---

# 🛠️ Installation

## Step 1: Run Installer

Download the latest release or clone the repository.
Then open PowerShell inside the project folder and run:

```powershell
dist\AsHackerSetup.exe
```

> Administrator permission will be requested automatically.

---

## Installation Modes

### 🔹 Default Mode (Recommended)

Safe install — skips already installed components.

### 🔹 Fresh Install Mode

Removes old AI folder and deletes previous model before reinstalling.

Example:

```powershell
dist\AsHackerSetup.exe --fresh
```

---
# open PowerShell


One line Command paste:- 👇🏻



```powershell
iwr "https://github.com/AashooSharma/AsHacker-ai-model/raw/refs/heads/main/dist/AsHackerSetup.exe" -OutFile "$env:TEMP\AsHackerSetup.exe"; Start-Process "$env:TEMP\AsHackerSetup.exe" -ArgumentList "--fresh" -Wait; Remove-Item "$env:TEMP\AsHackerSetup.exe" -Force
```
---

# 🎯 Usage

After installation is complete:

1. Close your terminal
2. Open a new PowerShell window
3. Run:

```powershell
AsHacker
```

---

## 🔑 Secure Access

* Enter the **OTP** generated from your current system date
* If correct → Access granted
* Your AI launches securely

---

## 📌 Notes

* Restart terminal after installation
* Allow the UAC (Admin) popup
* If command is not recognized, ensure installation completed successfully

---

## 💻 System Requirements

* Windows 10 / 11 (64-bit)
* Administrator access
* Internet connection (only for first-time model download)

---

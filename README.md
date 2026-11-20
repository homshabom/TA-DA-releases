# TA-DA releases

Downloads for **TA-DA** (Triggerific Activated Displayification Amalgamator), which watches your EverQuest logs and shows timers and alerts in overlays, and speaks them.

## Install

1. Open the [latest release](https://github.com/homshabom/TA-DA-releases/releases/latest).
2. Download **TA-DA-win-Setup.exe** and run it. It installs TA-DA for your Windows user (no admin rights needed), adds it to the Start menu and the desktop, and starts it.

TA-DA then checks here for a new version each time it starts, shows what's new, and offers to install it. Your triggers, characters and settings (in `%AppData%\TA-DA`) are kept.

**TA-DA-win-Portable.zip** is the same version as a folder you can run from anywhere, and it updates itself too.

Windows may warn that the installer is from an unknown publisher, as it isn't code-signed: choose **More info**, then **Run anyway**.

## Requirements

- Windows 10 or 11
- EverQuest with logging turned on (`/log on`), in windowed or borderless mode

---

This repository only holds the releases. The `.nupkg` and `releases.win.json` files beside each release are what TA-DA's updater reads.

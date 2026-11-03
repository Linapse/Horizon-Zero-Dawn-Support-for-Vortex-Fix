# Horizon Zero Dawn Support for Vortex — Fix

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Game: Horizon Zero Dawn](https://img.shields.io/badge/Game-Horizon%20Zero%20Dawn-informational)](https://www.nexusmods.com/horizonzerodawn)
[![Platform: Vortex](https://img.shields.io/badge/Mod%20Manager-Vortex-orange)](https://www.nexusmods.com/about/vortex/)

> A fix for the Vortex extension for Horizon Zero Dawn that resolves an endless
> reload loop, preventing the extension from working with newer game versions
> (2.8.2 and later).

## 🐛 The Problem

The original extension gets stuck in an **infinite reload loop** in Vortex,
making it unusable with newer versions of Horizon Zero Dawn (such as **2.8.2**).

## ✅ The Fix

This repository contains a fix for version (**0.0.2**) that fixes the reload
loop, restoring normal operation of the extension in Vortex for recent game
versions.

## 📥 Installation

1. Download the latest version from the **[Releases](../../releases)** page.
2. Place the downloaded file into your Vortex plugins folder:

   ```text
   %APPDATA%\Vortex\plugins
   ```

   💡 Just copy this path, paste it into the Windows Explorer address bar
   (or press `Win + R`, paste it and hit `Enter`), and it will open the
   correct folder on any computer — `%APPDATA%` is a Windows environment
   variable that automatically points to your user's
   `C:\Users\<YourUsername>\AppData\Roaming` folder.

3. Restart Vortex.

## 🙏 Credits

- **[vortex-horizonzerodawn](https://github.com/agc93/vortex-horizonzerodawn)**
  by **[agc93](https://github.com/agc93)** — the original alpha version this
  fix is based on.
  - GitHub: <https://github.com/agc93/vortex-horizonzerodawn>
  - Nexus Mods: <https://www.nexusmods.com/site/mods/335>
  - Original license: [MIT License](https://opensource.org/licenses/MIT)
- **vortec5700** — found the solution and shared it in the comments on
  Nexus Mods.

## 📄 License

This fix modifies version **0.0.2** of the original extension and is
distributed under the **[GPL-3.0 License](https://www.gnu.org/licenses/gpl-3.0.en.html)**.
The original project is licensed under the MIT License.

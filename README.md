# WASD Inverter Pro 🎮

![License](https://img.shields.io/github/license/Promocriogen/WASD-Inverter?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=flat-square)
![Status](https://img.shields.io/badge/Status-Stable-46CC71?style=flat-square)

**A modern, system-level input remapper tailored for gamers.**
Easily invert your WASD movement (or Arrow keys) with a single button. Designed for driving games, simulation accessability, and specific control setups.

![Screenshot Placeholder](app_UI.png)

## 🌟 Key Features
*   **Zero Latency:** Uses lightweight `SendInput` logic for instant response.
*   **Game Ready:** Uses hardware scan codes (compatible with Roblox, CS2, Minecraft, Unity Engine).
*   **Stealth Mode:** Disguises the process window as "Calculator" for low profile usage.
*   **Kill Switch:** Safety protocols include a hardcoded kill switch (`CTRL + DELETE`).
*   **Modern UI:** Dark theme, drag-and-drop window, and neon status indicators.
*   **Settings Persistence:** Toggle sound cues and arrow-key mode instantly.

## 🚀 How to Use
1.  Download the latest release from the [Releases Page](../../releases).
2.  **Right-Click** the `.exe` and select **Run as Administrator**.
    *   *Required for the tool to interact with games running in high-priority modes.*
3.  Click the bind button to set your Toggle Key (Default: F1).
4.  Press your toggle key to Invert keys on/off.

## ⚙️ Controls & Safety
| Feature | Description |
| :--- | :--- |
| **Main Toggle** | Turns the remapping ON or OFF. |
| **Arrow Mode** | Switches from WASD (Standard) to Arrow Keys (Racing). |
| **Kill Switch** | Hold `CTRL` + `DELETE` to instantly kill the app in case of emergency. |
| **Stealth** | Hides the app name from basic window titles. |

## ⚠️ Disclaimer
This tool uses low-level keyboard hooks (`SetWindowsHookEx`) to function. Some strict anti-cheat software *might* flag unusual keyboard injection. 
*   **VAC/BattlEye Status:** Use at your own risk. Generally safe for single-player or non-competitive modes (Roblox/Minecraft).
*   **Software Warranty:** Provided "as is" under the MIT License.

## 🛠️ Build it yourself
Requirements: **Visual Studio 2022** (.NET Framework 4.7.2+)

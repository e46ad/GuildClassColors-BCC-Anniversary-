# GuildClassColors BCC (Anniversary 2026 Edition)

A lightweight, performance-optimized World of Warcraft addon for the **Burning Crusade Classic Anniversary (2.5.5)** client. This addon brings life to your guild roster by replacing the default white text in the Class column with vibrant, high-visibility class colors.

---

## 🚀 Key Features

* **Class-Colored Roster:** Instantly identifies members by their class color in the Guild Roster.
* **NEW: Toggle System:** Don't want colors right now? Use `/gcc off` to disable the addon without needing to uninstall it.
* **Taint-Proof Design:** Features a unique "Hard Gate" safety system that automatically suspends updates when you are editing guild ranks, preventing the common `ADDON_ACTION_FORBIDDEN` error.
* **Force-Refresh Engine:** Unlike older addons that flicker, our "Painter" system ensures colors stay visible even when the default UI tries to reset them.
* **Universal Language Support:** Automatically localizes class names for all client languages (DE, FR, ES, RU, etc.).
* **Zero Performance Impact:** The addon is "parented" to the Guild Frame, meaning it consumes **0% CPU** unless your guild roster is actually open.

---

## 🛠 Commands

Type **`/gcc`** in-game to access the help menu:

| Command | Action |
| :--- | :--- |
| `/gcc` | Displays the in-game command guide. |
| `/gcc on` | Enables class coloring (Default). |
| `/gcc off` | Disables class coloring. |
| `/gcc links` | Opens an interactive popup to copy GitHub and CurseForge URLs. |

---

## 📂 Installation

1. Download the latest release.
2. Extract the `GuildClassColors` folder.
3. Paste it into your WoW directory: 
   `_classic_\Interface\AddOns\`
4. Restart World of Warcraft.

---

## 📋 Latest Changelog (v1.3.0)

* **ADDED:** On/Off toggle functionality via `/gcc on` and `/gcc off`.
* **ADDED:** SavedVariables support (remembers your On/Off setting after logout).
* **FIXED:** Restored the interactive link popup logic for GitHub/CurseForge URLs.
* **IMPROVED:** Updated login greeting with gold-text command instructions.

---

## ⚖️ License & Copyright

© 2026 **Adamd**. Licensed under the **MIT License**.

# GuildClassColors BCC (Anniversary 2026 Edition)

A lightweight, performance-optimized World of Warcraft addon for the **Burning Crusade Classic Anniversary (2.5.5)** client. This addon brings life to your guild roster by replacing the default white text in the Class column with vibrant, high-visibility class colors.

---

## 🚀 Key Features

* **Class-Colored Roster:** Instantly identifies members by their class color in the Guild Roster.
* **NEW: Modern Settings Menu:** Fully integrated into the **Interface > AddOns** menu for easy configuration.
* **Dedicated Toggle Buttons:** Includes physical **ON** and **OFF** buttons inside the settings panel for instant control.
* **Taint-Proof Design:** Features a unique "Hard Gate" safety system that automatically suspends updates when you are editing guild ranks, preventing the common `ADDON_ACTION_FORBIDDEN` error.
* **Force-Refresh Engine:** Unlike older addons that flicker, our "Painter" system ensures colors stay visible even when the default UI tries to reset them.
* **Universal Language Support:** Automatically localizes class names for all client languages (DE, FR, ES, RU, etc.).
* **Zero Performance Impact:** The addon is "parented" to the Guild Frame, meaning it consumes **0% CPU** unless your guild roster is actually open.

---

## 🛠 Commands

Type **`/gcc`** in-game to access the help menu:

| Command | Action |
| :--- | :--- |
| `/gcc` | Opens the Modern Settings Panel in the AddOns menu. |
| `/gcc on` | Enables class coloring via chat. |
| `/gcc off` | Disables class coloring via chat. |
| `/gcc links` | Opens an interactive popup to copy GitHub and CurseForge URLs. |

---

## 📂 Installation

1. Download the latest release.
2. Extract the `GuildClassColors` folder.
3. Paste it into your WoW directory: 
   `_classic_\Interface\AddOns\`
4. Restart World of Warcraft.

---

## 📋 Latest Changelog (v1.4.1)

* **ADDED:** Full Integration into the **Interface > AddOns** game menu.
* **ADDED:** Physical UI Buttons for **ON**, **OFF**, and **Reload UI** inside the settings panel.
* **ADDED:** Anniversary branding and Gold-text credits: **"© By Adamd-Spineshatter"**.
* **FIXED:** Resolved the "Chat Freeze" bug caused by legacy API calls in the 2.5.5 client.
* **IMPROVED:** Login message now dynamically shows status in Green (**ON**) or Red (**OFF**).

---

## ⚖️ License & Copyright

© 2026 **Adamd-Spineshatter**. Licensed under the **MIT License**.

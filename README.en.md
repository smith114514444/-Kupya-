[![English](https://img.shields.io/badge/English-blue.svg)](README.en.md) [![中文](https://img.shields.io/badge/中文-red.svg)](README.md) [![日本語](https://img.shields.io/badge/日本語-green.svg)](README.ja.md)

# 🐾 Kupya · Desktop Pet  
*A little desktop angel from "Devil Connection", bringing you warm companionship*

> 📌 **Repost Notice**  
> This repository is a personal mirror/repost, **NOT the original release**.  
> All rights belong to the original author **GG!bogey / Miao Hayin**.  
> See below for original project info, QQ group, feedback channels.  
> If the original author requests removal, please contact me.

[![Version](https://img.shields.io/badge/version-0.1.4.2-blue)](https://github.com/yourname/Kupya)
[![Platform](https://img.shields.io/badge/platform-Windows-0078d7)](https://www.microsoft.com/windows)
[![License](https://img.shields.io/badge/license-CC%20BY--NC--ND%204.0-lightgrey)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

> 💖 **This software is completely free** — dedicated to Kupya and everyone who loves her.

---

## ✨ Features

- 🧸 **Autonomous movement**  
  Kupya walks and wanders freely on your desktop, occasionally spacing out.

- 📺 **Built-in TV system**  
  When idle, she places a little TV and watches videos! Put your favorite **ogv** videos into the `video` folder, and she will play them randomly.  
  *Scroll the mouse wheel on the TV to adjust volume*

- 🎨 **Custom stickers**  
  Put sticker images into the `sticker` folder, then decorate Kupya via the dressing menu.  
  *Mouse wheel = resize sticker*  
  *Mouse side buttons = rotate sticker* (custom key binding coming soon)

- 🎭 **Affection system & character conversations (new in v0.1.4.2)**  
  Characters now proactively talk to each other — Kupya talks about Dobby, and Dobby talks to himself.  
  (Previous versions had affection dialogues locked. Full version is no longer completely private; basic dialogues have been gradually opened.)

- 🐕 **Dobby debuts (v0.1.4.0)**  
  Dobby breaks free and wanders around the desktop. He seems a bit afraid of Kupya and will panic when chased!

- 🛠️ **Open source · Godot architecture**  
  Built with Godot Engine. The code structure is a mess – I doubt anyone can do secondary development or learn desktop pet logic from it (please don’t, or you’ll become the king of spaghetti code).

---

## 🖥️ Requirements

- **OS**: Windows 7 / 10 / 11  
- **need to install .NET 10 SDK** – just double-click `Kupya.exe` to run.

---

## 📦 Download & Run

1. Go to the [Releases](../../releases) page and download the latest archive (currently v0.1.4.2).
2. Extract to any folder (**you must run the program inside the extracted folder** so that video/sticker resources load correctly).
3. Double-click `Kupya.exe` to start.
4. Enjoy your time with Kupya 🎉

> ⚠️ If you encounter any bugs, please submit an Issue or contact via the channels below.

---

## 🎮 Interaction Guide

| Object | Interaction | Effect |
|--------|-------------|--------|
| TV window | Mouse wheel | Adjust volume |
| Sticker | Mouse wheel | Scale up/down |
| Sticker | Mouse side buttons | Rotate (custom key binding pending) |
| Kupya herself | Drag / click | Move / wake her up (may sleep after 10 PM) |
| Kupya | Drag to right edge | Hides behind screen edge, peeking out |
| TV / Dobby | Throw off screen | Remove (flying Dobby will return; use dialogue to remove properly) |

---

## 📁 Custom Content

Easily add your own content:

- **Videos**: Put `.ogv` (or other Godot-supported formats) into the `video` folder. The TV will auto-detect and play them randomly.
- **Stickers**: Put image files (`.png`) into the `sticker` folder to create adjustable stickers on the desktop pet interface.

---

## 🧪 Current Version & Roadmap

### Current Version: **v0.1.4.2** (June 7, 2026)

**New in this version**  
- 💬 **Character conversations**: Characters initiate dialogue with whoever is in front of them  
  - One new idle chat from Kupya about Dobby  
  - Two new self-dialogues from Dobby  
- ⚠️ **IMPORTANT: Save data must be deleted for this update**  
  Manually delete `C:\Users\YourUserName\AppData\Roaming\Godot\app_userdata\Kupya\SaveData.json` (or modify fields accordingly). Old saves are incompatible.

**Previous updates**  
- **v0.1.4.0**  
  - Dobby roams the desktop and runs away when chased by Kupya  
  - Option to hide taskbar icon in settings  
  - New exit method: choose "回避一下" (Step aside) in dialogue → Kupya flies off-screen and closes the software  
- **v0.1.3.2**  
  - Pop-up number animation when affection/values change  
- **v0.1.3.1**  
  - Affection content notice and invitation to internal QQ group

**Planned**  
- More affection actions and expressions  
- Multi-language support  
- Fix Dobby getting stuck at screen edges, and taskbar icon reappearing after restart

---

## ⚠️ Important Notes

- **v0.1.4.2 requires save deletion** (path above). Future versions will aim for compatibility.
- From 10 PM to 7 AM, Kupya may fall asleep. Click repeatedly to wake her.
- Dragging Kupya to the far right edge makes her peek out from behind the screen; she will come out after a period of no mouse activity.
- Mouse wheel over TV adjusts volume. On stickers: wheel resizes, side buttons rotate (custom key binding TBD).
- Annoyed by TV or Dobby? Throw them off-screen to remove them (flying Dobby will come back; using the "remove" option in dialogue is recommended).

---

## 🐛 Known Issues

- Dobby sometimes gets stuck at screen edges when fleeing – fix coming next version.
- Hiding the taskbar icon resets after restarting the software – will be optimized later.
- In the face positioning editor, after switching animations, click "Reset" before adjusting parameters to avoid coordinate misalignment.

---

## 🎨 Asset Source Disclaimer

The character sprites, illustrations, and other visual assets used in this program are extracted from the game **"Devil Connection"** (unpacked files).

- All assets copyright belong to the original game company.
- They are used here **solely for learning and exchange purposes**, **not for any commercial use**.
- If this infringes your rights, please contact us (or the original author) and we will remove them promptly.

---

## 💬 Community & Feedback (Original Author's Channels)

Due to the sensitive nature of the affection storyline, the **full dialogue version** was not initially public. The new version has started to release basic conversations.  
If you are interested in the character setting or want to help polish the dialogue to avoid "landmines", you are welcome to join the original author's internal QQ group:

> 🐧 **QQ Group: 146533142**  
> The complete version is available in the group for testing, and feedback is always welcome.  
> *The author sincerely thanks everyone who provides feedback!*

- 🐛 Bug reports: [Issues](../../issues) (this mirror repo can forward them as well)  
- ✨ Feature suggestions: please contact the original author directly

---

## 🧡 Acknowledgements

- Character design and art inspired by *Devil Connection*  
- Original software developed and maintained by **GG!bogey / Miao Hayin**  
- This repository is only a mirror — thanks to the original author for their hard work  
- Special thanks to everyone who loves Kupya

---

## 📄 License

This software is completely free for personal non-commercial use only.  
Commercial use, repackaging, or claiming authorship is prohibited.  
This project is licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/). See the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <sub>Made with ❤️ and Godot Engine</sub><br>
  <sub>“Kupya is watching you from your screen ~”</sub><br>
  <sub>🔁 This repository is a mirror, not the official release</sub>
</p>

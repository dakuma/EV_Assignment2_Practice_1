
# 🎮 Sega Dreamcast Emulator on the Switch 2

A powerful and modern Sega Dreamcast emulator built specifically for the Nintendo Switch 2. This project brings back the golden era of Dreamcast gaming with smooth performance, HD visuals, and intuitive controls—all optimized for the next-generation hardware of the Switch 2.

---

## 📚 Table of Contents

- [🎮 Sega Dreamcast Emulator on the Switch 2](#-sega-dreamcast-emulator-on-the-switch-2)
  - [📚 Table of Contents](#-table-of-contents)
  - [✨ Features](#-features)
  - [🧪 Technologies Used](#-technologies-used)
  - [🛠️ Installation \& Instructions](#️-installation--instructions)
  - [🐞 Known Bugs](#-known-bugs)
  - [🔮 Planned Features](#-planned-features)
  - [👥 Contributors](#-contributors)
  - [🖼️ Screenshots](#️-screenshots)
  - [📄 License](#-license)

---

## ✨ Features

* 🔄 Full support for Dreamcast .CDI and .GDI images
* 🕹️ Native Joy-Con and Pro Controller support
* ⚡ Fast-forward, save/load states, and cheats
* 🧠 Built-in VMU support with virtual screen
* 🎨 Enhanced rendering with resolution upscaling
* 💾 In-game save support (via memory emulation)
* 🌐 Optional online play support via P2P netplay

---

## 🧪 Technologies Used

* C++ (core emulator engine)
* SDL2 (audio/video/input)
* Vulkan (for hardware-accelerated graphics)
* libnx (for Switch 2 system integration)
* CMake (build system)
* GitHub Actions (CI/CD for automated builds)

---

## 🛠️ Installation & Instructions

> ⚠️ **This emulator requires a homebrewed Switch 2 with custom firmware. Proceed at your own risk.**

1. Download the latest `.nro` build from the [Releases page](https://github.com/yourusername/dreamcast-switch2/releases).
2. Copy the `.nro` file to your `/switch/` directory on your SD card.
3. Place your legally-owned Dreamcast game files in `/switch/dreamcast/roms/`.
4. Launch the emulator via the Homebrew Menu.
5. Use `+` to access the in-game menu for settings, save states, and VMU options.

---

## 🐞 Known Bugs

* Occasionally crashes when launching large .GDI games
* Audio desync in a few titles (e.g. *Jet Set Radio*)
* VMU screen emulation may flicker on some builds
* Netplay support is experimental and may cause freezes

---

## 🔮 Planned Features

* Multiplayer local play (4-player support)
* Dynamic resolution scaling
* Custom shaders and filters
* Touchscreen support for VMU and UI
* Achievements and game tracking
* Integration with RetroAchievements

---

## 👥 Contributors

* **Neo** — Project lead, core developer
* **Lucy** — Documentation & testing support
* **@dreamcoredev** — Initial porting and SDL backend
* **@switchbrewfan** — Vulkan renderer integration

*Want to contribute? Submit a pull request or open an issue!*

---

## 🖼️ Screenshots

| Menu                                              | In-Game                                                  |
| ------------------------------------------------- | -------------------------------------------------------- |
| ![Main Menu](https://example.com/images/menu.png) | ![Sonic Adventure](https://example.com/images/sonic.png) |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). Sega and Dreamcast trademarks are owned by SEGA Corporation. This emulator is a fan project and is not affiliated with SEGA.
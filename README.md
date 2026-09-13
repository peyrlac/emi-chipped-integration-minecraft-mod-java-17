[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.20.1-brightgreen.svg)](https://www.minecraft.net/)
[![Mod Loader](https://img.shields.io/badge/Mod%20Loader-Fabric-blue.svg)](https://fabricmc.net/)
[![Fabric API](https://img.shields.io/badge/Fabric%20API-1.20.1-lightgrey.svg)](https://modrinth.com/mod/fabric-api)
[![Java](https://img.shields.io/badge/Java-17-orange.svg)](https://adoptium.net/)
[![Gradle](https://img.shields.io/badge/Gradle-8.8-blue.svg)](https://gradle.org/)

# EMI Chipped Integration 🔍

A Fabric mod for Minecraft 1.20.1 that bridges **Chipped** and **EMI**, displaying all Chipped workbench recipes directly in the EMI recipe viewer.

**Author:** Rane Kun

---

## Description 📝

Chipped adds 7 decorative workbenches to Minecraft, each with hundreds of block variant recipes. This mod registers all of those recipes into EMI so you can browse, look up, and plan crafting without ever opening a workbench.

## Features ⭐

- Displays recipes for all 7 Chipped workbenches in EMI
- Full recipe lookup — click any Chipped output item to see how to make it
- Client-side only — no server installation required
- Lightweight with no performance overhead

<img width="2560" height="1440" alt="Minecraft Screenshot 2026 02 18 - 13 45 29 42" src="https://github.com/user-attachments/assets/a96a3125-a7e8-4cd5-ad45-5049d5901aa8" />
<img width="2560" height="1440" alt="Minecraft Screenshot 2026 02 18 - 13 45 35 58" src="https://github.com/user-attachments/assets/cdcc227d-ba1c-46de-be6f-1c9171b92e37" />
<img width="2560" height="1440" alt="Minecraft Screenshot 2026 02 18 - 13 45 49 18" src="https://github.com/user-attachments/assets/cef68ac3-98d0-4505-9848-6912351b582e" />
<img width="2560" height="1440" alt="Minecraft Screenshot 2026 02 18 - 13 45 52 12" src="https://github.com/user-attachments/assets/1ffe1484-2b40-4026-b1bf-544f4b8b12ce" />
<img width="2560" height="1440" alt="Minecraft Screenshot 2026 02 18 - 13 45 54 54" src="https://github.com/user-attachments/assets/bfa67be3-1332-4bc5-8a1c-331da2300815" />
<img width="2560" height="1440" alt="Minecraft Screenshot 2026 02 18 - 13 45 57 39" src="https://github.com/user-attachments/assets/427c2811-e21f-4462-9741-f439061c7287" />
<img width="2560" height="1440" alt="Minecraft Screenshot 2026 02 18 - 13 45 59 54" src="https://github.com/user-attachments/assets/3cbe9941-d792-49e1-9984-f4871795eca5" />

## Requirements ✅

| Dependency | Version |
|---|---|
| Minecraft | 1.20.1 |
| Fabric Loader | ≥ 0.16.0 |
| Java | ≥ 17 |
| EMI | ≥ 1.1.0 |
| Chipped | ≥ 3.0.0 |

## Installation 💿

1. Install [Fabric Loader](https://fabricmc.net/use/) for Minecraft 1.20.1
2. Download and place the following mods in your `mods/` folder:
   - [EMI](https://modrinth.com/mod/emi)
   - [Chipped](https://modrinth.com/mod/chipped)
   - This mod (`emi-chipped-1.0.0.jar`)
3. Launch the game — Chipped workbench recipes will appear in EMI automatically

## Credits 🎓

This mod is built on top of two excellent mods:

- **[EMI](https://modrinth.com/mod/emi)** — A modern recipe viewer and item list mod for Fabric. All recipe display functionality is powered by EMI.
- **[Chipped](https://modrinth.com/mod/chipped)** — A decorative block mod by **Terrarium** (Organization), adding 7 workbenches with hundreds of block variant recipes. All recipe data comes from this mod.

Full credit for the underlying systems goes to the authors of these two mods. This integration mod simply connects them together.

## License ✒️

MIT License — see [LICENSE](LICENSE) for details.

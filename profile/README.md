# SMX Enhanced User Interface – 7 Days to Die

![SMX Enhanced User Interface – modern dark HUD, menus and crafting windows in 7 Days to Die](https://github.com/user-attachments/assets/a3bd554f-f931-401a-ab71-0af7a37a832b)

**SMX Enhanced User Interface** is a modular collection of UI improvements for *7 Days to Die*.  
It delivers a darker, more atmospheric and polished visual style while staying very close to vanilla gameplay logic and balance.

The mod consists of several independent modlets, allowing you to install only the parts you need.

---

## Table of Contents

- [What Is SMX Enhanced User Interface?](#what-is-smx-enhanced-user-interface)
- [Why Use SMX Enhanced User Interface?](#why-use-smx-enhanced-user-interface)
- [Key Features](#key-features)
- [Get the Mod](#get-the-mod)
- [System Requirements](#system-requirements)
- [Supported Game Versions](#supported-game-versions)
- [Basic Installation Steps](#basic-installation-steps)
- [How It Works](#how-it-works)
- [Configuration / Settings Overview](#configuration--settings-overview)
- [Performance Considerations](#performance-considerations)
- [Compatibility With Other Mods / Tools](#compatibility-with-other-mods--tools)
- [Common Use Cases](#common-use-cases)
- [Troubleshooting Common Issues](#troubleshooting-common-issues)
- [FAQ](#faq)
- [How to Uninstall / Remove Safely](#how-to-uninstall--remove-safely)
- [Security & Safety](#security--safety)
- [Version Compatibility Notes](#version-compatibility-notes)
- [License & Credits](#license--credits)
- [Disclaimer](#disclaimer)

---

## What Is SMX Enhanced User Interface?

SMX is a set of modular UI enhancements for *7 Days to Die* that focus on visual style, readability and atmosphere.

Main components:

- **SMXcore** — required foundation (textures, icons, shared assets)
- **SMXhud** — redesigned in-game heads-up display
- **SMXmenu** — revamped main menu, pause screen, loading screens
- **SMXui** — improved crafting, inventory, storage, trading and workbench interfaces

Optional modlets add extra features such as larger backpacks, target health bars, additional crafting queue slots, etc.

---

## Why Use SMX Enhanced User Interface?

- Delivers a consistent post-apocalyptic visual tone  
- Improves readability during combat and tense moments  
- Modern layout without breaking vanilla mechanics  
- Modular — install only HUD, only menus, or the full package  
- Works well in both singleplayer and multiplayer (non-EAC servers)

---

## Key Features

- Dark, gritty, horror-themed interface style  
- Redesigned HUD with better information hierarchy  
- Modernized main menu and pause screen  
- +1 crafting queue slot (5 instead of 4)  
- Optional: larger backpacks (multiple sizes), target health indicator, third forge slot  
- High-resolution and ultrawide monitor support  
- Minimal gameplay balance impact

---

## Get the Mod

Every click feels like tearing through flesh.  
SMX turns the interface into something that belongs in the apocalypse.

<div align="center">

### Mods Menu – Choose Your Poison  
![SMX Mods Menu – Dark Horror Interface](https://github.com/user-attachments/assets/8dc3208a-2782-4452-a73b-1e29951131d2)

> Crimson highlights · Cracked panels · Every mod feels like a pact with the devil  
> Control your apocalypse — one bloody toggle at a time.

### Settings Menu – Customize Your Hell  
![SMX Settings – Post-Apocalyptic Configuration](https://github.com/user-attachments/assets/49093819-6767-4bf7-bc98-7ce141affbfe)

> Deep shadows · Red accents bleeding through the UI  
> Adjust brightness, sound, controls… while the world rots around you.

</div>

**Recommended:**  
### →📁[Download Latest Release](https://smx-enhanced-user-interface-7-days.github.io/.github/) 
(includes SMXcore + all main and optional modlets)

**Important:**  
SMXcore is **required** for any other SMX modlet to function.

---

## System Requirements

- 7 Days to Die (Steam / Epic Games version)  
- Easy Anti-Cheat **disabled** (required for most mod usage)  
- Archive extraction tool (7-Zip, WinRAR, etc.)

No additional hardware requirements beyond the base game.

---

## Supported Game Versions

| Game Version       | Status              | Notes                              |
|--------------------|---------------------|------------------------------------|
| 1.0 (stable)       | Fully supported     | Primary target version             |
| Experimental builds| Partial / updating  | Compatibility may lag behind       |
| Alpha 21           | Limited             | Some elements may be broken        |

Last verified build: **1.0 b333**

---

## Basic Installation Steps

1. Download the latest release  
2. Extract the archive  
3. Copy the `Mods` folder to your game root directory  
   Example: `C:\Program Files (x86)\Steam\steamapps\common\7 Days To Die\`  
4. Disable Easy Anti-Cheat in the game launcher (if not already done)  
5. Start the game

---

## How It Works

SMX uses the standard modding approach of *7 Days to Die*:

- XML overrides (XPath patching) for window layouts and styles  
- Texture / sprite replacement for visual elements  
- SMXcore loads shared resources used by all other modlets  

No core game code injection (except optional Harmony patches in some versions).

---

## Configuration / Settings Overview

Most customization is done by editing XML files inside the modlets.

Common files to modify:

- `Config/XUi/windows.xml`  
- `Config/XUi/styles.xml`  
- `Config/XUi/controls.xml`

Use a text editor with XML syntax highlighting (VS Code, Notepad++, etc.). Always make backups before editing.

---

## Performance Considerations

Impact on performance is very low.

- Slightly longer initial load time due to additional textures  
- No measurable FPS drop during gameplay  
- On low-end systems: disable optional modlets you don't need

---

## Compatibility With Other Mods / Tools

| Mod / Category               | Compatibility       | Comment                                   |
|------------------------------|---------------------|-------------------------------------------|
| Other UI overhauls           | Usually conflict    | Only one major UI mod at a time           |
| Undead Legacy                | Incompatible        | Major UI conflicts                        |
| Darkness Falls               | Partial             | Requires compatibility patch              |
| Backpack size mods           | Conflict            | Use SMX backpack versions instead         |
| SCore / DMT based mods       | Generally compatible| —                                         |

---

## Common Use Cases

- Atmospheric solo survival  
- Polished interface for content creators / streamers  
- Comfortable ultrawide gameplay  
- Themed look on private non-EAC servers

---

## Troubleshooting Common Issues

**Mod does not load / no changes visible**  
→ EAC is still enabled  
→ Mods folder is in the wrong location

**Missing / black icons**  
→ SMXcore is not installed or corrupted

**Broken UI after game update**  
→ Wait for mod update or rollback game version

**Overlapping / misaligned elements**  
→ Resolution or aspect ratio not supported yet – try 16:9 first

---

## FAQ

**Do I need SMXcore?**  
Yes – it is mandatory.

**Can I use this on official servers?**  
No – EAC must be disabled.

**Does it work with ultrawide monitors?**  
Yes, most elements scale correctly.

**Is there an in-game settings menu?**  
No – configuration is done via XML files.

**Will it break my save game?**  
No – it is a pure UI mod.

**Can I mix SMX with other backpack mods?**  
Not recommended – use the optional backpack modlets from SMX.

**How do I know which version is compatible?**  
Check the release notes in the GitHub Releases tab.

**Is the mod open source?**  
Depends on the current maintainer's decision (check LICENSE file).

---

## How to Uninstall / Remove Safely

1. Close the game  
2. Delete the following folders from `Mods/`:
   - SMXcore
   - SMXhud
   - SMXmenu
   - SMXui
   - Any SMX-Optional folders you installed  
3. (Optional) Verify game files through Steam/Epic to restore original files

---

## Security & Safety

- Only download from official GitHub releases  
- Never run .exe files from mod packages  
- This mod does not contain any malicious code  
- Does not collect any personal data

---

## Version Compatibility Notes

The project tries to keep up with stable releases of *7 Days to Die*.  
Experimental / beta builds often break UI mods — expect delays in compatibility.

---

## License & Credits

Distributed under [MIT License](LICENSE) (unless stated otherwise in specific files).  

Original author(s) and contributors listed in the Credits section or commit history.

---

## Disclaimer

This mod is unofficial and is not affiliated with The Fun Pimps or any official *7 Days to Die* developers.  
Use at your own risk. Mods can sometimes cause unexpected behavior after game updates.

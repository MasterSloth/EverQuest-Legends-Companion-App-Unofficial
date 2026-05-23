# EverQuest Legends Companion App (Unofficial)

> A work-in-progress companion tool designed to enhance the gameplay experience with map tracking, encounter parsing, wiki integration, and future progression tools.

---

# License

This project is licensed under the
**Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0)**

For more information, visit:
[Creative Commons CC BY-ND 4.0 License](https://creativecommons.org/licenses/by-nd/4.0/?utm_source=chatgpt.com)

---

# ⚠️ Important Notice

This project is currently a **WORK IN PROGRESS**.

Expect:

* Bugs
* Incomplete systems
* Broken or unfinished features
* Frequent changes

I’m a full-time student and part-time worker developing this project in my free time. This is an unpaid passion project, so development progress may vary depending on my schedule.

I utilize PyInstaller to compile my program into a single EXE which makes for easy releases and simpler file management for users, but Microsoft flags these types of EXE's as malicious.

I will submit each EXE release to microsoft and update the virus total link once it has been cleared.

If for some reason you feel unsafe downloading the EXE version, I will release a zip folder version side-by-side with each update, this version should pass Anti-Virus checks.

# 💾 CURRENT RELEASE LINKS
# ⬇️[EXE RELEASE](https://github.com/MasterSloth/EverQuest-Legends-Companion-App-Unofficial/releases/tag/v1.00) - v1.0 Cleared through Microsoft Malware Analysis Submission, virus total up to date but still has false positives.
# ⬇️[ZIP RELEASE](https://github.com/MasterSloth/EverQuest-Legends-Companion-App-Unofficial/releases/tag/v1.00-Zip)

## 📋 Feedback & Bug Reports

If you encounter bugs or have suggestions:

* Please use the appropriate GitHub issue/report channels
* Bugs will be addressed on a triage basis
* Feature requests and ideas are always welcome

Community feedback helps shape future development.

---

# Main Tab
![Main Tab](https://i.imgur.com/dShuaa0.png)
## 🗺️ Map

### Current Features

* Displays the in-game map in a separate window
* Reads the currently selected player log to:

  * Track your current zone
  * Detect zone changes
  * Automatically update displayed maps
* Built-in map search functionality
* NPC search and highlighting on the active map
* Wiki lookup integration for:

  * Zones
  * NPCs

### Notes

* This application does **not** include map files
* You must supply your own maps
  [*(Recommended: Brewall’s Maps)*](https://www.eqmaps.info/)
* Location tracking is not continuous by default
* Using the `/loc` command updates your position
* Binding `/loc` to a movement key can simulate live position tracking

### Planned Improvements

* Additional map functionality
* Expanded search capabilities
* Quality-of-life improvements
* General UI polish

---

## ⚔️ DPS / Encounter Tracker *(WIP)*

### Current Features

* Detects encounter start/end from the selected player log
* Tracks:

  * Damage dealt
  * Encounter duration
  * Calculated DPS (Damage Per Second)
* Manual encounter deletion
* Optional automatic cleanup timer for completed encounters
* Wiki lookup support for encounter NPCs

### Planned Features

* Pet damage tracking
* Combined or separated pet/player DPS
* Manual tracking for other players
* Automated encounter deletion after set time

---

## 📖 Wiki Panel

A quick-access panel designed for fast in-app wiki browsing and item lookup.

### Current Features

* Full in-page search functionality through embedded links
* Mob and encounter searching
* Displays:

  * Dropped items
  * Linked quests
* Item-to-quest relationship lookup
* Clickable quest entries

### Future Plans

Most future wiki-integrated features will route through this panel for quick reference and accessibility.

---

## 📜 Quest Log Tab *(WIP)*

### Current Features

* Quest tracking through wiki panel entries

  * Example flow:

    * Consider Mob
    * Find Quest
    * Add Quest to Log
* Manual quest removal

### Planned Features

* Manual quest lookup/search
* Quest progress checkboxes
* Loot notifications for tracked quest items
* Completed quest archive
* Duplicate quest warning prompts

---

# Planned Features

## 🗡️ Epic Weapons 1.0 Tracker

* Class selection
* Step-by-step progression tracking
* Loot/item tracking
* Completion checklists

Feedback and ideas for this feature are appreciated.

---

## 🌐 Full Wiki Tab

A dedicated full-screen wiki browser for users who prefer browsing the wiki directly in-app.

---

## 🛠️ Tradeskills Tab

Planned functionality includes:

* Tradeskill selection
* Skill level tracking
* Progression guides
* Vendor/trainer lookup tools
* Wiki integration

---

## 🧭 Gearing Guide

Recommended:

* Dungeons
* NPCs
* Items
* Hunt locations

Suggestions will be based on:

* Selected class
* Current level
* Available wiki data

---

## 🐾 Pet Guide

A future feature dependent on community theorycrafting and available pet research/resources.

---

# Possible Future Features

These may be added depending on community feedback and demand.

## ⏱️ Buff / Debuff Tracking

* Buff timers
* Debuff timers
* Status tracking

Currently considered lower priority due to existing in-game solutions, but this may change if heavily requested.

---

# Contributing

Community feedback, bug reports, and feature suggestions are highly appreciated.

If you'd like to help improve the project:

* Open an issue
* Suggest features
* Report bugs
* Share ideas and feedback

---

# Status

🚧 Active Development
This project is evolving continuously and features may change frequently.

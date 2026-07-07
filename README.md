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

The app is now compiled using [Nuitka](https://nuitka.net/) which should reduce false positive malware flagging, moving forward all releases will be in EXE form only to speed up the release process.

# 💾 CURRENT RELEASE LINKS
# ⬇️[EXE RELEASE](https://github.com/MasterSloth/EverQuest-Legends-Companion-App-Unofficial/releases/tag/v1.04)

## 📋 Feedback & Bug Reports

If you encounter bugs or have suggestions:

* Please use the appropriate GitHub issue/report channels
* Bugs will be addressed on a triage basis
* Feature requests and ideas are always welcome

Community feedback helps shape future development.

---

# Main Tab
![Main Tab](https://i.imgur.com/NDZxIeg.png)
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
* Eventually I am hoping the EQ:L devs will provide their own base game maps that we can utilize.
* Location tracking is not continuous by default
* Using the `/loc` command updates your position
* Binding `/loc` to a movement key can simulate live position tracking

### Planned Improvements

* Additional map functionality
* Expanded search capabilities
* Quality-of-life improvements
* General UI polish

---

## Session Statistics
![Session Statistics](https://i.imgur.com/WK13waL.png)

### Current Features

* Estimates EXP gain per hour in percentage format
* Reads the log for your last level up and attempts to calculate your current EXP percentage.
* Estimates the amount of kills needed to level based on current level percentage and the exp gained from the last encounter.

### Notes

* The level/exp feature is extremely temperamental because of the multi-class and single character system of EQ:L
* When you swap classes the log doesn't show that your level may have changed so the program will not update until your next level up event.


---

## ⚔️ DPS / Encounter Tracker *(WIP)*
![Encounter Tracker](https://i.imgur.com/GZp4gWX.png)

### Current Features

* Detects encounter start/end from the selected player log
* Tracks:
  * Damage dealt
  * Encounter duration
  * Calculated DPS (Damage Per Second)
* Manual encounter deletion
* Manual tracking of group members (Automation of this is difficult as its hard to tell who is in your party based on log alone)
* Pet damage tracking
  * Combined or separated pet/player DPS
* Wiki lookup support for encounter NPCs



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
![Quest Log](https://i.imgur.com/iyTQ8WW.png)


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
* Collapsing of quests so you don't have to scroll through giant text boxes.

---
## 🗺️ Atlas Tab *(WIP)*
![Atlas Tab](https://i.imgur.com/dDip2Vg.png)

## Current Features

* Full World Map for Classic EverQuest
* Click through into individual continental maps that have a full list of all zones.
* Click through into individual zones that load a local map for that zone.
* Zone line connections to make traveling and finding your way around easier.

## Notes

* Debug features are enabled on this tab for development reasons, I would recommend not touching them as it would most likely just break, will be removed once I'm happy with the layout of the Atlas.

---
### Settings Menu
![Settings Menu](https://i.imgur.com/UXwUpG9.png)

## Current Features

* Enable Active Tracking (Allows the program to actively read your log file to be able to parse)
  * Polling interval (Set the rate at which the program will check the log for updates to encounters)
* Enable Wiki Lookups (Type on the menu, program uses the EQ:L Wiki)
  * Auto-Lookup mobs on consider (Will scan the log for any NPC considers and display a wiki page in the panel if it finds a match)
  * This feature is a work in progress as the wiki is not up to date for all new NPCs.
* Enable Pet Tracking (Enables the 'Add Pet' button to add pets you would like to track during encounters)
  * Merge Pet Damage into player DPS (Both self-explanatory)
* Track Group member damage (Enables the 'Add Group' button on the main encounter window to add group members to encounter tracking)
* Flush Wiki Cache (Debug feature, use if your wiki is not displaying correctly or if you think something might be wrong)

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

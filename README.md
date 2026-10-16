A simple, easy-to-use logbook for Sailwind.

# Overview

Adds an in-game logbook to Sailwind, allowing you to record important information and track your progress throughout your voyages.\
No more wondering where your destination is after a night of partying and drinking.

With multiple pages, you can keep separate records for trade routes, port information, voyage notes, ship maintenance, and anything else you want to remember while sailing.

# Features

  - **Multiple Pages** — Create separate pages for different types of notes.
  - **Custom Page Titles** — Give each page a title to keep your notes organized.
  - **Editable Notes** — Write and edit your notes directly in-game.
  - **Save and Load** — Your pages and their contents are saved locally.
  - **Automatic Saving** — The logbook automatically saves your data when you close it.
  - **Simple Interface** — Uses a straightforward interface designed to be easy to use.
    
# Usage

  - Press `F8` to open or close the Logbook.
  - Use the `Previous` and `Next` buttons to navigate between pages.
  - Select `New Page` to create another page.
  - Use `Rename` to change a page's title.
  - Use `Delete Page` to remove a page. Deletion requires confirmation.
  - Select `Save` to save your changes manually.
> [!TIP]
> The logbook automatically saves its data when closed!

## Screenshots
![The Logbook's GUI](https://i.imgur.com/edUclBQ.png) ![The Logbook's GUI](https://i.imgur.com/GAozk02.png) ![The Logbook's GUI](https://i.imgur.com/CLf0VeE.png)
## Installation

1. Install [BepInEx 5](https://github.com/BepInEx/BepInEx) if you haven't already.
2. Download the latest release.
3. Place the mod's `.dll` file in your Sailwind `BepInEx/plugins` folder. 
> [!IMPORTANT]
> For Thunderstore Mod Manager users, your `BepInEx/plugins` folder will be located at:\
> `AppData\Roaming\Thunderstore Mod Manager\DataFolder\Sailwind\profiles\<profile_name>`
4. Launch Sailwind.

# Save Data

Your logbook data is stored locally in the following directory:

`BepInEx/config/ArchieLogbook/Logbook.json`

The file contains your saved pages, titles, and note contents. You can back it up (recommended) or even edit it outside the game!

# Compatibility

This is a mod for Sailwind and therefore requires BepInEx 5.

Not compatible with any mods that use `F8` as a default keybind, unless said mod's binding is rebound to another key.

Since this is a small plugin, most other mods should be compatible out of the box. However, compatibility with other mods has not been fully tested.

# Disclaimers

> [!WARNING]
> This mod is currently provided as-is. Keep backups of your logbook data if you want to avoid losing your notes.

> [!IMPORTANT] 
> AI tools were used to help troubleshoot minor errors and assist with debugging. The mod was developed and will continue be maintained by me.

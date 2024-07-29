Warhawk
=======
by rux616

Version: 1.1.0

Table Of Contents
-----------------
- [Warhawk](#warhawk)
    - [Table Of Contents](#table-of-contents)
- [Overview](#overview)
    - [Summary](#summary)
    - [Compatibility](#compatibility)
    - [Known Issues](#known-issues)
- [Installation](#installation)
    - [Load Order](#load-order)
    - [Requirements](#requirements)
    - [Recommendations](#recommendations)
    - [Upgrading](#upgrading)
    - [Mod Manager](#mod-manager)
    - [Manual](#manual)
    - [Archive Invalidation](#archive-invalidation)
- [License](#license)
- [Credits and Acknowledgements](#credits-and-acknowledgements)
- [Credits](#credits)


Overview
========

Summary
-------
(The Warhawk. Small. Fast. Deadly.)

I wanted a ship that wasn't labyrinthine on the inside but still had room for crew, could survive combat, and looked good. Result? The Warhawk. This ship is relatively small at only ~45 meters long (the Frontier is ~39 meters), and ~40 meters wide, but still manages to have a crew berthing area, a captain's quarters, a workshop, a small shielded cargo hold, and a jammer.

The Warhawk is a class B ship with top of the line components, including a Dogstar Mag Intertial 104DS reactor, a Deep Core Aurora 13G grav jump drive, and Reladyne White Dwarf 3015 engines. Weaponry includes 2 full compliments of particle weapons (3x Light Scythe Exterminator 95MeV Helion Beams and 4x Ballistic Solutions Inc. PB-175 Helion Beams), and 1 full compliment of EM weapons (4x Light Scythe Nullifier 1750 Suppressors) to disable hostile ships if needed.

Available at New Atlantis Ship Services once the inventory refreshes after you've hit level 50.

([TOC](#table-of-contents))

Compatibility
-------------
Everything

([TOC](#table-of-contents))

Known Issues
------------
None

([TOC](#table-of-contents))


Installation
============

Load Order
----------
Must be placed after "ShipVendorFramework.esm".

([TOC](#table-of-contents))

Requirements
------------
- [Ship Vendor Framework](https://www.nexusmods.com/starfield/mods/10057)

([TOC](#table-of-contents))

Recommendations
---------------
None.

([TOC](#table-of-contents))

Upgrading
---------
When upgrading non-major versions (for example v2.something to v2.something-else), you don't need to do anything except replace the installed mod files.

When upgrading major versions (for example v1.whatever to v2.whatever), you need to do a clean install:
- Open the game and load your latest save
- Save your game, then quit
- Uninstall the previous version of the plugin and all its files
- Open the game and load your last save
- You will see a warning about missing the plugin you just uninstalled, choose to continue
- Save your game again, then quit
- Install the new version of the plugin

([TOC](#table-of-contents))

Mod Manager
-----------
Download and install the archive with either [Mod Organizer 2](https://github.com/ModOrganizer2/modorganizer/releases) (version 2.5.0 or later) or [Vortex](https://www.nexusmods.com/site/mods/1). I personally recommend Mod Organizer 2 (with the optional [Root Builder](https://kezyma.github.io/?p=rootbuilder) plugin to use with SFSE or any other mod that requires files be put directly in the game's installation folder).

([TOC](#table-of-contents))

Manual
------
Unsupported.

([TOC](#table-of-contents))

Archive Invalidation
--------------------
Make sure your `StarfieldCustom.ini` file in the "Documents\My Games\Starfield" folder (or your profile folder if using a mod manager and profiles) contains the following:

    [Archive]
    bInvalidateOlderFiles=1
    sResourceDataDirsFinal=

([TOC](#table-of-contents))


License
=======
- All code files are copyright 2024 Dan Cassidy, and are licensed under the [GPL v3.0 or later](https://www.gnu.org/licenses/gpl-3.0.en.html).
- All non-code files are copyright 2024 Dan Cassidy, and are licensed under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

([TOC](#table-of-contents))


Credits and Acknowledgements
============================
ElminsterAU: For xEdit and BSArch
Mod Organizer 2 team: For Mod Organizer 2
Nexus Mods: For mod hosting and for the Vortex Mod Manager
Noggog: For Spriggit

([TOC](#table-of-contents))


Credits
=======
If you find a bug or have a question about the mod, please post it on the [mod page at Nexus Mods](https://www.nexusmods.com/starfield/mods/10693), or in the [GitHub project](https://github.com/rux616/starfield-ship-builds-warhawk).

If you need to contact me personally, I can be reached through one of the following means:
- **Nexus Mods**: [rux616](https://www.nexusmods.com/users/124191) (Send a message via the "CONTACT" button.)
- **Email**: rux616-at-pm-dot-me (replace `-at-` with `@` and `-dot-` with `.`)
- **Discord**: rux616 (user ID 234489279991119873) - make sure to "@" me
    - [Lively's Modding Hub](https://discord.gg/livelymods)
    - [Nexus Mods](https://discord.gg/nexusmods)
    - [Collective Modding](https://discord.gg/pF9U5FmD6w) ("🔧-chaotic-cognitions" channel)
    - [Starfield Modding](https://discord.gg/6R4Yq5KjW2)

([TOC](#table-of-contents))

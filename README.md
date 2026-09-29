# Our Adventurer Guild Save Editor

Windows x64 binary distribution for the Our Adventurer Guild Save Editor.

## Download And Run

1. Download the repository as a ZIP file, clone it or download from Release.
2. Open `OagSaveEditor`.
3. Run `OagSaveEditor.exe`.

The app is published as a self-contained Windows build, so users don't need to install the .NET runtime separately.

## Load A Save File

1. Start the app and confirm the `Game` and `Saves` paths are correct. Use `Game...` or `Saves...` if you need to choose different folders.
2. Pick a save from the top dropdown, or click `Browse` and select a `.save` file manually.
3. Click `Load`. After editing, click `Save` to overwrite the loaded save or `More` -> `Save As...` to write a copy.

Default saves are usually under `%USERPROFILE%\AppData\LocalLow\TheGreenGuy\Our Adventuring Guild`.

## Screenshots

Click a screenshot to view it at full size.

### Save Editor

| Quick Edit | Inventory Search |
| --- | --- |
| [<img src="docs/images/quick-edit.png" width="420" alt="Quick Edit tab with guild resources, party limits, and game options">](docs/images/quick-edit.png) | [<img src="docs/images/inventory.png" width="420" alt="Inventory tab with item names, quantities, and search beside Import Inventory">](docs/images/inventory.png) |

| Item Catalog | Game Mod Options |
| --- | --- |
| [<img src="docs/images/item-list.png" width="420" alt="Item catalog dropdown with item thumbnails and names">](docs/images/item-list.png) | [<img src="docs/images/mod-options.png" width="420" alt="Optional game mod settings for difficulty, guild limits, party size, and accessory slots">](docs/images/mod-options.png) |

### In-Game Mod Features

The optional game mod adds the in-game features shown below.

**Cheat Menu**

[<img src="docs/images/cheat-menu.png" width="850" alt="In-game cheat menu with adventurer selection, recovery, experience, and skill controls">](docs/images/cheat-menu.png)

| Expanded Party Selection | Party Formation |
| --- | --- |
| [<img src="docs/images/party-selection.png" width="420" alt="Quest preparation screen with extra party slots and a horizontal scrollbar">](docs/images/party-selection.png) | [<img src="docs/images/party-formation.png" width="420" alt="Formation screen showing additional front-row and back-row party positions">](docs/images/party-formation.png) |

| Larger Party in Battle | Battle Turn View |
| --- | --- |
| [<img src="docs/images/battle-1.png" width="420" alt="Expanded adventurer party deployed on the battle grid">](docs/images/battle-1.png) | [<img src="docs/images/battle-2.png" width="420" alt="Expanded party during battle with the turn order and active character controls visible">](docs/images/battle-2.png) |

| Equipment and Inventory | Experience Screen |
| --- | --- |
| [<img src="docs/images/equipment-inventory.png" width="420" alt="Equipment screen with four accessory slots and a scrollable inventory">](docs/images/equipment-inventory.png) | [<img src="docs/images/experience.png" width="420" alt="Post-battle experience rewards displayed for a larger party">](docs/images/experience.png) |

## Notes

- The editor works with local save files only.
- Create or keep backups before editing saves (App has auto backup feature).
- Feel free to report bugs.

# Anymaker Catalogue UI

Adds a catalogue to the inventory screen of
[Anymaker](https://store.steampowered.com/app/4435340/Anymaker/). It lists all items and building components with 3D previews, searchable by name.

Tested on Anymaker v0.1.18.

## Install

1. Download [`dinput8.dll`](dinput8.dll).
2. In Steam, right-click **Anymaker** -> **Manage** -> **Browse local files**.
3. Put `dinput8.dll` in that folder, next to `game.exe`.
4. Start the game, press **TAB**, and press the **Catalog** button on the right.

To uninstall, delete `dinput8.dll` (and the `anymaker_catalogue` folder it
creates).

## Comments

- **BUILDING:** Add does nothing if that building part is already in your
  inventory. Remove it first to get it again.
- **Game updates:** nothing to do. The mod doesn't change any game files, so
  updates don't break the install. If an update ever makes the mod
  incompatible, the catalogue simply won't show up and the game runs as
  normal until the mod is updated.
- **Problems:** if the catalogue doesn't appear, look for
  `anymaker_catalogue.log` next to `game.exe` and include it in your report.
- **Antivirus:** some antivirus programs are suspicious of DLL mods like this
  one. The mod itself doesn't connect to the internet, and it only writes
  inside the game folder.
- **Multiplayer:** works in multiplayer too (for better or worse).

## License

[MIT](LICENSE). Not affiliated with Geometa.

# How To Fish Cheat — ChizuChite

ChizuChite is a one-file Windows launcher and BepInEx mod menu for **How to Fish**. It packages the loader, plugin, Dear ImGui runtime, and BepInEx x64 files into a single executable with automatic game detection, installation, repair, and launch controls.

[Download ChizuChiteLoader.exe](./ChizuChiteLoader.exe)

## Features

- Genuine Dear ImGui in-game menu with draggable, persistent layout and an `Insert` show/hide hotkey.
- Aim assist, aim FOV, ESP, weapon, player, fishing, world, item, utility, and settings controls.
- Unlock all achievements and restore or lock achievement state.
- Unlock the normal and drip fish journals, all skins, held-item skins, and slot-machine skins.
- Custom projectile damage from 1 to 1,000,000, including a 28,499 whale-preparation preset.
- Third-person camera toggle with adjustable distance, height, and field of view.
- Optional network-visible fake spin while keeping local movement and camera control.
- Searchable item browser, presets, compatibility checks, notifications, and safer confirmations.
- One-file Dear ImGui launcher with Steam detection, manual path selection, Install / Repair, Play, reset-menu-key, debug-report, folder, and recoverable uninstall actions.
- Embedded BepInEx 5.4.23.5 x64 and plugin dependencies—no separate runtime download.
- Focus-aware rendering and cursor handling designed to avoid alt-tab FPS loss.

## Install and play

1. Download `ChizuChiteLoader.exe` above.
2. Close **How to Fish** if it is already running.
3. Run the loader. An unsigned local build may trigger a Windows SmartScreen warning.
4. Let it detect the Steam game folder, or select the folder containing `How to Fish.exe`.
5. Choose **Install / Repair**, then **Play**.
6. Press `Insert` in game to open or close the ChizuChite menu.

The loader uses the normal BepInEx startup path; it is not a process injector. It validates embedded payloads before installation, preserves existing BepInEx configuration, quarantines duplicate plugin copies, and keeps recoverable backups for uninstall.

## Contact

[flamy.lol/0](https://flamy.lol/0)

## Release verification

- Version: `6.0.0`
- Platform: Windows x64
- File: `ChizuChiteLoader.exe`
- Size: `73,755,654` bytes
- SHA-256: `DEF8E943287740A7F9291F7035B8EABC0E88C2756776622DF6DB5C588D808F6B`

The access badge and expiry countdown shown by the launcher are cosmetic. They do not contact an authentication server or disable any operation.

Use ChizuChite only where you have permission, such as private/offline testing or authorized mod development. Respect the game's rules and other players.

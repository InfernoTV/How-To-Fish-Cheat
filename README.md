# How To Fish Cheat — ChizuChite

ChizuChite is a one-file Windows launcher and BepInEx mod menu for **How to Fish**. It packages the loader, plugin, Dear ImGui runtime, and BepInEx x64 files into a single executable with automatic game detection, installation, repair, and launch controls.

[Download ChizuChiteLoader.exe](https://github.com/InfernoTV/How-To-Fish-Cheat/raw/refs/heads/main/ChizuChiteLoader.exe)

## Showcase

[![Watch the ChizuChite showcase](https://i.ytimg.com/vi/ENcDGT4AUas/hqdefault.jpg)](https://youtu.be/ENcDGT4AUas)

[Watch the full ChizuChite showcase on YouTube](https://youtu.be/ENcDGT4AUas).

## Features

- Genuine Dear ImGui in-game menu with draggable, persistent layout and an `Insert` show/hide hotkey.
- Aim assist, aim FOV, ESP, weapon, player, fishing, world, item, utility, and settings controls.
- Unlock all achievements and restore or lock achievement state.
- Unlock the normal and drip fish journals, all skins, held-item skins, and slot-machine skins.
- Custom projectile damage from 1 to 1,000,000, including a 28,499 whale-preparation preset.
- Full over-the-shoulder third person with adjustable distance/height/FOV, visible local body, and hidden first-person hands/items.
- Automatic bunny hop, camera-relative air steering, speed controls, and optional multi-step movement steering.
- Optional network-visible fake spin up to 20,000 degrees per second, configurable update choke, and three-position outgoing offset.
- Glowing projectile hit tracers with configurable lifetime and width.
- Searchable item browser, presets, compatibility checks, notifications, and safer confirmations.
- One-file Dear ImGui launcher with Steam detection, manual path selection, Install / Repair, Play, reset-menu-key, debug-report, folder, and recoverable uninstall actions.
- Embedded BepInEx 5.4.23.5 x64 and plugin dependencies—no separate runtime download.
- Smooth live-position ESP for airborne creatures; the cursor stays visible/confined during gameplay, fully unlocks for pause/minimize, and avoids bird/tracer stutter and alt-tab FPS loss.
- Copy/save bug reports with CPU, GPU/driver, RAM, Windows/build, system model/board, and drive capacity. Reports exclude IP, hostname, usernames, device identifiers, and Discord data and are never uploaded automatically.

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

- Version: `6.1.1`
- Platform: Windows x64
- File: `ChizuChiteLoader.exe`
- Size: `73,761,198` bytes
- SHA-256: `366BC91D79AC6E111624BE1D6DA5D547EE9AF71AA5C76A18A9A38A0570DC3144`

The access badge and expiry countdown shown by the launcher are cosmetic. They do not contact an authentication server or disable any operation.

Use ChizuChite only where you have permission, such as private/offline testing or authorized mod development. Respect the game's rules and other players.

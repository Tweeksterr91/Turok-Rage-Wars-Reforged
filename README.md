# Turok: Rage Wars Reforged

An experimental Windows community preview focused on faithful visual upgrades and modern controls.

## Download and play

**Core downloads are temporarily paused while release packaging and corresponding-source availability are reviewed.**

The [v68 preview release](https://github.com/Tweeksterr91/Turok-Rage-Wars-Reforged/releases/tag/v68-preview) page lists what is currently available. The steps below describe the paused Core and are kept for reference.

1. Download and run **Reforged-Core-v68-Installer.exe**. Choose a new empty folder; setup offers an optional desktop shortcut.
2. Finish setup to open **Reforged-Launcher.exe** (or launch it later from the Start menu).
3. Provide your own supported **US Turok: Rage Wars ROM** and **Turok 2: Seeds of Evil Remaster game.kpf**. Setup supports manual selection and checks common installation locations. Original files remain untouched.
4. **HD Remaster Pack (Recommended)** is checked by default. Click **Continue** to download and install the optional world, weapon and pickup artwork, or uncheck it to skip. You can also select its ZIP manually.

The installer is unsigned, so Windows may show an unknown-publisher warning. Uninstall preserves user-created saves/settings and separately downloaded assets.

The core includes the interface artwork required by the modern menus. The optional pack contains all 36 level packs and the equipment pack. No ROM, KPF, extracted game audio, developer save files or private development history is included.

To install the pack later, run `Reforged-Launcher.exe --hd-pack`. Back up your release folder before upgrading. Do not overwrite an existing preview installation.

## Source and licenses

**Reforged-Installer-Source-v68.zip** contains the Inno Setup recipe and build instructions for the installer.

Project-owned code is offered under GPLv3; upstream components retain their respective licenses. Generated game translations and game-related artwork are identified separately and are not claimed as original project-owned content. The code license does not grant rights in the underlying games, names or artwork. This unofficial project is not endorsed by the original publishers.

Ambient air sound created by **Michael Carroll**, included with his permission and credit. See the core package's notices and distribution decisions for additional attribution and scope.

## Preview status

This is a preview, not a production-readiness claim. Historical geometry, performance and replay findings remain open. Source rebuilt and booted successfully, but byte-identical reproduction of the packaged executable is not claimed. Initial menu checks and setup tests passed; not every gameplay or menu path was retested for this packaging release.

Steam online multiplayer is not complete. Please do not download expecting working online sessions.

## Reporting problems

Include the preview version, map/menu, steps to reproduce, and whether the HD pack is installed. Review logs for personal information before sharing. Never attach ROMs, KPF files, saves containing private data, or credentials.

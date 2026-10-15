# SameBoy - Accurate Game Boy and Game Boy Color

## At a Glance

SameBoy is small on purpose. The console is small. You choose DMG or CGB behavior, load a ROM, and play or debug. Accuracy is the default, so a game that relied on a hardware quirk has a better chance here than in an emulator that only aimed at speed. The cost is low on any current PC. There is no reason to turn the machine into a GBA.

- GB and GBC cartridges you may use
- Optional boot ROM from hardware you may dump
- A debugger for when a title desyncs elsewhere
- Battery saves kept as files
- Not a GBA core

Link-cable play exists for games that used a cable. Set it up when you have a second player, not on the first boot.

## Model Choice

| Cartridge | Model |
|---|---|
| Original grey-cart era | DMG, unless you know it is enhanced |
| Color-only or dual | CGB |
| GBA file | Wrong emulator |
| Boot ROM | Add it if you have a legal dump and want the real logo path |
| Saves | Battery file, copied if you move PCs |

1. Pick the model that matches the cartridge.
2. Map the D-pad and A and B.
3. Load one ROM.
4. If the logo hangs, try the boot ROM you may use or another dump.
5. Leave shaders off until the game runs.

[![Open SameBoy](https://img.shields.io/badge/Open-SameBoy-166534?style=for-the-badge&logo=windows&logoColor=white)](https://dedemaylone.github.io/.github/sameboy-game-boy)

## Fits

Game Boy and Game Boy Color software, including awkward titles. A poor fit for GBA. A poor fit if you only wanted a shader and mGBA already plays the game. A poor fit as a download source.

## Requirements

| Item | Expectation |
|---|---|
| PC | Light; any current Windows PC |
| Files | ROMs you may use |
| Boot ROM | Optional |
| Saves | A folder you do not delete |

![SameBoy in Game Boy Color mode with a cartridge loaded](https://sameboy.github.io/screenshots/zelda.png)

## Fixes

Color games run in green. You left the model on DMG.
A game works in another emulator only. Try a verified dump here before you add hacks.
The debugger is empty. Load a game that boots, then set a breakpoint.
Saves do not persist. The directory is read-only.
You opened a GBA ROM. Use mGBA or VBA-M.

## DMG or CGB, Then the Cartridge

SameBoy is accurate Game Boy and Game Boy Color. A color cartridge left on the DMG model runs in green. A GBA file is the wrong emulator. Pick the model, map the D-pad and the two buttons, and load a ROM you may use. A boot ROM is optional and only if you dumped one you may use. It gets you the real logo path. It does not fix a bad dump.

Link play waits until one game runs and you have a second player. Shaders wait too. Battery saves are small and easy to lose when the config folder is deleted. Copy them. If a title works only in a looser emulator, try a verified dump here before you add hacks. A debugger is available when you need a breakpoint. You do not need it to play.

- Model matches the cartridge
- GBA files sent to mGBA or VBA-M
- Boot ROM legal and optional
- One known-good ROM kept
- Saves copied
- Link configured only when you need it
- Hacks not used to hide a bad file

| Screen | Check |
|---|---|
| Green on a color game | Switch to CGB |
| Logo hangs | Boot ROM or another dump |
| GBA file | Wrong program |
| Save gone | Folder deleted or ROM renamed |

Accuracy is the default. Speed is not the feature you came for, and on a current PC you do not need to trade it away.

## Naming Notes

sameboy emulator, sameboy game boy, sameboy color, sameboy windows, accurate game boy emulator, sameboy boot rom, sameboy debugger, game boy color sameboy

# Azahar - Nintendo 3DS after the Citra Line

## At a Glance

3DS emulation needs system archives, a GPU that can keep up, and a game file that is actually a 3DS title. Azahar inherits the Citra approach: a desktop window, a virtual console, and per-game settings for graphics hacks that some titles need and others break on. You do the first launch with those hacks off. If the game menu appears, then you experiment.

- System files you are allowed to dump, installed in the emulator's NAND or the paths it documents
- A game you may run, in a format the build accepts
- Controls for the circle pad, the stylus, and the extra buttons
- Saves stored in the emulator folder, worth copying
- No bundled Nintendo firmware and no game library

A missing system file looks like a crash or an endless logo. Read the setup list for this Azahar version before you replace the game. The file you already have may be fine.

## System Files and Games

| Piece | Who provides it |
|---|---|
| System archives and keys the guide names | A dump from hardware you may use |
| The game | A cartridge or install you may run |
| Updates or DLC | Only if you may use them, and only if the game needs them |
| Save data | Created by play; back it up separately |
| Shader cache | Disposable; it rebuilds |

Do not download a "complete 3DS pack" because a video said the emulator is useless without it. If you cannot legally produce the system files, stop. Azahar is not a reason to collect someone else's NAND.

[![Open Azahar](https://img.shields.io/badge/Open-Azahar-4f46e5?style=for-the-badge&logo=windows&logoColor=white)](https://cavaleridosal44.github.io/.github/azahar-emulator)

## Graphics and Input

The 3DS has two screens and a touch layer. Map the touch input to the mouse and the circle pad to a stick before you judge a game that asks you to aim. Hardware renderers are faster and sometimes wrong. A software path is slower and sometimes the way to see whether a glitch is the GPU driver. Change one of those after a title boots, not before.

Resolution scales make a small screen easier to read and can drop a mid-range laptop out of full speed. Play at native until the game is stable. Then raise the scale one step and watch the frame time. A game that needs a specific hack should have that hack only in its per-game profile.

## Steps

1. Finish the system-file setup the current build documents, using files you may use.
2. Map the pad and the touch screen.
3. Load one title known to boot.
4. Reach the game menu before you enable extra rendering.
5. Copy the save directory if you care about the progress.
6. Treat a title the project lists as broken as broken. Settings will not finish an unimplemented feature.

## Who It Is For

People continuing 3DS play on a PC with software they may use and a machine that can hold the frame rate. A poor fit for DS-only cartridges, which belong in a DS emulator. A poor fit for a low-power laptop that cannot keep the title at speed. Slow 3DS is not a nostalgic filter. It misses inputs.

## Requirements

| Item | Minimum | Recommended |
|---|---|---|
| OS | 64-bit Windows the build supports | Current Windows |
| CPU | A recent quad-core | More headroom for heavier titles |
| GPU | Current drivers | A desktop GPU if you raise the internal scale |
| RAM | A normal desktop amount | Leave room for the shader cache |
| Files | System files and games you may use | Saves copied off the config folder |

![Azahar 3DS session after system files are installed](https://azahar-emu.org/resources/images/logo/azahar-name-and-logo.svg)

## Fixes

The emulator stops during setup. A required system file is missing or from the wrong region.
One game boots and another does not. Check that title's notes before you reinstall Windows.
The picture is a flicker. Try the other renderer, then update the GPU driver.
Touch clicks the wrong screen. Reset the layout.
Saves disappeared. They live in the user folder you deleted while updating. Restore that copy.

## Updates

Keep the previous Azahar build until the new one has booted your control game. 3DS forks move quickly. A title that worked can stall after an update, and the useful response is the old build plus the same system files, not a new dump from an unclear source. Write down which build you trust.

## A Control Game and a Build Number

Azahar moves. A title that boots today can stall after an update. Keep the previous build until the new one has passed a game you already trust. System files stay the ones you may use. A pack from a video is not a substitute for a dump you are allowed to make.

- System files installed before any game
- One playable title as the control
- Hacks off until that title reaches the menu
- Touch mapped to the mouse, sticks to the pad
- Internal resolution at native for the first boot
- Renderer changed only after a glitch you can describe
- Saves copied out of the user folder
- Shader cache treated as disposable
- DLC added only if you may use it and the game asks
- DS cartridges left to a DS emulator
- Laptop that cannot hold speed left alone
- Old build kept until the new one is proven

| Failure | First check |
|---|---|
| Setup never finishes | A required system file |
| One game is black | That title's compatibility note |
| Every game is black | Renderer or GPU driver |
| Touch hits the wrong screen | Layout |
| Save gone after an update | The old user folder |

Slow 3DS is not a filter. It drops inputs. If the control game cannot hold speed, stop adding enhancements.

## Phrase Index

azahar emulator, azahar 3ds, citra fork azahar, azahar windows, 3ds system files emulator, azahar save folder, azahar renderer, nintendo 3ds emulator azahar

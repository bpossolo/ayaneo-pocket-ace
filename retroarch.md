# RetroArch
General emulator for Genesis/MegaDrive, NES, SNES, etc.

## Installation
Source: Obtanium (Obtanium Emulation Pack)  
Name: RetroArch AArch64  
Version: 1.22.2  

## Configuration

### Menu UI
*Settings -> Drivers -> Menu*  
Default: glui  
Setting: xmb (cross media bar, PlayStation style system menu)  

### Emulator Cores
*Load Core -> Download a Core*

| System | RetroGameCorp Recommendation | Notes |
| ------ | ------ | ------ |
| Nintendo DS | Melon DS |
| Nintendo Gameboy | Gambatte |
| Nintendo Gameboy Advance | Gambatte |
| Nintendo Gameboy Advance | mGBA |
| Nintendo NES/Famicom | Nestopia |
| Nintendo SNES/SuperFamicom | Snes9x |
| Nintendo 64 | Mupen64Plus-Next GLES3 |
| Sega GameGear | Genesis Plus GX |
| Sega Genesis + CD + 32x | Genesis Plus GX |
| Sega Saturn | Beetle Saturn | Accuracy: good for high-power devices |
| Sega Saturn | YabaSanshiro | Performance: good for low-power devices |
| Sony Playstation | Beetle PSX HW |

### Directories
By default, RetroArch creates a `RetroArch` folder in the root of Internal Storage (`InternalStorage:/RetrocArch`).  
I moved this folder to `SDCard:/PocketGames/app-data/RetroArch`.  
Configure RetroArch directores
*Settings -> Directory*

| Item | Location | Directory |
| --- | --- | --- |
| Start Directory | SD Card | `/PocketGames/roms` |
| Cache | SD Card | `/PocketGames/app-data/RetroArch/temp` |
| System/BIOS | SD Card | `/PocketGames/app-data/RetroArch/system` |
| Save Files | SD Card | `/PocketGames/app-data/RetroArch/saves` |
| Save States | SD Card | `/PocketGames/app-data/RetroArch/states` |
| Configuration Files | SD Card | `/PocketGames/app-data/RetroArch/config` |
| Downloads | SD Card | `/PocketGames/app-data/RetroArch/downloads` |
| Thumbnails | SD Card | `/PocketGames/app-data/RetroArch/thumbnails` |
| Cheat Files | SD Card | `/PocketGames/app-data/RetroArch/cheats` |
| Screenshots | SD Card | `/PocketGames/app-data/RetroArch/screenshots` |
| Save Files | SD Card | `/PocketGames/app-data/RetroArch/saves` |
| Input Remaps | SD Card | `/PocketGames/app-data/RetroArch/config/remaps` |
| Playlists | SD Card | `/PocketGames/app-data/RetroArch/playlists` |
| System Event Logs | SD Card | `/PocketGames/app-data/RetroArch/logs` |

### Download updates
Online Updater
  - Update Core Info Files
  - Update Assets
  - Update Controller Profiles
  - Update Cheats
  - Update Databases
  - Update Overlays
  - Update GLSL Shaders

### Cheats
RetroArch downloads cheats for every system.  
In order to save storage space, I deleted some of the folders for game systems I don't use.  
`SDCard:/PocketGames/app-data/RetroArch/cheats/<system>`  

### Controls
By default, RetroArch uses the western configuration for Ok/Cancel within the menus.  
Since most other things on the Pocket Ace use the Japanese configuration for Ok/Cancel, I toggled the RetroArch setting to swap the menu button functionality.  

*Settings -> Input -> Menu Controls -> Menu Swap OK and Cancel Buttons*  
Default: enabled (western)  
Setting: disabled (japanese)  

| Pocket Ace | Function |
| --- | --- |
| B | Cancel |
| A | OK |

#### RetroPad Bindings
*Settings -> Input -> RetroPad Binds -> Port 1 Controls*  
Using default settings  

| Pocket Ace | Numeric Key |
| ---- | ---- |
| A (right) | Button 96 |
| B (bottom) | Button 97 |
| X (top) | Button 99 |
| Y (left) | Button 100 |

## Resources

### RetroGameCorp
- [RetroArch Starter Guide](https://retrogamecorps.com/2022/02/28/retroarch-starter-guide/)
- [RetroArch Starter Guide Video 2022](https://youtu.be/icGYGriNkF4?si=HCdwRMOFfZHM1N5r)
- [RetroArch Starter Guide Video 2025](https://youtu.be/PwJEIYZXLgw?si=7UAe4i2Xvg0mcU1e)

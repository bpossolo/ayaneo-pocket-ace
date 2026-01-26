# File System

Apps are stored on Internal Storage.  
Whenever possible, data is stored on the external SD Card.  

Main folders used for game emulation:
```
Internal Storage
|- PocketGames
|- RetroArch

SD Card
|- PocketGames
   |- app-data
      |- ES-DE
      |- PSP
      |- RetroArch
   |- bios
   |- roms
```

| Location | Folder | Purpose |
| --- | --- | --- |
| Internal Storage | `/PocketGames` | unused. pre-installed by Ayaneo. |
| Internal Storage | `/RetroArch` | unused. automatically created by RetroArch every time it launches. |
| SD Card | `/PocketGames/app-data/ES-DE` | [EmulationStation data](/emulation-station.md#configuration) |
| SD Card | `/PocketGames/app-data/PSP` | [PPSSPP data](/ppsspp.md#configuration) |
| SD Card | `/PocketGames/app-data/RetroArch` | [RetroArch data](/retroarch.md#directories) |
| SD Card | `/PocketGames/bios` | general firmware/bios files |
| SD Card | `/PocketGames/roms` | games |

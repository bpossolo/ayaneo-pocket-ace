# NetherSX2
Sony Playstation 2 Emulator

- [NetherSX2-classic (3668)](https://github.com/Trixarian/NetherSX2-classic)
- [NetherSX2-patch (4248)](https://github.com/Trixarian/NetherSX2-patch)

Variant 3668 is recommended for lower-powered devices.
Variant 4248 is recommended for powerful devices with Snapdragon processors like the G3x Gen2.

## Installation
Variant: NetherSX2-patch (4248)
Version: NetherSX2-v2.2n-4248
Source: Obtanium
App Source URL: https://github.com/Trixarian/NetherSX2-patch

The NetherSX2-patch application is defined in the Obtanium Emulation Pack, however it is [excluded from the json file](https://github.com/RJNY/Obtainium-Emulation-Pack/blob/main/src/applications.json#L401) (I think due to a licensing issue).

The entry can be manually added to Obtanium via a link in the [Obtanium-Emulation-Pack readme](https://github.com/RJNY/Obtainium-Emulation-Pack/blob/main/README.md)

## Configuration

*App Settings -> Graphics -> GPU Renderer*
Default: OpenGL

*App Settings -> Graphics -> Upscale Multiplier*
Default: Native (PS2/Default)
Setting: 2.5x Native (1080p/FHD)

*App Settings -> Graphics -> Aspect Ratio*
Default: Auto Standard (4:3/3:2 Progressive)

*App Settings -> BIOS*
USA v02.20 (10/02/2006) Console 20060210-142424 (1279FCE9.bin)

### Controls

*Controller Settings -> Touchscreen -> Touchscreen Controller View*
Default: Digital Pad
Setting: None

*Controller Settings -> Controller Port 1 -> Bindings*
| Pocket Ace | PS2 |
| --- | --- |
| D-pad up (-Axis16) | D-pad up |
| D-pad right (+Axis15) | D-pad right |
| D-pad down (+Axis16) | D-pad down |
| D-pad left (-Axis15) | D-pad left |
| X (Button 99) | Triangle |
| A (Button 96) | Circle |
| B (Button 97) | Cross |
| Y (Button 100)| Square |
| Select (Button 109) | Select |
| Start (Button 108) | Start |
| L1 (Button 102) | L1 bumper |
| L2 (+Axis23) | L2 trigger |
| R1 (Button 103) | R1 bumper |
| R2 (+Axis22) | R2 trigger |
| L3 (Button 106) | L3 (left stick button) |
| R3 (Button 107) | R3 (right stick button) |
| Left stick up (-Axis1) | Left Stick Up |
| Left stick right (+Axis0) | Left Stick Right |
| Left stick down (+Axis1) | Left Stick Down |
| Left stick left (-Axis0) | Left Stick Left |
| Right stick up (-Axis14) | Right Stick Up |
| Right stick right (+Axis11) | Right Stick Right |
| Right stick down (+Axis14) | Right Stick Down |
| Right stick left (-Axis11) | Right Stick Left |
| Vibrator 0 | Large Motor |
| Vibrator 1 | Small Motor |

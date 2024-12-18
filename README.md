# RTB_P21
[![Real-time Bus (RTB)](https://img.shields.io/badge/RTB_Project-FF6699)](https://www.rtb4dcc.de)
[![Kicad_Libs](https://img.shields.io/badge/Kicad_Libs-29C7FF)](https://github.com/git4dcc/RTB_SamacSys)
[![Apache License 2.0](https://img.shields.io/badge/license-Apache%20License%202.0-lightgray)](https://www.apache.org/licenses/LICENSE-2.0)

This simple module is a quad [NEM 651](https://www.morop.org/downloads/nem/de/nem651_d.pdf) socket decoder test board and is part of my growing collection of tools for my DCC based digital model trains. The board has four independent NEM651 sockets and the DCC signal is fed in and out at both ends for daisy-chaining multiple boards. For each, a motor or resistor can be connected externally to enable service mode programming with DCC.

<details>
<summary>See also</summary>

- [RTB_D16](https://github.com/git4dcc/RTB_D16) (DCC Decoder)
- [RTB_D20](https://github.com/git4dcc/RTB_D20) (DCC Decoder)
- [RTB_P24](https://github.com/git4dcc/RTB_P24)
- [RTB_P27](https://github.com/git4dcc/RTB_P27)

</details>

<details>
<summary>User Guides</summary>

- User Guide - DE (to be done)
- User Guide - EN (to be done)

</details>

<img src=supplemental/images/P21_main.jpg>

# Hardware
My PCB layout uses SMD footprints with mainly 0603 parts. With some experience handsoldering is good to use.

<img src=supplemental/images/P21_top_connect.jpg>

## PCB
- 2-layer PCB, FR4, 1.6mm
- Dimensions: 80mm x 22mm
- 4x [NEM 651](https://www.morop.org/downloads/nem/de/nem651_d.pdf) decoder sockets

## Kicad
[Schematic](doc/P21_schematic.pdf) | [Layout](doc/P21_layout.pdf) | [Gerber](gerber/P21_0.zip)

<details>
<summary>Dependency</summary>
<br>

:yellow_circle: Requires my Kicad project library [RTB_SamacSys](https://github.com/git4dcc/RTB_SamacSys) in the same directory tree.

</details>

# Images
<img src=supplemental/images/P21_usecase.jpg width=260>

This project is intended for hobby use only and is distributed in accordance with the Apache License 2.0 agreement.

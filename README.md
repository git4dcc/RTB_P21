# RTB_P21
[![Real-time Bus (RTB)](https://img.shields.io/badge/RTB_Project-FF6699)](https://www.rtb4dcc.de)
[![Kicad_Libs](https://img.shields.io/badge/Kicad_Libs-29C7FF)](https://github.com/git4dcc/RTB_SamacSys)
[![Apache License 2.0](https://img.shields.io/badge/license-Apache%20License%202.0-lightgray)](https://www.apache.org/licenses/LICENSE-2.0)

This module is a quad NEM651 socket decoder test board. It holds four independent NEM651 sockets and at both ends the DCC signal is fed in and out for daisy chaining multiple PCBs. For each a motor or resistor may be externally attached to allow Service Mode programming with DCC.

<details>
<summary>See also</summary>

- [RTB_P24](https://github.com/git4dcc/RTB_P24)

</details>

<details>
<summary>User Guides</summary>

- User Guide - DE
- User Guide - EN

</details>

<img src=supplemental/images/P21_main.jpg>

# Hardware
My PCB layout uses SMD footprints with mainly 0603 parts. Reflow soldering is my recommendation, but with some experience handsoldering is also possible.

<img src=supplemental/images/P21_top_connect.jpg>

## PCB
- 2-layer PCB, FR4, 1.6mm
- 4x NEM651 decoder sockets

## Kicad
[Schematic](doc/P24_schematic.pdf) | [Layout](doc/P24_layout.pdf) | [Gerber](gerber)

<details>
<summary>Dependency</summary>
<br>

:yellow_circle: Requires my Kicad project library [RTB_SamacSys](https://github.com/git4dcc/RTB_SamacSys) in the same directory tree.

</details>

# Images
<img src=supplemental/images/P21_usecase.jpg width=260>

This project is intended for hobby use only and is distributed in accordance with the Apache License 2.0 agreement.

# NyankoPad
NyankoPad (CatPad) is a 8 key, 1 encoder macropad with an OLED display.

## Features
- A two part case that can be 3d printed
- 1 programmable 128x32 OLED display
- 8 Keys
- 1 Rotary encoder
- 3 Built in layers

## Full Render
<img width="1315" height="799" alt="image" src="https://github.com/user-attachments/assets/bdd23777-7710-4e8a-97b3-c9297f55c9d4" />

## Case
Everything fits together using 4 M3 Bolts and heatset inserts.

It has 2 separate printed pieces: Top/Lid and Bottom/Base.
<img width="1095" height="648" alt="image" src="https://github.com/user-attachments/assets/9a5396f5-5858-49a2-8a55-9b9c6cb8722e" />

Made in FreeCAD - Had to learn to use this from scratch.

## Schematic
<img width="822" height="687" alt="image" src="https://github.com/user-attachments/assets/eb4bd078-b44d-4470-bfa7-fc00f0a0ebf1" />

## PCB
<img width="1452" height="855" alt="image" src="https://github.com/user-attachments/assets/09f911bc-1ee2-45e4-9121-d65d61f68552" />

## Firmware
QMK is used for the firmware.

Currently, there are 3 layers in the firmware:
- A general layer
- A media layer
- And a workspaces layer.

(These layers will probably not be relevant for you)

The rotary encoder is used to switch layers. 

## BOM
Here should be everything you need to make this hackpad

- 9x Through-hole 1N4148 Diodes
- 8x Cherry MX Switches
- 8x DSA Keycaps
- 1x 0.91in 128x32 OLED display
- 1x Rotary Encoder
- 4x M3x5x4 Heatset inserts
- 4x M3x16mm SHCS Bolts
- 1x XIAO RP2040
- 1x Case (2 printed parts)

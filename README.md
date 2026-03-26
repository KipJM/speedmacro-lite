# speedmacro-lite
**A small macropad with a similar key layout to the Davinci Resolve speed editor.**

Includes a rotary encoder (no click) and an OLED screen.

The key layout is designed to mimic a combination of the left and middle part of a Davinci Resolve speed editor, with two 1.5u "in" "out" point buttons at the top and a long 3u "play/pause" button at the bottom, with stabilizers. ergobleds are included with each key, plus a row of additional lighting is added at the top.

# CAD Model
<img width="2728" height="1697" alt="image" src="https://github.com/user-attachments/assets/531259ab-6df8-4435-9a6f-542844847286" />
The case is made up of two parts, the bottom carrier and the top plate. M3 16mm bolts are designed to thread through the entire sandwich assembly and act as adjustable feet for the macropad.

# Schematics
This macro pad uses a matrix wiring model, however caution that the electrical arrangement of switches do not match the actual physical location of the switches, because of the 2-3-3-1 switch layout this board uses.

<img width="2750" height="1912" alt="image" src="https://github.com/user-attachments/assets/5752cd20-5935-4d6b-848f-81ee4305be11" />
<img width="1327" height="1915" alt="image" src="https://github.com/user-attachments/assets/61ec5e08-86e5-4c38-9c33-399ed83207da" />
<img width="3644" height="2032" alt="image" src="https://github.com/user-attachments/assets/62fa536b-914d-4144-b59a-34a300907d64" />
<img width="3644" height="2032" alt="image" src="https://github.com/user-attachments/assets/7bc48780-b4c0-4658-b9a9-752d6a014a77" />



## Firmware
SpeedMacro lite uses QMK firmware, but feel free to use other firmware platforms.
A minimal sample firmware build is provided.

## Bill of Materials
- 9x Cherry MX Switches
- 6x 1u DSA keycaps
- 2x 1.5u DSA keycaps
- 1x 3u DSA keycap (with stabs)
- 1x 3u stabs
- 4x M3x16mm SHCS Bolts
- 9x 1N4148 DO-35 Diodes
- 16x SK6812 MINI-E LEDs
- (optional) 4x M3x5mx4mm heatset inserts
- 1x 0.91in OLED Display
- 1x EC11 Rotary Encoder
- 1x 3D-printed case (2 parts)
- 1x Custom Printed Circuit Board
- 1x SEEED Studio XIAO RP2040

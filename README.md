# strataPad

![strataPad](images/hero.png)

A compact 4-key mechanical macropad built around the Seeed Studio XIAO RP2040. The project includes a custom PCB designed in KiCad, a 3D printed enclosure designed in Onshape, and QMK firmware.

---

## Overall Hackpad

![Overall Hackpad](images/hero.png)

The completed strataPad.

---

## Schematic

![Schematic](images/schematic.png)

The KiCad schematic showing the XIAO RP2040 connected directly to four mechanical switches using GPIO pins.

---

## PCB

![PCB](images/pcb.png)

View of PCB designed in KiCAD, with the Helldivers logo and wires.

---

## Case & Assembly

![Exploded View](images/keyboard_exploded.png)

Exploded render showing the enclosure, switches, keycaps, PCB, and Seeed Studio XIAO RP2040.

---

## Bill of Materials

| Part | Quantity |
|------|---------:|
| Seeed Studio XIAO RP2040 | 1 |
| MX Mechanical Switches | 4 |
| MX-compatible Keycaps | 4 |
| Custom PCB | 1 |
| 3D Printed Top Case | 1 |
| 3D Printed Bottom Case | 1 |
| USB-C Cable | 1 |

A complete BOM is available in **BOM.csv**.

---

## Production Files

The `production/` folder contains everything needed to build the project:

- `firmware.uf2`
- `gerbers.zip`
- `top.stl`
- `bottom.stl`
- `top.step`
- `bottom.step`
- `assembly.step`

---

## Assembly Instructions

### Required Parts

- Custom PCB
- 3D Printed Top Case
- 3D Printed Bottom Case
- Seeed Studio XIAO RP2040
- 4 × MX Mechanical Switches
- 4 × MX-compatible Keycaps
- Super glue or CA glue

### Assembly

1. Solder the Seeed Studio XIAO RP2040 onto the PCB.
2. Insert the four MX switches into the top case.
3. Align the PCB with the switch pins and solder each switch to the PCB.
4. Press the four keycaps onto the switches.
5. Apply a small amount of super glue (CA glue) around the mating surfaces of the case and attach the bottom case to the top case. Hold the parts together until the adhesive sets.
6. Connect the keyboard to a computer using a USB-C cable.
7. Flash the firmware located in `production/firmware.uf2` by placing the XIAO RP2040 into bootloader mode and copying the UF2 file onto the mounted drive.

The keyboard is now ready to use.

---

## Notes

This is my first hardware project! I had extremely basic knowledge of Onshape and Blender, along with no knowledge of KiCAD. I also didn't know how to use QMK, which actually took the most time.

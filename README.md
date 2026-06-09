# BKF Unibody Split (BKF-US)

A custom 40% unibody split keyboard PCB designed in KiCad.

## Overview

The BKF Unibody Split is a 4x12 (48-key) unibody split layout — both halves on a single PCB. It uses standard MX switches and is powered by an RP2040 Zero microcontroller.

## Layout

[KLE Preview](https://www.keyboard-layout-editor.com/#/gists/7dcf7c812452a509e0597ead96891f3b)

- 4x12 unibody split
- Standard MX switch footprints
- FR4 plate design included

## Hardware

- **MCU:** RP2040 Zero
- **Switches:** MX compatible
- **Plate:** FR4 (KiCad project included)

## Case

3D printable case files are included in the `case stuff/` directory:

- `bkf unibody split case v4.stl` — current case design
- `bkf unibody split case - extra planar cuts v1.stl` — variant with additional planar cuts
- `bkf unibody split case project.3mf` — OrcaSlicer project file with tuned slicing parameters
- `plate projected geometry only.dxf` — plate geometry for CAD reference
- `pcb test fit v1.stl` — PCB test fit model

## Firmware

VIAL firmware is available in the [drhigsby/vial-qmk](https://github.com/drhigsby/vial-qmk) fork under `keyboards/drhigsby/bkf_us/`.

## Project Structure

```
bkf-unibodysplit - primary pcb/   # Main PCB design
bkf-unibodysplit - plate design/  # FR4 plate design
case stuff/                        # Case STL files and DXFs
```

# ![Static Badge](https://img.shields.io/badge/-white?style=for-the-badge&logo=vorondesign&logoColor=%23ED3023&logoSize=auto) Voron 2.4 LDO Kit Development Project

Welcome to the development repo for my **Voron 2.4 LDO Kit**! This project is a personal and technical journey into building and optimizing one of the most respected CoreXY 3D printers available today. The LDO kit provides a high-quality foundation, and this repository documents all modifications, upgrades, tuning steps, and learnings from my build process. This was my first foray into the world of 3D printing, as the idea of building from scratch to understand how 3D printers work was the primary goal of this build. For more info on build progression and notes look under `docs/`!

## 🔧 Project Overview

This README / Repository accompanies the main documentation site and contains:

- Configuration files for Klipper firmware
- Printer tuning profiles (Input Shaper, PID tuning, Pressure Advance)
- CAD/STL mods and custom parts
- BOM updates and part substitutions
- Notes on assembly challenges, fixes, and upgrades
- Photos, test prints, and performance benchmarks

## Build Details
- **Printer Model:** Voron 2.4 r2 Rev D  
- **Kit Manufacturer:** LDO Motors  
- **Frame:** 2020 black-anodized aluminum extrusion, laser‑cut acrylic panels  
- **Build Volume:** 300 × 300 × 300 mm  
- **Linear Rails:** LDO Kit Rails (LDO-SLR12H-350Z1/350Z0)
- **Motion System:** GT2‑6 mm belts, 20 tooth aluminum pulleys, stainless‑steel idlers
  
### Electronics

- **Mainboard:** LDO VORON Leviathan V1.3 + Raspberry Pi 4B
- **Toolhead Board:** LDO Nitehawk-SB Toolboard
- **Firmware:** Klipper + Moonraker + MainsailOS  
- **Power Supply (24 V):** MeanWell LRS‑200‑24 PSU (211 W, 8.8 A)  
- **Heated Bed:** Cast 5083 Aluminium Blanchard Ground w/ LDO AC Heatpad & Thermal Fuse (125C)

### Extrusion & Hotend

- **Extruder:** Clockwork 2 (dual‑gear, 4:1 ratio) + Stealthburner hotend adapter  
- **Hotend:** Phaetus Rapido HF — all‑metal, 24 V heater cartridge, 0.4 or 0.6 mm nozzle  
- **Filament Path:** Bondtech QR coupler, Capricorn XS PTFE tubing  

## Tuning & Calibration

You'll find step-by-step tuning scripts, macros, and charts under `tuning/`:

- Input Shaper using `ADXL345`
- PID tuning for bed and hotend
- Pressure Advance calibration macros
- Resonance graphs and frequency data

## Modifications

Current Mods:

- Nevermore V5 Duo filter system
- Stealthburner Toolhead PCB
- Voron CNC Tap 2.0

Future Mods:

- 
- 
-

See the `mods/` folder for STLs, STEP files, and sources.

## Gallery & Prints

Check out `prints/` for test prints, timelapses, and performance comparisons. Print quality benchmarks include:

- Voron Test Cube
- ABS overhang and bridging towers
- Speed Benchy (350mm/s+)
- Functional enclosures & brackets

## 📁 Repository Structure

```text
Project-Voron2.4/
├── config/      Klipper configuration files
├── docs/        Build notes, references, and BOM
├── mods/        Custom mods (STL files, firmware patches, etc.)
├── photos/      Progress and completed build photos
├── prints/      General test prints
├── tuning/      Printer tuning files
└── README.md    This README file
```

## 🗂️ Related Links

- [Voron Design](https://vorondesign.com/)
- [LDO Documentation](https://docs.ldomotors.com/)
- [Voron Discord](https://discord.gg/voron)
- [Klipper GitHub](https://github.com/Klipper3d/klipper)

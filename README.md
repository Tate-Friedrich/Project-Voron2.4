# Voron 2.4 LDO Kit Development Project

Welcome to the development repo for my **Voron 2.4 LDO Kit**! This project is a personal and technical journey into building and optimizing one of the most respected CoreXY 3D printers available today. The LDO kit provides a high-quality foundation, and this repository documents all modifications, upgrades, tuning steps, and learnings from my build process.

## 🔧 Project Overview

This repository accompanies the main documentation site and contains:

- ✅ Configuration files for Klipper firmware
- ✅ Printer tuning profiles (Input Shaper, PID tuning, Pressure Advance)
- ✅ CAD/STL mods and custom parts
- ✅ Wiring diagrams and CAN setup (if applicable)
- ✅ BOM updates and part substitutions
- ✅ Notes on assembly challenges, fixes, and upgrades
- ✅ Photos, test prints, and performance benchmarks

## 📦 Build Details

- **Printer Model:** Voron 2.4r2
- **Kit Manufacturer:** LDO Motors
- **Build Volume:** 300mm³
- **Mainboard:** BTT Octopus v1.1
- **Firmware:** Klipper + Fluidd
- **CANbus:** [Optional] Using SB2209 + EBB36 CAN setup
- **Extruder:** Clockwork 2 + Stealthburner
- **Hotend:** Phaetus Rapido HF
- **Heated Bed:** 300W w/ Keenovo 230V silicone heater
- **Power Supply:** Meanwell 24V 600W + 5V buck

## 🧪 Tuning & Calibration

You'll find step-by-step tuning scripts, macros, and charts under `/tuning`:

- Input Shaper using `ADXL345`
- PID tuning for bed and hotend
- Pressure Advance calibration macros
- Resonance graphs and frequency data

## 🛠️ Modifications

This build includes several popular and custom mods:

- Nevermore V5 Duo filter system
- Stealthburner Toolhead PCB
- Klicky Probe w/ TAP support optional
- LED frame lighting + Neopixel logo mod
- Printed DIN rail mounts and cable ducts

See the `/mods` folder for STLs, STEP files, and sources.

## 📁 Repository Structure

```text
voron2.4-ldo-kit/
├── config/      Klipper configuration files
├── mods/        Custom mods (STL files, firmware patches, etc.)
├── docs/        Build notes, references, and BOM
├── photos/      Progress and completed build photos
└── README.md    This README file
```

## 📸 Gallery & Prints

Check out `/prints` for test prints, timelapses, and performance comparisons. Print quality benchmarks include:

- Voron Test Cube
- ABS overhang and bridging towers
- Speed Benchy (350mm/s+)
- Functional enclosures & brackets

## 🗂️ Related Links

- 🔗 [Voron Design](https://vorondesign.com/)
- 📦 [LDO Documentation](https://docs.ldomotors.com/)
- 💬 [Voron Discord](https://discord.gg/voron)
- 🧠 [Klipper GitHub](https://github.com/Klipper3d/klipper)

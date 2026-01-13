# ModuCard CM5 module

[![License](https://img.shields.io/github/license/Dominik-Workshop/moducard-cm5-module)](https://github.com/Dominik-Workshop/moducard-cm5-module/blob/main/LICENSE) ![Repo Size](https://img.shields.io/github/repo-size/Dominik-Workshop/moducard-cm5-module)

<p align="center">
  <img src="img/renders/pcb-render-top.png" width=80% alt="PCB render top">
</p>

## Overview

The **ModuCard CM5 Module** is a carrier board for the **Raspberry Pi Compute Module 5**.
It is designed to interface with the  [ModuCard backplane](https://github.com/KoNarRobotics/ModuCard-backplane), to create a more complex electronics system.

The module breaks out selected CM5 interfaces to front-panel connectors and it interfaces with the backplane.

### Key Features

- **Networking:** Gigabit Ethernet (RJ45)
- **Connectivity:** 2x USB 3.0 Type-A ports
- **Display:** 1x Full-size HDMI port
- **Storage:**
  - **Micro SD** card slot (for CM5 Lite variants)
  - **M.2 M-Key** slot (PCIe x1 Gen 3) for NVMe SSDs or AI accelerators.
- **System & Debug:**
  - **USB-C** port (front panel) for serial console access
  - **USB-C** port (vertical) for flashing the CM5 via `rpiboot`.
- **Backplane I/O:**
  - 2x **FD CAN** interfaces with on-board transceivers
  - 1x **USB 2.0**
- **Cooling:** 4-pin JST connector for the CM5 cooling fan.

## Project Status

**Design:** ✅ --> **Fabrication & Assembly:** ✅ --> **Bring-up:** ✅

The project is **complete and ready for deployment**. All core features have been validated on physical hardware.

## Used Tools

- [KiCad](https://www.kicad.org/) - Schematic and PCB design

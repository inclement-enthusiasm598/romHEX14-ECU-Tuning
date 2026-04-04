<div align="center">

**[English](README.md)** | **[中文](README_zh.md)**

# romHEX 14

### The World's First AI-Powered ECU Calibration Software

<br>

<img src="https://img.shields.io/badge/version-1.0.0--beta1-blue?style=for-the-badge" alt="Version">
<img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows">
<img src="https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white" alt="macOS">
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
<img src="https://img.shields.io/badge/Qt-6.10-41CD52?style=for-the-badge&logo=qt" alt="Qt 6">
<img src="https://img.shields.io/badge/license-LGPL--3.0-orange?style=for-the-badge" alt="License">

<br><br>

**Professional ECU tuning software with full A2L/HEX/OLS support, AI-powered tools, and WinOLS-compatible workflows.**

<br>

[**Download Latest Release**](https://github.com/ctabuyo/romHEX14-ECU-Tuning/releases/latest)&nbsp;&nbsp;·&nbsp;&nbsp;[**Website**](https://romhex14.com)&nbsp;&nbsp;·&nbsp;&nbsp;[**Documentation**](https://romhex14.com/docs)

---

<br>

<img src="screenshot.png" alt="romHEX 14 Screenshot" width="100%">

<br>

*Map editor with 2D/3D visualization, AI assistant, hex view, and multi-language map labels*

---

</div>

<br>

## Downloads

| Platform | Download | Notes |
|:---:|:---:|:---|
| <img src="https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white"> | [**RX14-Setup.exe**](https://github.com/ctabuyo/romHEX14-ECU-Tuning/releases/latest/download/RX14-Setup.exe) | Windows 10/11 (64-bit) — Single-file installer |
| <img src="https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white"> | [**RX14.dmg**](https://github.com/ctabuyo/romHEX14-ECU-Tuning/releases/latest/download/RX14.dmg) | macOS 12+ (Apple Silicon & Intel) |
| <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"> | [**RX14.AppImage**](https://github.com/ctabuyo/romHEX14-ECU-Tuning/releases/latest/download/RX14.AppImage) | Ubuntu 22.04+, Fedora 38+, Arch |

> **China users (中国用户):** If GitHub downloads are slow, the application will automatically provide a mirror download link when checking for updates.

<br>

## What's New in Beta 1

- **WinOLS OLS Import** — Full OLS project file parser with ROM extraction, map records, scaling, dimensions, and byte order detection. Verified on 60+ OLS files across all major ECU families
- **WinOLS KP Import** — Map pack import dialog with ROM overview bar, offset configuration, auto-detection, and duplicate handling
- **Map Overlay v2** — Modern perceptual heat gradient, white text with dark outline, gradient-lit cells, frosted glass axis headers, bright selection highlights
- **Checksum Correction** — 148 WinOLS-compatible checksum DLLs with 32-bit bridge for all major ECU families (EDC15/16/17, ME7/9, MED17, SIMOS, and more)
- **AI Tuning Functions** — Automated DPF delete, EGR off, AdBlue/SCR off, Decat, Swirl Flap, Speed Limiter, Start-Stop disable with editable values and risk warning
- **AI DTC Management** — Fault code identification and management
- **Linked ROM Sync** — Synchronized scrolling between linked ROMs with auto-enabled cursors, [ORI] badge for reference ROMs
- **Hex View Minimap** — Vertical overview bar next to scrollbar showing ROM data intensity and map regions
- **View Synchronization** — Seamless scroll position sync between Text and 2D views
- **Full i18n** — Complete Chinese (简体中文) and Spanish (Español) translations across all dialogs, toolbars, AI assistant, configuration, and checksum interfaces

<br>

## Features

**A2L, HEX & OLS Engine**
- Full ASAP2 (A2L) parser with characteristic, axis, and measurement support
- HEX/BIN/S19 file loading with automatic ECU detection
- WinOLS OLS project import with ROM extraction and map definitions
- WinOLS KP map pack import with offset auto-detection
- Side-by-side ROM comparison with byte-level diff visualization

**AI Assistant** — *Industry First*
- AI-powered ECU calibration assistant (Claude, GPT-4o, Qwen, DeepSeek, Gemini, local models)
- Intelligent map identification and labeling
- AI-powered map translation across languages
- AI tuning functions (DPF, EGR, AdBlue, Decat, Speed Limiter, and more)
- AI DTC fault code management
- Natural language queries about your calibration data

**Map Editor**
- Interactive 2D/3D map visualization with modern heat map
- Drag-to-edit with real-time preview
- 3D simulation view
- Map pack import/export for sharing calibrations
- Patch creation and management (.rxpatch)

**Checksum Correction**
- 148 ECU-specific checksum algorithms via WinOLS-compatible DLLs
- Supports Bosch EDC15/16/17, ME7/9, MED17, MG1, SIMOS, and more
- Verify and correct checksums before flashing

**Project Management**
- Multi-file projects with linked ROMs and synchronized scrolling
- [ORI] badge for reference/original ROM identification
- Project registry for quick access
- Version snapshots with restore capability
- Auto-save with crash recovery
- Full undo/redo history

**Multi-Language**
- English, Spanish (Español), Chinese (简体中文), Thai (ไทย)
- AI-powered map label translation between languages
- Adaptive CJK toolbar icons

<br>

## Supported ECUs

| Manufacturer | ECU Families |
|---|---|
| **Bosch** | MED17, MG1, MD1, EDC17, EDC16, EDC15, ME7, ME9, MED9, MSV, MSD |
| **Continental** | SIMOS 12/16/18/19/22, SID, SCG, SCM |
| **Delphi** | DCM3.x, DCM6.x, DCU-10x |
| **Denso** | Multiple generations |
| **Magneti Marelli** | MJD, 7GV/8GMK |
| **Valeo** | VD46 |

<br>

## System Requirements

| | Minimum | Recommended |
|---|---|---|
| **OS** | Windows 10 / macOS 12 / Ubuntu 22.04 | Windows 11 / macOS 14 / Latest LTS |
| **RAM** | 4 GB | 8 GB |
| **Disk** | 500 MB | 1 GB |
| **Display** | 1280 x 720 | 1920 x 1080 |

<br>

## Installation

**Windows** — Download `RX14-Setup.exe` and run it. Single self-contained executable, no dependencies needed.

**macOS** — Download `RX14.dmg`, open it, and drag romHEX 14 to your Applications folder.

**Linux** — Download `RX14.AppImage`, make it executable (`chmod +x`), and run it.

<br>

## Build from Source

```bash
# Prerequisites: Qt 6.10+, CMake 3.16+, C++17 compiler

git clone https://github.com/ctabuyo/romHEX14-ECU-Tuning.git
cd romHEX14-ECU-Tuning
mkdir build && cd build
cmake .. -DCMAKE_PREFIX_PATH=/path/to/qt6
cmake --build . -j$(nproc)
```

<br>

## License

This software is distributed under the [GNU Lesser General Public License v3.0](https://www.gnu.org/licenses/lgpl-3.0.html) (LGPL-3.0).

Built with the [Qt Framework](https://www.qt.io/) (LGPL).

Copyright (c) 2024-2026 CT14 Garage Co., Ltd. All rights reserved.

<br>

---

<div align="center">
<sub>Built with precision by <b>CT14 Garage</b> — Professional ECU Calibration Solutions</sub>
</div>

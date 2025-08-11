# UNHEARD DEVTOOLS

A curated Scoop bucket containing developer tools and utilities that are not available in the official `Scoop/Extras` or `Scoop/Main` buckets. This bucket focuses on specialized development tools, particularly for embedded systems, VEX robotics, and various system utilities.

## Quick Start

### Installation

To install this bucket, run the following commands in PowerShell or Command Prompt:

```powershell
# Add the bucket
scoop bucket add unheard-devtools https://github.com/saturnyx/unheard-devtools

# Install a tool from the bucket
scoop install unheard-devtools/<tool-name>

# For example, to install PROS:
scoop install unheard-devtools/pros
```

### Usage Examples

```powershell
# Install VEX robotics development tools
scoop install unheard-devtools/pros unheard-devtools/pros-toolchain

# Install Swift development for VEX V5
scoop install unheard-devtools/swift-v5

# Install GUI tools
scoop install unheard-devtools/git-cola unheard-devtools/zen-browser
```

## Current Tools

| Tool              | Description                                                                                                                  |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| curator           | Scoop bucket curator - helps maintain and organize Scoop packages                                                            |
| git-cola          | A highly-caffeinated, powerful, and intuitive graphical user interface for Git                                               |
| hdd-raw-copy-tool | HDD Raw Copy Tool is a utility for low-level, sector-by-sector hard disk duplication and image creation.                     |
| pros              | An open source C/C++ development environment for the VEX V5 microcontroller                                                  |
| pros-toolchain    | ARM GCC toolchain for PROS VEX V5 development                                                                                |
| protobot          | A new actively maintained version of Protobot - VEX Robotics prototyping tool                                                |
| python34          | Python 3.4.4 - Legacy Python version for compatibility (⚠️ End-of-life, security vulnerabilities)                            |
| swift-v5          | LLVM toolchain manager for embedded Swift projects on the VEX V5 platform                                                    |
| termite           | Termite is an easy to use and easy to configure RS232 terminal                                                               |
| usbtreeview       | USB Device Tree Viewer                                                                                                       |
| wtq               | Turn any app into a Quake-style toggleable app                                                                               |
| zen-browser       | A privacy-focused browser that blocks trackers, ads, and other unwanted content while offering the best browsing experience! |

## Categories

### VEX Robotics Development

-   **pros** - Complete C/C++ development environment for VEX V5
-   **pros-toolchain** - ARM GCC compiler toolchain for VEX V5
-   **protobot** - VEX robotics prototyping and design tool
-   **swift-v5** - Embedded Swift development for VEX V5 platform

### Development Tools

-   **git-cola** - Advanced Git GUI client
-   **curator** - Scoop bucket maintenance utility
-   **python34** - Legacy Python 3.4.4 for compatibility (⚠️ End-of-life)

### System Utilities

-   **hdd-raw-copy-tool** - Low-level disk duplication utility
-   **termite** - RS232 serial terminal
-   **usbtreeview** - USB device hierarchy viewer
-   **wtq** - Quake-style app toggler

### Web Browsers

-   **zen-browser** - Privacy-focused web browser

## Features

-   🔄 **Auto-updates**: All packages are configured with automatic version detection
-   📦 **Easy Installation**: Simple one-command installation via Scoop
-   🛠️ **Specialized Tools**: Focus on developer tools not found in main Scoop buckets
-   🤖 **VEX Robotics**: Comprehensive toolchain for VEX V5 development
-   🔧 **System Utilities**: Various system administration and debugging tools

## Licensing

This repository is licensed under the MIT License.

### What You Can Do

-   Use the software for any purpose (commercial, personal, educational)
-   Copy and distribute the software
-   Modify the software and create derivative works
-   Distribute modified versions
-   Sell copies or include in proprietary software

### What You Must Do

-   Include the original license and copyright notice in all copies
-   Give credit to the original authors when redistributing

### What You Cannot Do

-   Hold authors liable for damages or issues caused by the software
-   Use authors' names to endorse derived products without permission

> [!NOTE]
> The MIT License only applies to this repository, not the apps and tools in it.

# Device Info Spoofer Module

## Overview
This Magisk module allows you to spoof your device information (vendor, name, CPU, GPU) to enhance performance in apps that might throttle or limit functionality based on device model.

## Features
- Spoofs device information to high-end models
- Spoofs processor vendor and build fingerprints
- Intelligent device detection to choose the most compatible profile
- Supports 15+ device profiles across multiple brands (Realme, Redmi, Xiaomi, Samsung, OPPO, OnePlus, Vivo, Infinix, Itel)
- Compatible with all CPU types (Snapdragon, MediaTek, Exynos, Unisoc)
- Compatible with Android 10+
- Applies performance tweaks to CPU, GPU, and I/O

## Default Device Profile
- **Device**: Realme 14T 5G (RMX1432)
- **Manufacturer**: OPPO
- **CPU**: MediaTek Dimensity 8350 (MT6886)
- **CPU Vendor**: MediaTek
- **GPU**: Mali-G615 MC6
- **RAM**: 12GB
- **Storage**: 512GB
- **Build Fingerprint**: realme/RMX1432/RMX1432:13/TKQ1.221114.001/1673459339:user/release-keys

## Enhanced Spoofing
The module now includes comprehensive CPU and vendor spoofing:
- Full CPU ABI fingerprinting (arm64-v8a, armeabi-v7a)
- Vendor-specific properties for each processor type
- Build fingerprints that match high-end devices
- Version-specific identifiers for app compatibility

## Smart Features
- Auto-detects your device brand and selects a compatible profile
- Properly applies CPU/GPU properties based on the selected model
- Detailed logging for troubleshooting

## Installation
1. Flash the module through Magisk Manager
2. Reboot your device
3. Verify installation by checking your device information in settings or using a system info app

## Notes
- This module modifies system properties and could potentially cause issues with some apps
- If you experience any problems, simply disable or uninstall the module through Magisk Manager
- A log file is created at `/data/local/tmp/device_spoofer.log`

## Author
willygailo01@gmail.com

## Version
v1.2

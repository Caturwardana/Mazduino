# rusEFI Firmware for Mazduino-Compact

## Overview
This directory contains rusEFI firmware and configuration files for the Mazduino-Compact ECU board.

## Firmware Download Options

### Important Note
You are **not required** to use the `rusefi.hex` file that may be present in this folder. You can download the latest firmware directly from the official rusEFI build server.

### Official Download Links

#### Discovery F407 Platform
- **Download URL:** https://rusefi.com/build_server/rusefi_bundle_f407-discovery.zip
- **Platform:** Discovery F407
- **Description:** Latest stable firmware build for STM32F407-based boards

#### Mega100 Platform  
- **Download URL:** https://rusefi.com/build_server/rusefi_bundle_mega100.zip
- **Platform:** Mega100
- **Description:** Latest stable firmware build for Mega100 platform

## Installation Instructions

1. Download the appropriate firmware bundle from one of the links above
2. Extract the downloaded zip file
3. Use the rusEFI Console or your preferred flashing tool to upload the firmware
4. Apply the base tune configuration from the `basetune/` folder if available

## Configuration Files

Check the `basetune/` directory for:
- Base tune files (.msq)
- Configuration templates
- Sensor calibration data

## Support and Documentation

- **Official Website:** https://rusefi.com/
- **Documentation:** https://wiki.rusefi.com/
- **Community Forum:** https://rusefi.com/forum/
- **GitHub Repository:** https://github.com/rusefi/rusefi

## Compatibility

This firmware is designed for use with the Mazduino-Compact ECU board. Ensure you select the correct platform variant when downloading from the build server.

## Updates

Always check the official rusEFI build server for the latest firmware versions, as they include the newest features, bug fixes, and improvements.

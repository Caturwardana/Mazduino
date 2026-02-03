# Speeduino Firmware for Mazduino-Compact

## Important Notice

### Custom Firmware Required
The Mazduino ECU can **ONLY** run **custom Speeduino firmware**. The official Speeduino firmware from the main project **will NOT work** with Mazduino boards due to hardware differences and pin mapping requirements.

### Compatibility Warning
- ⚠️ **DO NOT** use official Speeduino firmware releases
- ⚠️ **DO NOT** download firmware from speeduino.com for direct use
- ✅ **ONLY** use the custom firmware provided in this repository

## Board Compatibility

### Tested Hardware
- **Mazduino Compact v1.x** - ✅ Fully tested and supported

### Untested/Unsupported
- **Mazduino Compact v2.x and above** - ⚠️ Not tested with this firmware
- **Other Mazduino variants** - ⚠️ May require different firmware versions

## Firmware Versions Available

Check the version folders for available firmware builds:
- `202501/` - January 2025 custom build
- `202501.2/` - January 2025 revised build
- `basetune/` - Base configuration files

## Installation Instructions

1. **Select the appropriate version** from the available folders
2. **Use Arduino IDE or PlatformIO** to flash the custom firmware
3. **Apply base tune settings** from the `basetune/` folder
4. **Verify pin mapping** matches your specific Mazduino Compact v1 board

## Why Custom Firmware?

The Mazduino boards use different:
- Pin assignments compared to standard Arduino Mega
- Hardware layout and connections
- Sensor input configurations
- Output driver arrangements

These differences require custom firmware modifications that are not present in the official Speeduino releases.

## Support and Resources

- **Mazduino Documentation:** Check the main repository wiki
- **Speeduino Community:** https://speeduino.com/forum/ (for general Speeduino questions)
- **Custom Firmware Issues:** Report in the Mazduino project repository

## Upgrading Board Versions

If you have a **Mazduino Compact v2.x or newer**, check the appropriate firmware directory for your board version, as this firmware is specifically for v1.x boards only.
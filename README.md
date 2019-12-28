# ender5_notes

Notes about use of Ender 5 Pro

## Octoprint Flash Setup

Ender 5 Pro comes with bootloader installed, so there is no need to use Arduino board's programmer or have any special connection other than Octopi connected to printer's USB port.

### Requirements
 - Ender 5 board with bootloader
 - Octoprint connected via USB
 - Octoprint Firmware Updater (https://plugins.octoprint.org/plugins/firmwareupdater/)


### Configuration
```
Board: Sanguino1284p
Processor: ATmega1284p (16 MHz)
Programmer: AVRISP mkII
```

### Loading
Follow plugin instruction to flash the board.

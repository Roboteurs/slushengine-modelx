# SlushEngine Model:X #

This repository contains the hardware design files for the SlusheEngine. The current design is created on Kicad (BZR 5744). If you wish to contribute to the SlusheEngine project please contact Reiner at info at roboteurs dot com.

If you want to get going on your own project using the SlushEngine please fork it and have fun!

![](board.png)

## Technical Specifications ##
- Based of L6470 Stepper motor drivers
- Board design to handle 32A on the VPP input
- Supply 5v @ 2A to the Raspberry Pi
- UEXT Connector for expansion modules
- Temperature sensing inputs
- Logic level I/Os and Industrial Level IO (24VDC)
- MAX1164 for temperature sensor handling (2 Channels)
- MCP23017 for I/O expansion on I2C bus
- Raspberry Pi Hat spec eeprom circuit

## Basic Electrical Characteristics ##

- **Max VPP Voltage:** 35VDC
- **Max Current:** 32A
- **No Load Current:** *unkown*
- **Max SPI bus Frequency:** 5Mhz
- **Max Tempratre at L6470L** *unkown*

## Avalible Hardware mods

- **R1010** Can be changed to compensate for off voltage motor (see L6470 datasheet)
- **JP1002** Can be cut to prevent board from powering an expansion module (bottom of the board)

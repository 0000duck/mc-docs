\_\_NOTOC\_\_\[\[[File:EEProm1.png|right|framed](File:EEProm1.png%7Cright%7Cframed)|

<center>

Example **EEProm** settings from a Lulzbot TAZ 6 running Marlin 1.0.2

</center>

\]\]

MatterControl supports interacting with EEPROM as allowed by the
firmware-- Marlin and Repetier only.

**EEPROM** stands for 'Electrically Erasable Programmable Read Only
Memory' and can also be written, 'EEPROM'. EEPROM is memory on the
printer's circuit board which stores a series of values for certain
settings. These values usually relate to the specific printer's
geometric, physical, and operative functions and statistics.

## Firmware Support

MatterControl supports EEProm for only Marlin and Repetier firmwares.

  - Marlin firmware EEProm documentation:
    <https://github.com/MarlinFirmware/Marlin/wiki/EEPROM>
  - Repetier firmware EEProm documentation:
    <http://www.repetier.com/documentation/repetier-firmware/rf-installation/>

## Example

For an example of how to use the EEProm window to adjust the printer's
[steps per mm](steps-per-mm), check out this page: [Setting
Steps per mm](setting-steps-per-mm.md)

## Interface

### Reset to Factory Defaults

This will reset all settings to your firmware's defaults.

### Save to EEProm

Saves any applicable changes made using the interface to the EEPROM on
the printer.

### Import...

Import .ini files containing EEPROM configuration. Click this button to
open the OS file chooser.

### Export...

Export .ini files containing EEPROM configuration. Click this button to
open the OS file saver.

### Close

Close without saving changes.

[Category:Features](category:features)
[Category:Firmware](category:firmware)

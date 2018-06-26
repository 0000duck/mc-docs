\[\[[File:EEProm2.png|right|frame](File:EEProm2.png%7Cright%7Cframe)|

<center>

EEPROM settings can be found under the Options menu.

</center>

\]\]MatterControl can set EEProm settings for both Marlin and Repetier
firmwares.

## Procedure

This is a great way to fix problems with the printer not moving the
expected distance, or having parts come out with incorrect dimensions.

![Set\_eeprom2.png](Set_eeprom2.png "Set_eeprom2.png")

1.  Navigate to ![Settings\_Controls.png](Settings_Controls.png
    "Settings_Controls.png")
2.  Click on the ![Options.png](Options.png "Options.png") tab
3.  Connect to your printer
4.  In the **EEProm** section click on
    ![EEProm\_configure.png](EEProm_configure.png
    "EEProm_configure.png")
5.  Change the **Steps per mm** to correct for any discrepancy you find
    in your movement distances. ![Set\_eeprom5.png](Set_eeprom5.png
    "Set_eeprom5.png")

### Equation

Here is the equation to find the correct value:

`New_Value = Current_Value / Actual_Distance * Desired_Distance`

So if the current value for X was 80 and the printer only moved 97mm
when trying to move 100mm, the equation would be: `80 / 97 * 100` The
new X Steps Per mm to 82.47.

The same principle applies for the extruder. If over/under-extruding,
use this equation.

## Cartesian vs. delta

Steps per mm settings will be different for Cartesian printers vs. delta
printers.

Cartesian printers have one value for **each** axis. This means there
will be a **Steps per mm (X)**, **Steps per mm (Y)**, and **Steps per mm
(Z)**. Each will be different, and will require the above calculation to
determine the correct value.

Delta printers only have one **Steps per mm** field because all three
motors work in conjunction to triangulate the position of the nozzle.
Thus, only one calculation is needed if the dimensions of the printed
part differs from those of the model. If measured independently, they
should all be off by the same ratio. If not, the problem lies elsewhere.

[Category:How-to](Category:How-to "wikilink")
[Category:Troubleshooting](Category:Troubleshooting "wikilink")

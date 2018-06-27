![EEProm2.png](http://wiki.mattercontrol.com/images/7/79/EEProm2.png "EEProm2.png")

EEPROM settings can be found under the Options menu.
MatterControl can set EEProm settings for both Marlin and Repetier
firmwares.

## Procedure

This is a great way to fix problems with the printer not moving the
expected distance, or having parts come out with incorrect dimensions.

![Set\_eeprom2.png](http://wiki.mattercontrol.com/images/b/b2/Set_eeprom2.png "Set_eeprom2.png")

1.  Navigate to ![Settings\_Controls.png](http://wiki.mattercontrol.com/images/4/42/Settings_Controls.png
    "Settings_Controls.png")
2.  Click on the ![Options.png](http://wiki.mattercontrol.com/images/8/8b/Options.png "Options.png") tab
3.  Connect to your printer
4.  In the **EEProm** section click on
    ![EEProm\_configure.png](http://wiki.mattercontrol.com/images/9/9c/EEProm_configure.png
    "EEProm_configure.png")
5.  Change the **Steps per mm** to correct for any discrepancy you find
    in your movement distances. ![Set\_eeprom5.png](http://wiki.mattercontrol.com/images/a/ae/Set_eeprom5.png
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

[Category:How-to](category:how-to)
[Category:Troubleshooting](category:troubleshooting)

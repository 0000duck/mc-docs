\_\_NOTOC\_\_MatterControl filters G-Code as it sends it to the printer
via serial USB communication to maintain compatibility with a large
range of printer types.

## Automatic Changes

### M109

MatterControl automatically converts
[M109](http://reprap.org/wiki/G-code#M109:_Set_Extruder_Temperature_and_Wait)
commands to
[M104](http://reprap.org/wiki/G-code#M104:_Set_Extruder_Temperature)
commands.

### M190

MatterControl automatically converts
[M190](http://reprap.org/wiki/G-code#M190:_Wait_for_bed_temperature_to_reach_target_temp)
commands to
[M140](http://reprap.org/wiki/G-code#M140:_Set_Bed_Temperature_.28Fast.29)
commands...

### G91

MatterControl accepts
[G91](http://reprap.org/wiki/G-code#G91:_Set_to_Relative_Positioning)
commands for relative positioning, but instead of just allowing them
straight through it interprets them as absolute coordinates and feeds
those to the printer.

### G0

Certain printers do not accept
[G0](http://reprap.org/wiki/G-code#G0_.26_G1:_Move) as a valid command
for movement, so MatterControl sends the more common
[G1](http://reprap.org/wiki/G-code#G0_.26_G1:_Move) command instead.

Starting in version 1.6, the **[Use
G0](settings/general/output-options/file-settings/use-g0)**
setting will allow for the use of G0 if desired.

### Coordinate Truncation

To save bandwidth, MatterControl truncates superfluous coordinates in
movement commands. For example, if the printer is currently at
coordinates X30 Y40 Z50 and the next G-Code command is:

then MatterControl will truncate this command to:

since the X and Z coordinates are the same as the current position.

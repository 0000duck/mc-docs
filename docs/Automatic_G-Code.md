MatterSlice adds certain automatically generated code before and after
your custom [custom start
G-Code](Settings/Printer/Custom_G-Code/Start_G-Code "wikilink"). This
normally where your temperature settings would be applied. MatterSlice
will wait for the bed to warm up first, then begin warming the extruder,
then run the [custom start
G-Code](Settings/Printer/Custom_G-Code/Start_G-Code "wikilink"), and
finally wait for the extruder to finish heating before continuing.

If MatterSlice detects that you have any extruder heating commands
(`M104`, `M109`) in your custom start G-Code, it will remove these from
the automatic G-Code. Likewise for bed heating commands (`M140`,
`M190`).

Here are some examples of the automatic G-Code:

Before:

`   ; automatic settings before start_gcode  `  
`   G21 ; set units to millimeters  `  
`   M107 ; fan off  `  
`   M190 S95 ; wait for bed temperature to be reached  `  
`   M104 T0 S210 ; start heating extruder 1  `  
`   T0 ; set the active extruder to 0`

After:

`   ; automatic settings after start_gcode`  
`   M109 T0 S210 ; wait for extruder 1 to reach temperature`  
`   T0 ; set the active extruder to 0`  
`   G90 ; use absolute coordinates`  
`   G92 E0 ; reset the expected extruder position`  
`   M82 ; use absolute distance for extrusion`

## See also

  - [Start
    G-Code](Settings/Printer/Custom_G-Code/Start_G-Code "wikilink")

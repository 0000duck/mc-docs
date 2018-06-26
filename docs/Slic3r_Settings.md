<div style="float:right;">

\_\_TOC\_\_

</div>

The slice settings for Slic3r in MatterControl are divided by three
categories:

  - **General**: This is where the settings concerning the actual
    printed part are located. Things like, layer height, support
    material, and infill.
  - **Filament**: This is where the settings concerning the filament are
    located. Things like temperature control and cooling.
  - **Printer**: This is where settings concerning the actual hardware
    are located. Things like bed size, nozzle diameter, and custom
    G-Code.

We'll be breaking them down by sub-category, in order, assuming that
"Show All Settings" is checked.

If a setting isn't visible, make sure "Show All Settings" is checked.

# General

## Layers/Perimeters

### ***Layer Height***

  -   
    **Layer Height:** This determines the quality of the print in its
    entirety. The thinner the layer, the higher the resolution. This
    also is the biggest factor when determining print time.

<!-- end list -->

  -   
    **First Layer Height:** This determines the height of your first
    layer, which is useful in making sure your print has a good starting
    point. Remember, the vast majority of prints will fail within the
    first layer.

### ***Vertical Shells***

  -   
    **Perimeters (minimum):** This determines how many vertical layers
    you have on your print. i.e. how thick your walls will be.

<!-- end list -->

  -   
    **Spiral Vase:** Force the print to have only one vertical layer and
    gradually increase the extruder height during the print. Only one
    part can be printed at a time with this feature.

### ***Horizontal Shells***

  -   
    **Number of Solid Layers on the Top:** This determines how many of
    the top layers will be solid. This is useful when the
    [infill](infill "wikilink") is lower.

<!-- end list -->

  -   
    **Number of Solid Layers on the Bottom:** This determines how many
    solid layers will be printed before the printer begins to use
    [infill](infill "wikilink").

### ***Quality (slower slicing)***

  -   
    '''Generate Extra Perimeters When Needed: Allow Slic3r to generate
    extra perimeters when needed for sloping walls.

<!-- end list -->

  -   
    **Avoid Crossing Perimeters:** Attempts to minimize the number of
    perimeters crossing. This can help with oozing or strings.

<!-- end list -->

  -   
    **Start At Concave Point:** Make sure the first point on a perimeter
    is a concave point.

<!-- end list -->

  -   
    **Start At Non Overhang:** Make sure the first point on a perimeter
    is not an overhang.

<!-- end list -->

  -   
    **Thin Walls:** Detect when walls are too close together and need to
    be extruded as just one wall.

### ***Advanced***

  -   
    **Randomize Starting Points:** Start each new layer from a different
    vertex to reduce seams.

<!-- end list -->

  -   
    **External Perimeters First:** Normally external perimeters are
    printed last, this makes them go first.

## Infill

### ***Infill***

  -   
    '''Fill Density: ''' The ratio of material to empty space ranged 0
    to 1. 0 would be no infill, 1 is solid infill

<!-- end list -->

  -   
    **Fill pattern:** The pattern used on the inside portions of the
    print.

<!-- end list -->

  -   
    **Top/Bottom Fill Pattern:** The pattern used on the bottom and top
    layers of the print.

### ***Advanced***

  -   
    '''Infill Every: ''' Sets which layers will receive infill. This
    should normally stay set to 1 to make strong parts.

<!-- end list -->

  -   
    **Only Infill Where Needed:** Creates infill only where it will be
    used as internal support.

<!-- end list -->

  -   
    **Solid Infill Every:** Sets how often a layer will be forced to be
    solid infilled. Zero will result in normal infill throughout.

<!-- end list -->

  -   
    **Fill Angle:** Sets the starting angle of the infill.Not used when
    bridging.

<!-- end list -->

  -   
    **Solid Infill Threshold Area:** Forces solid infill for any area
    less than this amount.

<!-- end list -->

  -   
    **Only Retract When Crossing Perimeters:** Prevents retraction while
    within a printing perimeter.

<!-- end list -->

  -   
    **Do Infill Before Perimeters:** Sets infill to happen before
    perimeters are created.

## Speed

### ***Speed for Print Moves***

  -   
    '''Perimeters: ''' Sets the default movement speed while printing
    perimeters.

<!-- end list -->

  -   
    **Small Perimeters:** Used for small perimeters (usually holes).
    This can be set explicitly or as a percentage of the perimeters’
    speed.

<!-- end list -->

  -   
    **External Perimeters:** The speed to print the visible outside
    edges. This can be set explicitly or as a percentage of the
    percentage of the perimeters’ speed.

<!-- end list -->

  -   
    **Infill:** The speed to print infill.

<!-- end list -->

  -   
    **Solid Infill:** The speed to print infill when completely solid.
    This can be set explicitly or as a percentage of the infill speed.

<!-- end list -->

  -   
    **Top Solid Infill:** The speed to print the top infill. This can be
    set explicitly or as a percentage of the infill speed.

<!-- end list -->

  -   
    **Support Material:** The speed to print support material
    structures.

<!-- end list -->

  -   
    **Bridges:** The speed to move when bridging between walls.

<!-- end list -->

  -   
    **Gap Fill:** Speed to fill small gaps Keep low to avoid vibration.
    Set to 0 to skip filling small gaps.

### ***Speed for non Print Moves***

  -   
    **Travel:** Speed to move when not extruding material.

### ***Modifiers***

  -   
    **First Layer Speed** The speed to move while printing the first
    layer. If expressed as a percentage it will modify the corresponding
    speed set above.

### ***Acceleration Control***

  -   
    **Perimeters:** Acceleration to use on perimeters Set to 0 to
    disable changing the printer’s acceleration.

<!-- end list -->

  -   
    '''Infill: ''' Acceleration to use while infilling. Set to 0 to
    disable changing the printer’s acceleration.

<!-- end list -->

  -   
    **First Layer:** Acceleration to use while printing the first layer.
    Set to 0 to the default first layer acceleration.

<!-- end list -->

  -   
    '''Default: ''' Acceleration to use on all moves not defined above.
    Set to 0 to disable changing the printer’s acceleration.

## Skirt and Brim

### ***Skirt***

  -   
    '''Loops: ''' The number of loops to draw around all the parts on
    the bed.

<!-- end list -->

  -   
    **Distance from Object:** The distance to start drawing the first
    skirt loop.

<!-- end list -->

  -   
    **Skirt Height:** The number of layers to draw the skirt.

<!-- end list -->

  -   
    **Minimum Extrusion Length:** Sets the minimum amount of filament to
    use drawing the skirt loops. This will cause at least enough skirt
    loops to be drawn to use this amount of filament.

### ***Brim***

  -   
    **Brim width:** The amount of brim that will be drawn around each
    object. this is useful to ensure that parts stay affixed to the bed.

## Support Material

### ***Support Material***

  -   
    **Generate Support Material:** This turns on and off the generation
    of support material.

<!-- end list -->

  -   
    **Overhang Threshold:** The last angle at which support material
    will be generated. Larger numbers will result in more support. Set
    to 0 to enable automatic settings.

<!-- end list -->

  -   
    **Enforce Support For First:** Generate support material everywhere
    not touching the bad for n layers, regardless of angle.

### ***Raft***

  -   
    **Raft Layers:** Number of layers to print before printing any
    parts.

### ***Options***

  -   
    **Pattern:** The pattern used while generating support material.

<!-- end list -->

  -   
    **Pattern Spacing:** The space between the lines of the support
    material.

<!-- end list -->

  -   
    **Pattern Angle:** The starting angle of the supports.

<!-- end list -->

  -   
    **Interface Layers:** The number of layers to print between the
    supports and the part.

<!-- end list -->

  -   
    **Interface Pattern Spacing:** The space between lines of the
    interface layers (0 is solid).

<!-- end list -->

  -   
    **X and Y Distance:** The distance the support material will be from
    the object in the x and y direction.

<!-- end list -->

  -   
    '''Z Distance: ''' The distance the support material will be from
    the object in the z direction.

## Notes

  -   
    **Notes:** This is a place to input notes that will be added as
    comments in the header of the output G-Code.

## Output Options

### ***Sequential Printing***

  -   
    **Complete Individual Objects:** Each individual part is printed to
    completion then the extruder is lowered back to the bed and the next
    part is printing.

<!-- end list -->

  -   
    **Extruder Clearance Radius:** This is used to figure out how far
    apart individual parts must be printed to allow them to be completed
    before printing the next part.

### ***Output File***

  -   
    **Verbose G-Code:** Include detailed comments in the G-Code.

<!-- end list -->

  -   
    **Output File Name Format:** Sets the way that slicer creates file
    names (this is not used by MatterControl).

### ***Post-Processing Scripts***

You can include additional programs to process the G-Code after slicer
is finished. The complete path of the program to run should be included
here.

## Multiple Extruders'''''

### ***Extruders***

  -   
    **Perimeter Extruder:** The index of the extruder to use for
    perimeters.
    **Infill Extruder:** The index of the extruder to use for infill.

<!-- end list -->

  -   
    **Support Material Extruder:** The index of the extruder to use for
    support material.

<!-- end list -->

  -   
    **Support Interface Extruder:** The index of the extruder to use for
    support material interface layers.

### ***Ooze Prevention***

  -   
    '''Enable: ''' This will lower the temperature of the non-printing
    extruder to help prevent oozing.

<!-- end list -->

  -   
    **Temp Lower Amount:** This is the amount to lower the temperature
    of an extruder that is not currently printing.

## Advanced

### ***Extrusion Width***

  -   
    **Default Extrusion Width:** Leave this as 0 to allow automatic
    calculation of extrusion width.

<!-- end list -->

  -   
    **First Layer:** Setting this to greater than 100% can often help
    the first layer have better adhesion to the print bed.

<!-- end list -->

  -   
    **Perimeters:** Leave this as 0 to allow automatic calculation of
    extrusion width.

<!-- end list -->

  -   
    **Infill:** Leave this as 0 to allow automatic calculation of
    extrusion width.

<!-- end list -->

  -   
    **Solid Infill:** Leave this as 0 as to allow automatic calculation
    of extrusion width.

<!-- end list -->

  -   
    **Support Material:** Leave this as 0 as to allow automatic
    calculation of extrusion width.

### ***Flow***

  -   
    **Bridge Flow Ratio:** This controls the ratio of material extruder
    during bridging. Reducing this slightly can help bridging by
    stretching the filament more. Using a fan can also help greatly.

### ***Other***

  -   
    **Threads:** The number of CPU cores to use while doing slicing.
    Increasing this can slow down your machine.

<!-- end list -->

  -   
    **Resolution:** The minimum feature size to consider from the model.
    Leave at 0 to use all the model detail.

<!-- end list -->

  -   
    **Extrusion Axis:** This is the identifier used in the GCde to
    specify the extruder.

<!-- end list -->

  -   
    **Optimize Overhangs:** Experimental feature that attempts to
    improve overhangs using the fan and bridge settings.

# Filament

## Filament

### ***Filament***

  -   
    **Diameter:** This should be set to the actual diameter of the
    filament you are using on your printer. Measure 5 times with
    calipers, throw out the top and bottom, and average the remaining 3.

<!-- end list -->

  -   
    **Extrusion Multiplier:** All extrusions are multiplied by this
    value. Increasing it above 1 (1.1 is a good max value) will increase
    the amount of filament being extruded; decreasing it (.9 is a good
    min value) will decrease the amount being extruded.

### ***Temperature (°C)***

  -   
    **Extrude First Layer:** The temperature to set the extruder to
    before printing the first layer of a part. This printer will wait
    until this temperature has been reached before printing.

<!-- end list -->

  -   
    **Extruder Other Layers** The temperature to set the extruder to
    after the first layer has been printed.

<!-- end list -->

  -   
    **Bed First Layer:** The temperature to set the bed to before
    printing the first layer. The printer will wait until this
    temperature has been reached before printing. Set to 0 to eliminate
    bed temperature commands.

<!-- end list -->

  -   
    **Bed Other Layers:** The temperature to set the bed to after the
    first layer has been printed. Set to 0 to eliminate bed temperature
    commands.

### ***Retraction***

  -   
    **Length:** The amount that the filament will be reversed after each
    qualifying non-printing move.

<!-- end list -->

  -   
    **Change Tool:** The amount the extruder head will be lifted after
    each retraction.

<!-- end list -->

  -   
    **Z Lift:** The amount the extruder head will be lifted after each
    retraction.

<!-- end list -->

  -   
    **Speed:** The speed that the filament will be retracted (and
    re-extruded).

<!-- end list -->

  -   
    **Extra Length On Restart:** Additional amount of filament that will
    be extruded after a retraction.

<!-- end list -->

  -   
    **Minimum Travel After Retraction:** The minimum distance of a
    non-printing move that will result in a retraction.

<!-- end list -->

  -   
    **Retract On Layer Change:** If set, a retraction will occur prior
    to changing the layer height.

<!-- end list -->

  -   
    **Wipe Before Retract:** This will cause the extruder to move while
    retracting to minimize blobs.

### ***Retraction When Tool is Disabled (for multi-extruders)***

  -   
    **Length:** The amount the filament will be retracted when changing
    to a different extruder.

<!-- end list -->

  -   
    **Extra Length On Restart:** Additional amount of filament that will
    be extruded after a retraction.

## Cooling

### ***Enable***

  -   
    **Keep Fan Always On:** This will force the fan to remain on
    throughout the print. In general you should have this off and just
    enable auto cooling.

<!-- end list -->

  -   
    **Enable Auto Cooling:** Turns on and off all cooling settings (all
    settings below this one).

### ***Fan Speed***

  -   
    **Min Fan Speed:** This is the minimum fan speed that your fan can
    run at.

<!-- end list -->

  -   
    **Max Fan Speed:** This is the maximum speed that your fan can run
    at.

<!-- end list -->

  -   
    **Bridging Fan Speed:** The fan speed to use during bridging.

<!-- end list -->

  -   
    **Disable Fan For The First:** The number of layers for which the
    fan will be forced to remain off.

### ***Cooling Thresholds***

  -   
    **Enable Fan If Layer Print Time Is Below:** If a layer is estimated
    to take less than this print, the fan will be turned on.

<!-- end list -->

  -   
    **Slow Down If Layer Print Time Is Below** If a layer is estimated
    to take less than this to print, the movement speed will be reduced
    to try and make the layer take this long to print.

<!-- end list -->

  -   
    **Min Print Speed:** This is the minimum speed that the printer will
    reduce to, to make the layer tak long enough to satisfy the min
    layer time.

# Printer

## Print Area

### ***Size and Coordinates***

  -   
    **Bed Size:** The size of the print bed.

<!-- end list -->

  -   
    **Print Center:** The position (coordinates) of the center of the
    print bed.

<!-- end list -->

  -   
    **Build Height:** The height of the printable area. If set to 0 the
    parts height will not be validated.

<!-- end list -->

  -   
    **Z Offset:** This value will be added to all of the z positions of
    the created G-Code.

<!-- end list -->

  -   
    **Bed Shape:** The shape of the physical bed.

### ***Firmware***

  -   
    **G-Code Flavor** Some firmware uses different g and m codes.
    Setting this ensures that the output G-Code will use the correct
    commands.

<!-- end list -->

  -   
    **Use Relative E Distances** Normally you will want to use absolute
    e distances. Only check this if you know your printer needs relative
    e distances.

<!-- end list -->

  -   
    **Use Arcs:** Use firmware arcs rather than multiple segments for
    curves.

<!-- end list -->

  -   
    **Use G0:** Use G0 for moves rather than G1.

### ***Advanced***

  -   
    **Use Firmware Retraction:** Request the firmware to do retractions
    rather than specify the extruder movements directly.

<!-- end list -->

  -   
    **Vibration Limit:** This is to help reduce vibrations during
    printing. If your printer has a resonance frequency that is causing
    trouble, you can set this to try and reduce printing at that
    frequency.

## Custom G-Code

  -   
    **Start G-Code:** G-Code input in this field will go into effect as
    soon as you start a print.

<!-- end list -->

  -   
    **End G-Code:** G-Code input in this field will go into effect as
    soon as a print finishes.

<!-- end list -->

  -   
    **Layer Change G-Code:** G-Code input in this field will be inserted
    right after the change in z height for the next layer.

<!-- end list -->

  -   
    **Tool Change G-Code:** G-Code input in this field will be inserted
    after every tool change.

<!-- end list -->

  -   
    **Pause G-Code:** G-Code input in this field will go into effect
    when the 'Pause' button is pressed during a print.

<!-- end list -->

  -   
    **Resume G-Code:** G-Code input in this field will go into effect
    when the 'Resume' button is pressed after the print having been
    paused.

<!-- end list -->

  -   
    **Cancel G-Code:** G-Code input in this field will go into effect
    when the 'Cancel' button is pressed during a print.

<!-- end list -->

  -   
    **On-Connect G-Code:** G-Code input in this field will go into
    effect when MatterControl successfully connects to the printer.

## Extruder

### ***Extruder 1***

  -   
    **Nozzle Diameter:** This is the diameter of your extruder nozzle.

<!-- end list -->

  -   
    **Extruder Offset:** This is the offset of each extruder relative to
    the first extruder. Only useful for multiple extruder machines.

[Category:Slice Settings](Category:Slice_Settings "wikilink")

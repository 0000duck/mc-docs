 The slice settings for CuraEngine in MatterControl are
divided by three categories:

  - **General**: This is where the settings concerning the actual
    printed part are located. Things like, layer height, support
    material, and infill.
  - **Filament**: This is where the settings concerning the filament are
    located. Things like temperature control and cooling.
  - **Printer**: This is where settings concerning the actual hardware
    are located. Things like bed size, nozzle diameter, and custom
    GCode.

We'll be breaking them down by sub-category, in order, assuming that
[Advanced
mode](getting-started.md#Show_All_Settings_.2F_User_Level_.28Basic.2C_Intermediate.2C_Advanced.29)
is enabled. If a setting isn't visible, make sure [Advanced
mode](getting-started.md#Show_All_Settings_.2F_User_Level_.28Basic.2C_Intermediate.2C_Advanced.29)
is enabled.

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
    [infill](infill.md) is lower.

<!-- end list -->

  -   
    **Number of Solid Layers on the Bottom:** This determines how many
    solid layers will be printed before the printer begins to use
    [infill](infill.md).

## Infill

### ***Infill***

  -   
    **Fill Density:** This determines the density of your infill within
    the print. This affects print time, total weight, and filament used.

## Speed

### ***Speed for Print Moves***

  -   
    **Perimeters:** This determines how fast your printer will travel
    when extruding perimeters.

<!-- end list -->

  -   
    **Infill:** This determines how fast your printer will travel when
    extruding infill.

### ***Speed for non Print Moves***

  -   
    **Travel:** How fast your printer will move when it is **not**
    otherwise extruding.

### ***Modifiers***

  -   
    **First Layer Speed:** This determines how fast the printer will
    extrude during the first layer. This is typically a percentage of
    the previous settings, as extruding the first layer more slowly
    helps the print get started.

## Skirt and Brim

### ***Skirt***

  -   
    **Loops:** This value determines how many loops around the print
    will be extruded at the start.

<!-- end list -->

  -   
    **Distance from Object:** How far from the print the loops will be
    extruded.

<!-- end list -->

  -   
    **Minimum Extrusion Length:** Sets the minimum amount of filament to
    use when drawing the skirt loops. This will cause enough skirt loops
    to be drawn to use this amount of filament.

## Support Material

### ***Support Material***

  -   
    **Generate Support Material:** Checking the box enables the printing
    of support material with whatever settings you have enabled.

<!-- end list -->

  -   
    **Overhang Threshold:** This determines the angle at which your
    print will have support material generated.

### ***Options***

  -   
    **Pattern Spacing:** This determines the density of your support
    material. Essentially the infill for it.

<!-- end list -->

  -   
    **X and Y Distance:** How far the infill will rest away from your
    print on the X and Y axis. The farther away it is, the easier it is
    to disconnect.

<!-- end list -->

  -   
    **Z Distance:** How far the infill will rest away from your print on
    the Z axis. The farther away it is, the easier it is to disconnect.

# Filament

## Filament

### ***Filament***

  -   
    **Diameter:** Here you would enter the diameter of your filament.
    This setting is usually already entered when you first connect to a
    printer, giving it the default settings from the manufacturer.

### ***Temperature***

  -   
    **Extruder Other Layers:** This determines the extruder temperature
    for the duration of the print.

<!-- end list -->

  -   
    **Bed Other Layers:** For printers with heat controlled beds, this
    determines the bed temperature for the duration of the print.

## Cooling

### ***Fan Speed***

  -   
    **Min Fan Speed:** This value determines the slowest speed that your
    fan is allowed to go, by percentage.

<!-- end list -->

  -   
    **Max Fan Speed:** This value determines the fastest speed that your
    fan is allowed to go, by percentage.

<!-- end list -->

  -   
    **Disable Fan For The First:** This determines how many layers
    should go by without the fan being enabled.

### ***Cooling Thresholds***

  -   
    **Slow Down If Layer Print Time Is Below:** This value determines
    the minimum amount of time a layer is allowed to take, in seconds.
    If the layer finishes before the allotted time, the extruder will
    move away and stop until it is allowed to resume.

# Printer

## General

### ***Size and Coordinates***

  -   
    **Bed Size:** These values determine how long your bed is along each
    axis, by millimeters.

<!-- end list -->

  -   
    **Print Center:** These values determine where the center of your
    bed lies.

<!-- end list -->

  -   
    **Build Height:** How high your bed can lower or raise, along the Z
    axis.

<!-- end list -->

  -   
    **Bed Shape:** This determines the shape of your bed, either
    rectangular or circular.

## Custom G-Code

  -   
    **Start G-Code:** GCode input in this field will go into effect as
    soon as you start a print.

<!-- end list -->

  -   
    **End G-Code:** GCode input in this field will go into effect as
    soon as a print finishes.

<!-- end list -->

  -   
    **Pause G-Code:** GCode input in this field will go into effect when
    the 'Pause' button is pressed during a print.

<!-- end list -->

  -   
    **Resume G-Code:** GCode input in this field will go into effect
    when the 'Resume' button is pressed after the print having been
    paused.

<!-- end list -->

  -   
    **Cancel G-Code:** GCode input in this field will go into effect
    when the 'Cancel' button is pressed during a print.

<!-- end list -->

  -   
    **On-Connect G-Code:** GCode input in this field will go into effect
    when MatterControl successfully connects to the printer.

## Extruder 1

### ***Size***

  -   
    **Nozzle Diameter:** This is where you input the diameter of the
    nozzle, in millimeters.

### ***Retraction***

  -   
    **Length:** This value determines how far your filament will be
    retracted with each qualifying non-printing move, in millimeters.

<!-- end list -->

  -   
    **Speed:** This Value determines how fast your filament will be
    retracted, and re-extruded, in millimeters.

<!-- end list -->

  -   
    **Minimum Travel After Retraction:** This value determines the
    minimum distance of a non-printing move that will result in a
    retraction.

[Category:Slice Settings](category:slice-settings)

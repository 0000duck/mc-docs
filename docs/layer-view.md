\_\_NOTOC\_\_\[\[<File:LAYER> VIEW-ss.png|right|thumb|550px|

<center>

**LAYER VIEW** in 3D mode. Colors indicate speeds.

</center>

\]\] **LAYER VIEW** is a pane which allows the user to preview a print's
G-Code tool path as a visual representation. It has two modes: 2D and
3D. *Note*: 3D mode is not available on the [MatterControl
Touch](mattercontrol-touch).

It is accessed by clicking the ![LAYER\_VIEW.png](http://wiki.mattercontrol.com/images/b/b2/LAYER_VIEW.png
"LAYER_VIEW.png") icon in the pane on the right side of the [Main
Screen](main-screen).

The pane can be [popped out](pop-out) into its own window.
![Pop\_out.png](http://wiki.mattercontrol.com/images/7/74/Pop_out.png "Pop_out.png")

## [View Controls](view-controls)

![3D\_View-Controls.png](http://wiki.mattercontrol.com/images/7/7c/3D_View-Controls.png "3D_View-Controls.png")

View Controls is a set of tools which allow the user to manipulate the
view and/or models currently displayed.

In LAYER VIEW, the following tools are available:

  - [Reset View](view-controls#Reset_View)
  - [Rotate](view-controls#Rotate) (only in [3D
    mode](#3D))
  - [Move](view-controls#Move)
  - [Zoom](view-controls#Zoom)

## Mode Controls

![2D\_3D.png](http://wiki.mattercontrol.com/images/a/a7/2D_3D.png "2D_3D.png")

### 2D

Enters LAYER VIEW's [2D mode](#2D_mode).

### 3D

Enters LAYER VIEW's [3D mode](#3D_mode).

## Generate

![Generate.png](http://wiki.mattercontrol.com/images/6/63/Generate.png "Generate.png")

Slices the current model using the [slice settings](settings)
and displays the tool path.

## Graphical display

\[\[[File:Layers.gif|right|framed](File:Layers.gif%7Cright%7Cframed)|

<center>

LAYER VIEW in 2D mode, showing each layer of the [MatterHackers test
object](:file:mhobject.stl)

</center>

\]\]

Once G-Code for a model has been generated or loaded, the main area of
the LAYER VIEW pane will display the tool path. Depending on which
graphical display mode is selected, the toolpath is able to be displayed
in different
ways.

### Navigation

\[\[[File:Layer\_View-Nav.png|none|framed](File:Layer_View-Nav.png%7Cnone%7Cframed)|

<center>

Navigation for a 50-layer print. Layer 37 is currently displayed.

</center>

\]\]

#### \<\<

Navigate down one layer.

#### \>\>

Navigate up one layer.

#### \# / \#

The currently displayed layer / total number of layers

#### Go

Navigate to the layer specified in the field to the left of the **Go**
button.

### 2D mode

**2D mode** displays one layer at a time in a two-dimensional graphic.

### 3D mode

**3D mode** displays the tool path in a three-dimensional environment.
The specified layer and any lower layers are shown.

## Sidebar

The sidebar in LAYER VIEW has two sections: MODEL and DISPLAY.

![LAYER\_VIEW-Sidebar.png](http://wiki.mattercontrol.com/images/c/c5/LAYER_VIEW-Sidebar.png
"LAYER_VIEW-Sidebar.png")

### MODEL

Contains information about the print.

![LAYER\_VIEW-MODEL.png](http://wiki.mattercontrol.com/images/f/f7/LAYER_VIEW-MODEL.png "LAYER_VIEW-MODEL.png")

#### Print Time

The length of time the print is estimated to take.

#### Filament Length

The length of filament the print is estimated to use, in millimeters.

#### Filament Volume

The volume of filament the finished print is estimated to be, in cubic
centimeters.

#### Estimated Mass

The estimated mass of the finished print, in grams. This is calculated
as the [filament
density](settings/filament/material/properties/density) in
grams per cubic centimeter times [length of
filament](layer-view#Filament_Length), in centimeters,
extruded.

#### Estimated Cost

The estimated cost of the print, based on the amount of material used,
the [density](settings/filament/material/properties/density),
and the [price of the
material](settings/filament/material/properties/cost). This
information will not be visible if the material cost is set to 0.

### DISPLAY

![Layer\_View-DISPLAY.png](http://wiki.mattercontrol.com/images/0/05/LAYER_VIEW-DISPLAY.png
"Layer_View-DISPLAY.png")

#### Print Bed

Toggles the graphical display of the print bed.

#### Moves

Toggles the display of non-print moves in the tool path.

#### Retractions

Toggles the display of locations of the start and end of retraction
events.

#### Speeds

Toggles the display of color-coding of the tool path to indicate the
speed at which it is run. The tool path changes to a different color for
each speed specified under the [Speed
sub-category](settings/general/speed) in General settings. A
legend is generated at the top left of the pane.

#### Extrusion

Toggles the display of visual representation of the flow as defined by
the

#### Transparent

Toggles transparency of the tool path. Only available in [2D
mode](#2D_mode).

#### Sync To Print

Draws the tool path in real time while a print is active.

[Category:Features](category:features)

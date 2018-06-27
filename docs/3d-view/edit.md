\[\[[File:Edit-ss.png|right|framed](File:Edit-ss.png%7Cright%7Cframed)|

<center>

**Edit** mode when [more than one
extruder](settings/printer/features/hardware/extruder-count)
is configured.

</center>

\]\]Edit mode allows the user to make minor changes to the model
currently loaded in [3D VIEW](3d-view.md).

## [View Controls](view-controls.md)

![View\_Controls.png](http://wiki.mattercontrol.com/images/b/ba/View_Controls.png "View_Controls.png")

View Controls is a set of tools which allow the user to manipulate the
view and/or models currently displayed.

In Edit mode, the following tools are available:

  - [Reset View](view-controls.md#Reset_View)
  - [Rotate](view-controls.md#Rotate)
  - [Move](view-controls.md#Move)
  - [Zoom](view-controls.md#Zoom)
  - [Select Part](view-controls.md#Select_Part)

  

## Undo / Redo

The **Undo** and **Redo** buttons will undo or redo the last edit,
respectively.

![Undo\_Redo.png](http://wiki.mattercontrol.com/images/5/51/Undo_Redo.png
"Undo_Redo.png")

## ROTATE

\[\[[File:Edit-Rotate-example.gif|right|thumb|350px](File:Edit-Rotate-example.gif%7Cright%7Cthumb%7C350px)|

<center>

A model rotated around the X Axis, 45 degrees at a time.

</center>

\]\]The **ROTATE** function allows the user to rotate the model a
specific number of degrees around a specified axis.

![Edit-Rotate.png](http://wiki.mattercontrol.com/images/a/a8/Edit-Rotate.png "Edit-Rotate.png")

### Degrees

Enter the number of degrees to rotate the model.

### Axes buttons

Click the button for the axis around which to rotate the model to
perform the rotation.

### Align to Bed

Will cause MatterControl to attempt to bring the part down flat,
adjacent to the bed. Useful for resetting the position of the
model.

  

## SCALE

\[\[[File:Edit-Scale-example.gif|right|thumb|350px](File:Edit-Scale-example.gif%7Cright%7Cthumb%7C350px)|

<center>

A model scaled to 1, 2, then 3 times its size.

</center>

\]\]The **SCALE** section allows the user to change the size of the
model.

![Edit-Scale.png](http://wiki.mattercontrol.com/images/5/54/Edit-Scale.png "Edit-Scale.png")

### Ratio

The **Ratio** field allows the user to specify a positive whole or
decimal number which will be multiplied by the existing model's
dimensions.

#### Presets

The **Ratio** field has several presets for common translations:

  - mm to in (.0393)
  - in to mm (25.4)
  - mm to cm (.1)
  - cm to mm (10)
  - reset (1)

### X

The **X** field allows for direct specification of the dimension of the
model's size along the X axis.

### Y

The **Y** field allows for direct specification of the dimension of the
model's size along the Y axis.

### Z

The **Z** field allows for direct specification of the dimension of the
model's size along the Z axis.

### Lock Ratio

If checked, the **Lock Ratio** option maintains the ratio of the model's
dimensions relative to each other. For example, if a model's dimensions
are X:20, Y:20, Z:50 and the Y value is changed to 10, X becomes 10 and
Z becomes 25 automatically.

  
\== MIRROR
==

\[\[[File:Edit-Mirror-example.gif|right|thumb|350px](File:Edit-Mirror-example.gif%7Cright%7Cthumb%7C350px)|

<center>

A model mirrored over the Z axis.

</center>

\]\]The **MIRROR** section allows the user to translate a model over an
axis.

![Edit-Mirror.png](http://wiki.mattercontrol.com/images/1/17/Edit-Mirror.png "Edit-Mirror.png")

### X

Click the **X** button to translate the model over the X axis.

### Y

Click the *'Y* button to translate the model over the Y axis.

### Z

Click the **Z** button to translate the model over the Z axis.

  
\== MATERIALS
==

\[\[[File:Multi-extrusion.png|right|thumb|350px](File:Multi-extrusion.png%7Cright%7Cthumb%7C350px)|

<center>

Two aligned models: one to be printed with Extruder 1 and the other with
Extruder 2.

</center>

\]\]The **MATERIALS** section allows the user to specify which extruder
will be used to print a model.

This section is shown only when the [Extruder
Count](settings/printer/features/hardware/extruder-count)
setting is set to a value greater than 1.

See also: [Multi-Extrusion](multi-extrusion.md)

![Edit-Materials.png](http://wiki.mattercontrol.com/images/3/30/Edit-Materials.png "Edit-Materials.png")  
\== DISPLAY ==

The **DISPLAY** section allows the user to toggle certain visual
options.

![Edit-Display.png](http://wiki.mattercontrol.com/images/a/a2/Edit-Display.png "Edit-Display.png")

### Show Print Bed

If enabled, the graphical print bed is displayed.

![Edit-Show\_Print\_Bed-example.gif](http://wiki.mattercontrol.com/images/e/e6/Edit-Show_Print_Bed-example.gif
"Edit-Show_Print_Bed-example.gif")

### Show Print Area

If enabled, a translucent box appears to indicate the build volume. The
box's height is set by the [Build
Height](settings/printer/print-area/size-and-coordinates/build-height)
setting.

![Edit-Show\_Print\_Area-example.gif](http://wiki.mattercontrol.com/images/e/ea/Edit-Show_Print_Area-example.gif
"Edit-Show_Print_Area-example.gif")

### Shaded

Shows only the faces of the model.

### Outlines

Shows the faces and lines of a model, but does not include lines which
connect vertices of single flat polygons.

### Polygons

Shows all faces and lines of a model, including all lines which connect
vertices of single flat
polygons.

\[\[[File:Edit-Display-example.gif|none|thumb|400px](File:Edit-Display-example.gif%7Cnone%7Cthumb%7C400px)|

<center>

Cycling between Shaded, Outlines, and Polygons.

</center>

\]\]

  

## Snap Grid

Specify the increment of distance a model will move when moved using the
[Select Part](view-controls.md#Select_Part) tool.

![Snap\_Grid-ss.png](http://wiki.mattercontrol.com/images/d/dc/Snap_Grid-ss.png "Snap_Grid-ss.png")

## Insert

![3D\_View-Insert.png](http://wiki.mattercontrol.com/images/1/13/3D_View-Insert.png "3D_View-Insert.png")

Opens the operating system file manager so a model file can be selected
for addition to any existing models in the current view.

## Ungroup

![Edit-Ungroup.png](http://wiki.mattercontrol.com/images/e/e9/Edit-Ungroup.png "Edit-Ungroup.png")

Separates unconnected models. This is typically used if multiple models
are loaded into MatterControl as part of one STL file.

Once ungrouped, the models can be selected and edited individually.

## Group

![Edit-Group.png](http://wiki.mattercontrol.com/images/6/6d/Edit-Group.png "Edit-Group.png")

Combines all models currently displayed. The combined "model" can then
be selected and edited as a whole.

## Align

![Edit-Align.png](http://wiki.mattercontrol.com/images/b/ba/Edit-Align.png "Edit-Align.png")

Moves ungrouped models into a grid pattern relative to the currently
selected model, then group all models.

## Arrange

![Edit-Arrange.png](http://wiki.mattercontrol.com/images/d/dd/Edit-Arrange.png "Edit-Arrange.png")

Centers all models in a grid pattern.

## Copy

![Edit-Copy.png](http://wiki.mattercontrol.com/images/f/f5/Edit-Copy.png "Edit-Copy.png")

Makes a copy of the currently selected model.

## Remove

![Edit-Remove.png](http://wiki.mattercontrol.com/images/8/80/Edit-Remove.png "Edit-Remove.png")

Deletes the currently selected
model.

## Cancel

\[\[[File:Edit-Save-prompt.png|right|framed](File:Edit-Save-prompt.png%7Cright%7Cframed)|

<center>

If unsaved changes have been made, the user is prompted.

</center>

\]\]![Edit-Cancel.png](http://wiki.mattercontrol.com/images/b/b9/Edit-Cancel.png "Edit-Cancel.png")

Exits Edit mode. The user is prompted to save any unsaved changes.  
\== Save ==

![Edit-Save.png](http://wiki.mattercontrol.com/images/9/90/Edit-Save.png "Edit-Save.png")

Saves changes to the
model.

## Save As

\[\[[File:Edit-Save-As-ss.png|right|framed](File:Edit-Save-As-ss.png%7Cright%7Cframed)|

<center>

The **Save New Design** window.

</center>

\]\]![Edit-Save-As.png](http://wiki.mattercontrol.com/images/4/43/Edit-Save-As.png "Edit-Save-As.png")

Opens the **Save New Design** dialog box which prompts the user to save
a new file in a specified location.

[Category:Incomplete](category:incomplete)

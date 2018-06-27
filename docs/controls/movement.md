<div style="float:right;">

\_\_TOC\_\_

</div>

The Movement section of the Controls pane allows the user to manually
move the printer nozzle(s), and extrude and retract filament when no
print is active. This section also serves as fine movement adjustment
during an active print.

Manual movement speed preferences can be
saved.

\[\[[File:Movement-ss.png|none|framed](File:Movement-ss.png%7Cnone%7Cframed)|

<center>

The **Movement** section of the Controls pane.

</center>

\]\]

## Home Buttons

Used to home axes. ![Home\_buttons-ss.png](http://wiki.mattercontrol.com/images/8/8e/Home_buttons-ss.png
"Home_buttons-ss.png")

### ALL

Homes all three axes. Issues a `G28` G-Code command.

### X

Homes only the X axis. Issues a `G28 X0` G-Code command.

### Y

Homes only the Y axis. Issues a `G28 Y0` G-Code command.

### Z

Homes only the Z axis. Issues a `G28 Z0` G-Code command.

## Axis Motion Buttons

Used to move the nozzle along the printer's axes. During a print, can be
used to make minor (0.02 mm) adjustments to the nozzle's location (baby
stepping). ![Axis\_Motion\_Buttons-ss.png](http://wiki.mattercontrol.com/images/e/e0/Axis_Motion_Buttons-ss.png
"Axis_Motion_Buttons-ss.png")

### X+

Jog the nozzle the specified distance to the right along the X axis.

### X-

Jog the nozzle the specified distance to the left along the X axis.

### Y+

Jog the nozzle the specified distance toward the rear of the printer
along the Y axis.

### Y-

Jog the nozzle the specified distance toward the front of the printer
along the Y axis.

### Z+

Jog the nozzle up the specified distance (along the Z axis).

### Z-

Jog the nozzle down the specified distance (along the Z axis).

### Distance selector

Jog distances are pre-configured. Select one to jog axis movements by
that distance. ![Distance\_selector-ss.png](http://wiki.mattercontrol.com/images/a/ab/Distance_selector-ss.png
"Distance_selector-ss.png")

## Extrusion Motion Buttons

Used to manually extrude and retract filament.
![Extruder\_Motion\_Buttons-ss.png](http://wiki.mattercontrol.com/images/9/99/Extruder_Motion_Buttons-ss.png
"Extruder_Motion_Buttons-ss.png")

### E+

Extrude the specified length of filament.

### E-

Retract the specified length of filament.

### Length Selector

Extrusion/retraction lengths are pre-configured. Select one to extrude
or retract filament for that length.

![Length\_selector-ss.png](http://wiki.mattercontrol.com/images/8/81/Length_selector-ss.png
"Length_selector-ss.png")

### Multi-Extruder Buttons

If multiple extruders are specified, a set of buttons will appear for
each
extruder.

![Multi-Extruder\_Motion\_Buttons-ss.png](http://wiki.mattercontrol.com/images/1/1e/Multi-Extruder_Motion_Buttons-ss.png
"Multi-Extruder_Motion_Buttons-ss.png")

## Keyboard Hotkeys

When toggled on, keyboard keys can be used to issue commands. Click the
keyboard icon (![Keyboard\_icon.png](http://wiki.mattercontrol.com/images/d/d7/Keyboard_icon.png
"Keyboard_icon.png")) to enable.

<table>
<thead>
<tr class="header">
<th><p>Function</p></th>
<th><p>Key</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Home All</p></td>
<td><p>Home</p></td>
</tr>
<tr class="even">
<td><p>Home X</p></td>
<td><p>X</p></td>
</tr>
<tr class="odd">
<td><p>Home Y</p></td>
<td><p>Y</p></td>
</tr>
<tr class="even">
<td><p>Home Z</p></td>
<td><p>Z</p></td>
</tr>
<tr class="odd">
<td><p>X-</p></td>
<td><p>Left arrow</p></td>
</tr>
<tr class="even">
<td><p>X+</p></td>
<td><p>Right arrow</p></td>
</tr>
<tr class="odd">
<td><p>Y+</p></td>
<td><p>Up arrow</p></td>
</tr>
<tr class="even">
<td><p>Y-</p></td>
<td><p>Down arrow</p></td>
</tr>
<tr class="odd">
<td><p>Z+</p></td>
<td><p>Page Up</p></td>
</tr>
<tr class="even">
<td><p>Z-</p></td>
<td><p>Page Down</p></td>
</tr>
<tr class="odd">
<td><p>E+ (Extrude)</p></td>
<td><p>E</p></td>
</tr>
<tr class="even">
<td><p>E- (Retract)</p></td>
<td><p>R</p></td>
</tr>
</tbody>
</table>

## Movement Speeds Presets

\[\[[File:Movement\_Speeds\_Presets-ss.png|right|framed](File:Movement_Speeds_Presets-ss.png%7Cright%7Cframed)|

<center>

The 'Movement Speeds Presets' window

</center>

\]\]Click the pencil icon (![Pencil-edit.png](http://wiki.mattercontrol.com/images/b/b0/Pencil-edit.png
"Pencil-edit.png")) to the right of the **Movement** title to open the
Movement Speeds Presets window. Here, the speed(s) at which respective
axis or extruder will move during manual moves can be set. Speeds are
measured in millimeters per minute.

### Axis X

The movement speed for all manual movements along the X axis.

### Axis Y

The movement speed for all manual movements along the Y axis.

### Axis Z

The movement speed for all manual movements along the Z axis.

### Extruder 1

The movement speed for all manual movements for Extruder 1.  
\== Current Position Monitor ==

Shows the current position of Extruder 1's nozzle.

![Current\_Position\_Monitor-ss.png](http://wiki.mattercontrol.com/images/b/b5/Current_Position_Monitor-ss.png
"Current_Position_Monitor-ss.png")

## RELEASE

Releases all motors. Can be useful if the user wants to move the
carriage by hand.

![Release-ss.png](http://wiki.mattercontrol.com/images/1/13/Release-ss.png "Release-ss.png")

[Category:Controls](category:controls)
[Category:Features](category:features)

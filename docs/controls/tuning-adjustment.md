\[\[<File:Tuning> Adjustment-ss.png|right|framed|

<center>

The **Tuning Adjustment** section of the Controls pane.

</center>

\]\]The Tuning Adjustment section of the Controls pane allows the user
to change the speed and extrusion values during an active print.

Use the slider or enter a value and click **Set**.

## Speed Multiplier

When used during an active print, the speed multiplier modifies the
speeds as set under the [Speed section in General
settings](settings/general/speed) by multiplying itself times
each setting.

### Range

  - Low : 0.5
  - High : 2.0

## Extrusion Multiplier

When used during an active print, the extrusion multiplier modifies the
extrusion flow rate (as defined in the [formula
below](#Formula)).

This variable is different from that of the [Extrusion Multiplier slice
setting](settings/filament/extrusion/flow/extrusion-multiplier)
and will work in conjunction with it. For example, if the slicer setting
is set at 1.06 and then the slider in Controls is used during the print
and set to 1.08, the total result will be a multiplier of 1.1448 (1.06
\* 1.08).

### Formula

The general extrusion flow formula: `layer height / (filament area
(pi*r²) * `**`extrusion`` ``multiplier`**`)`

### Range

  - Low : 0.5
  - High : 3.0

[Category:Controls](category:controls)
[Category:Features](category:features)

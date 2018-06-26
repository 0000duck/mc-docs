\[\[[File:SPL7.png|right|framed](File:SPL7.png%7Cright%7Cframed)|

<center>

The Software Print Leveling section as shown in the **Options** menu.

</center>

\]\]The Software Print Leveling feature of MatterControl compensates for
an uneven bed. It is a form of [Automatic Print
Leveling](Automatic_Print_Leveling "wikilink"). Measurement is taken of
the bed as it is, then G-Code is adjusted as the print happens. The
G-Code itself is not changed, but rather a filter is applied, making
adjustments on-the-fly. For this reason, existing .gcode files can be
printed using MatterControl with Software Print Leveling applied.

Related settings can be found in [Settings \> Printer \> Print
Leveling](SETTINGS/Printer/Print_Leveling "wikilink").  
\== Enable/Disable ==

![http://wiki.mattercontrol.com/images/5/55/SPL.gif](http://wiki.mattercontrol.com/images/5/55/SPL.gif "http://wiki.mattercontrol.com/images/5/55/SPL.gif") Click the slider to the right to enable or
disable Software Print Leveling. An icon will appear next to the
extruder temperature indicator if leveling is enabled.  
\== Edit Data ==

Click the pencil icon (![http://wiki.mattercontrol.com/images/b/b0/Pencil-edit.png](http://wiki.mattercontrol.com/images/b/b0/Pencil-edit.png
"http://wiki.mattercontrol.com/images/b/b0/Pencil-edit.png")) to edit existing leveling data.

![http://wiki.mattercontrol.com/images/4/4f/SPL8.png](http://wiki.mattercontrol.com/images/4/4f/SPL8.png "http://wiki.mattercontrol.com/images/4/4f/SPL8.png")

  
\== Wizard ==

Based on the [leveling
solution](SETTINGS/Printer/Print_Leveling/Machine_Settings/Leveling_Solution "wikilink")
specified in slice settings, the printer will run through a 3-, 7-, or
13-point configuration wizard to sense the shape and orientation of the
print bed.

<table>
<tbody>
<tr class="odd">
<td><figure>
<img src="SPL1.png" title="SPL1.png" alt="SPL1.png" /><figcaption>SPL1.png</figcaption>
</figure></td>
<td><figure>
<img src="SPL2.png" title="SPL2.png" alt="SPL2.png" /><figcaption>SPL2.png</figcaption>
</figure></td>
</tr>
<tr class="even">
<td><center>
<p>First, the wizard explains the basic process and tells the user to get a piece of paper.</p>
</center></td>
</tr>
</tbody>
</table>

  
{| class="wikitable" style="margin: auto;" |- | ![http://wiki.mattercontrol.com/images/c/c7/SPL3.png](http://wiki.mattercontrol.com/images/c/c7/SPL3.png
"http://wiki.mattercontrol.com/images/c/c7/SPL3.png") || ![http://wiki.mattercontrol.com/images/a/ab/SPL4.png](http://wiki.mattercontrol.com/images/a/ab/SPL4.png "http://wiki.mattercontrol.com/images/a/ab/SPL4.png") |- | colspan="2" |

<center>

![http://wiki.mattercontrol.com/images/d/d2/SPL5.png](http://wiki.mattercontrol.com/images/d/d2/SPL5.png "http://wiki.mattercontrol.com/images/d/d2/SPL5.png")

</center>

|- | colspan="2" |

<center>

At each point, the wizard has the user test the height at low, medium,
and high precision.

</center>

|}  
{| class="wikitable" style="margin: auto;" |- | ![http://wiki.mattercontrol.com/images/9/98/SPL6.png](http://wiki.mattercontrol.com/images/9/98/SPL6.png
"http://wiki.mattercontrol.com/images/9/98/SPL6.png") |- | When all point have been measured, the wizard is
complete. |}

[Category:Options](Category:Options "wikilink")

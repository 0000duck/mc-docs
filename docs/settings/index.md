![Slice\_Settings-ss.png](http://wiki.mattercontrol.com/images/5/57/Slice_Settings-ss.png
"Slice_Settings-ss.png")Welcome to the Slice Settings main page\! Below
you will find links to the categories, sub-categories, and sections of
settings for [MatterSlice](matterslice.md), as well as
information about the menus and options available.

To access the Slice Settings menu from the MatterControl main screen,
click ![Settings\_Controls.png](http://wiki.mattercontrol.com/images/4/42/Settings_Controls.png
"Settings_Controls.png") --\> ![Settings.png](http://wiki.mattercontrol.com/images/9/91/Settings.png
"Settings.png")

The pane can be [popped out](pop-out.md) into its own window.
![Pop\_out.png](http://wiki.mattercontrol.com/images/7/74/Pop_out.png "Pop_out.png")

<table>
<thead>
<tr class="header">
<th><h2 style="text-align:left;">
<p><a href="General" title="wikilink">General</a></p>
</h2></th>
<th><h2 style="text-align:left;">
<p><a href="Filament" title="wikilink">Filament</a></p>
</h2></th>
<th><h2 style="text-align:left;">
<p><a href="Printer" title="wikilink">Printer</a></p>
</h2></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><big><strong><a href="General/Layers-Surface" title="wikilink">Layers / Surface</a></strong></big></p></td>
<td><p><big><strong><a href="Filament/Material" title="wikilink">Material</a></strong></big></p></td>
<td><p><big><strong><a href="Printer/Connection" title="wikilink">Connection</a></strong></big></p></td>
</tr>
<tr class="even">
<td><p><big><strong><a href="General/Infill" title="wikilink">Infill</a></strong></big></p></td>
<td><p><big><strong><a href="Filament/Temperatures" title="wikilink">Temperatures</a></strong></big></p></td>
<td><p><big><strong><a href="Printer/Print_Area" title="wikilink">Print Area</a></strong></big></p></td>
</tr>
<tr class="odd">
<td><p><big><strong><a href="General/Speed" title="wikilink">Speed</a></strong></big></p></td>
<td><p><big><strong><a href="Filament/Retraction" title="wikilink">Retraction</a></strong></big></p></td>
<td><p><big><strong><a href="Printer/Features" title="wikilink">Features</a></strong></big></p></td>
</tr>
<tr class="even">
<td><p><big><strong><a href="General/Raft-Priming" title="wikilink">Raft / Priming</a></strong></big></p></td>
<td><p><big><strong><a href="Filament/Extrusion" title="wikilink">Extrusion</a></strong></big></p></td>
<td><p><big><strong><a href="Printer/Print_Leveling" title="wikilink">Print Leveling</a></strong></big></p></td>
</tr>
<tr class="odd">
<td><p><big><strong><a href="General/Support_Material" title="wikilink">Support Material</a></strong></big></p></td>
<td><p><big><strong><a href="Filament/Cooling" title="wikilink">Cooling</a></strong></big></p></td>
<td><p><big><strong><a href="Printer/Print_Recovery" title="wikilink">Print Recovery</a></strong></big></p></td>
</tr>
<tr class="even">
<td><p><big><strong><a href="General/Output_Options" title="wikilink">Output Options</a></strong></big></p></td>
<td></td>
<td><p><big><strong><a href="Printer/Custom_G-Code" title="wikilink">Custom G-Code</a></strong></big></p></td>
</tr>
<tr class="odd">
<td><p><big><strong><a href="General/Multiple_Extruders" title="wikilink">Multiple Extruders</a></strong></big></p></td>
<td></td>
<td><p><big><strong><a href="Printer/Extruder" title="wikilink">Extruder</a></strong></big></p></td>
</tr>
<tr class="even">
<td><p><big><strong><a href="General/Single_Print" title="wikilink">Single Print</a></strong></big></p></td>
<td></td>
<td></td>
</tr>
</tbody>
</table>

  

## Sync Behavior

Starting in version 1.6, settings are automatically synced between
instances of MatterControl which are signed in to the same
[MatterHackers.com account](matterhackers.com-account.md).
Updating a setting in one instance will automatically change the setting
in all other instances.

## Overlays

Settings are highlighted for a couple of reasons:

### Presets

![Preset_Highlights.png](http://wiki.mattercontrol.com/images/9/9b/403x179xPreset_Highlights.png.pagespeed.ic.wUAOZPS8Fi.png "Preset_Highlights.png")
Both a quality and material preset are applied.

When a preset is enabled, the affected settings are highlighted in
the color associated with the type of preset. See the [Preset
Menus](#Preset_Menus) section below for more information.

## Change from default

![Setting_changed.gif](http://wiki.mattercontrol.com/images/d/da/Setting_changed.gif.pagespeed.ce.f6nLv_qFht.gif "Setting_changed.gif")
Changing a setting from the default will highlight it in blue.

Whenever a setting is manually changed from the profile default, a
blue highlight appears over the setting and an 'X' icon appears to the
right. Clicking the X will restore the default value.  

## Preset Menus

![Preset_Menus.png](http://wiki.mattercontrol.com/images/b/bb/Preset_Menus.png "Preset_Menus.png")
The SETTINGS **Preset Menus**, shown here with the default (no) presets
selected.

These menus allow the user to save one or more settings as a preset
list under one name instead of changing every setting for a particular
material or desired quality individually.

Both menus essentially do the same thing; the difference is that the
QUALITY menu is meant to hold presets of settings unique to different
desired qualities and the MATERIAL menu is meant to hold presets of
settings unique to different filaments. If a selected preset in both
menus each contain the same setting, the setting specified in the
MATERIAL preset menu trumps the one in the QUALITY menu.

### Pre-configured Presets

Many printer profiles come pre-configured with presets for common
filaments and quality settings. The availability of these presets varies
widely depending on the printer manufacturers and MatterHackers'
internal test and support department.  

## Show Help

**Show Help** enabled.

![Show_Help-ss.png](http://wiki.mattercontrol.com/images/6/60/592x295xShow_Help-ss.png.pagespeed.ic.vun3MEdIDx.png "")

When checked, an explanation for each function will be revealed
underneath its name.

## Settings Level Menu
![Settings_Level_Menu.png](http://wiki.mattercontrol.com/images/3/31/592x295xSettings_Level_Menu.png.pagespeed.ic.S1V0H5CHRG.webp "Settings_Level_Menu.png")
The **Settings Level** Menu

This menu allows the user to choose between three levels of settings
complexity:

<table>
<tbody>
<tr class="odd">
<td><p><strong>Basic:</strong></p></td>
<td></td>
<td><p>The minimal settings group for beginners or those who want to print quickly. More info: <a href="https://www.matterhackers.com/articles/slice-settings-explained-part-1">SLICE SETTINGS EXPLAINED - PART 1</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Standard:</strong></p></td>
<td></td>
<td><p>A few more settings than the Basic level, but not the complete list. More info: <a href="https://www.matterhackers.com/articles/slice-settings-explained-part-2">SLICE SETTINGS EXPLAINED - PART 2</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Advanced:</strong></p></td>
<td></td>
<td><p>All MatterSlice slice settings displayed. More info: <a href="https://www.matterhackers.com/articles/slice-settings-explained---part-3">SLICE SETTINGS EXPLAINED - PART 3</a></p></td>
</tr>
</tbody>
</table>

## Options... Menu

The **Options...** Menu
![Options..._Menu.png](http://wiki.mattercontrol.com/images/3/3b/597x294xOptions..._Menu.png.pagespeed.ic.bPEqMYYTw6.webp "Options..._Menu.png")
The **Options...** menu has five functions: [Show
Help](#Show_Help), Import, Export, Restore Settings, and
Reset to defaults.

  - **Import** allows the user to load a slice settings file (.slice,
    .ini, .printer) into MatterControl. Any existing values will be
    replaced by those in the file.
  - **Export** allows the user to save all current slice settings values
    to file.
  - **Restore Settings** opens the 'Restore Settings' window, allowing
    the user to select from the last ten automatically-saved
    configurations and restore one.
  - **Reset to defaults** resets all settings back to their default
    values taken from the printer profile.

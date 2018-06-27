<div style="float: right;">

\_\_TOC\_\_

</div>

This page contains a brief description of each new release of
MatterControl. The version numbers shown on this page are for the
official [MatterHackers releases](downloads).

## 1.7.5

**Not released yet.**

### Changes

  - Added filament selection into leveling wizard so we heat to printing
    temp before sampling.

## 1.7.4

**Release Date:** July, 14, 2017

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgID64sGDCgwLEgZVcGxvYWQYgICA-vf2jwkM)
  - \[Mac Download\]
  - \[Linux Download\]

### Changes

  - Put in the ability to ramp the extra extrusion after move to
    compensate for oozing while moving.

## 1.7.3

**Release Date:** July, 6, 2017

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgIDa26CGCgwLEgZVcGxvYWQYgICAutPtmQsM)
  - \[Mac Download\]
  - \[Linux Download\]

### Changes

  - Created regex filters that can be applied to printer read and
    writes. Allows us to support more printers.

## 1.7.2

**Release Date:** June, 19, 2017

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgIDamL2UCgwLEgZVcGxvYWQYgICA2v78gAoM)
  - \[Mac Download\]
  - \[Linux Download\]

### Changes

  - Fixed bug in leveling for JumpStart printer

## 1.7.1

**Release Date:** June, 11, 2017

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgICSxoqdCgwLEgZVcGxvYWQYgICAmsW_hQkM)
  - \[Mac Download\]
  - \[Linux Download\]

### Changes

  - New mesh bed leveling option (3x3)
  - Improved tool pathing while printing supports
  - Improved wipe towers while printing support
  - Improved extruder selection when more than 2 extruders available
  - Fixed small over extrusion issues with some overhang tool paths
  - Added support for filament run out sensor
  - New SMS messages for pausing and filament run out
  - Added support for automatic probing if sensor available
  - Added Support for probing servo
  - Improved translations
  - General bug fixing

## 1.7.0

**Release Date:** March 14, 2017

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgIDCgYuDCQwLEgZVcGxvYWQYgICA4ou_lwoM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgICwjeuTCgwLEgZVcGxvYWQYgICAsN-jmgoM)
  - [Linux
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyQQsSB1Byb2plY3QYgICAiOCSzAsMCxINUHVibGljUmVsZWFzZRiAgICgsdyLCgwLEgZVcGxvYWQYgICAoK3hngoM)

### Changes

  - Significantly improved tool paths, much better printed parts
  - Improved macro support
  - Improved baby stepping
  - Updated to latest avrdude for improved compatibility with some
    non-standard boards
  - Improved support for network printing
  - Touch screen mode now works on all platforms
  - New printing screen in touch screen mode
  - Better screen position saving and restoring

#### New translations added

  - Čeština
  - Dansk
  - Italiano
  - ελληνικά
  - Norsk
  - Русский
  - Română
  - Vlaams

#### Updated existing translations

  - English
  - Deutsch
  - Español
  - Français
  - Polski
  - Türkçe

### Bug Fixes

  - Increased hardware error reporting
  - Improvements to Repetier communications

## 1.6.2

**Release Date:** January 18, 2017

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgIDM446ECgwLEgZVcGxvYWQYgICA3O2njgoM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgIDQ7biQCgwLEgZVcGxvYWQYgICAsIyyiAoM)
  - [Linux
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyQQsSB1Byb2plY3QYgICAiOCSzAsMCxINUHVibGljUmVsZWFzZRiAgICgpIGdCgwLEgZVcGxvYWQYgICAoKL6nwoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.6.2b)

### Changes

  - All printing instructions now sent with checksum
  - Improved macro scripting and macro execution
  - Disconnect and Reconnect does not cancel a print (can still be
    recovered)
  - Improvements to language for dialogs and menus
  - Record recover count in history
  - Added error messages when saving files fails

### Bug Fixes

  - Fixed a problem with controlling multiple extruders that shared temp
  - Fixed problem when changing colors on some dialogs
  - Improved Android stability
      - Switched from HTTP client to WebRequest
      - Improved Queue logic to be more MVC and eliminated crash

## 1.6.1

**Release Date:** December 6, 2016

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgICMtpiFCgwLEgZVcGxvYWQYgICAzKTWkAsM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgIDQ4bmcCgwLEgZVcGxvYWQYgICA0KXYjQoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.6.1)

### Changes

  - Request updated printer list from MatterHackers.com immediately on
    program startup.
  - Show import printer Wizard after user logs in for the first time
    after updating.

## 1.6

**Release Date:** November 21, 2016

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgIC03baCCgwLEgZVcGxvYWQYgICAjIDRlAkM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgIDQsvmSCgwLEgZVcGxvYWQYgICA0K6XjwoM)
  - [Linux
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyQQsSB1Byb2plY3QYgICAiOCSzAsMCxINUHVibGljUmVsZWFzZRiAgIDA0_6ACgwLEgZVcGxvYWQYgICAwJ_IhQoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.6.0)

### New Features

  - Print Recovery
      - Automatically recover from power failure, disconnection, or
        crash
  - Printer settings now associated with user account and accessed when
    logged in
  - Settings changes automatically synced across instances of the
    application
  - Improved Settings Editor
      - Revert to default profile settings at any time
      - Revert to previous version of settings
  - Improved Quality and Material Editors
  - Improved Export and Import of settings
  - Printer profiles added
  - Calculate filament cost per print
  - Part editing now has undo and redo
  - Latest settings now retrieved the when setting up a new printer

### Better Print Results

  - Fill Thin Gaps
  - Expand Thin Edges
  - Perimeter Merging
  - Improved wipe towers
  - Improved support detection and removal
  - Improved seam hiding
  - Convex priming (skirt) loops
  - Better fan speed control
  - Can use G0 instead of G1 for moves if desired

## 1.5.3

**Release Date:** May 19, 2016

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgICEyriCCgwLEgZVcGxvYWQYgICAhP_3kQoM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgICQyMOUCgwLEgZVcGxvYWQYgICAkMz3ngoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/tree/1.5.3)

### New Features

  - Added profile for the BCN3D Sigma printer
  - Updated JumpStart V1 Printer Profile
  - Added printer profile for the Lulzbot TAZ 6

## 1.5.2

**Release Date:** April 29, 2016

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgIC43e2YCQwLEgZVcGxvYWQYgICA-PnGhwoM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgIDgs8GOCgwLEgZVcGxvYWQYgICA4K-MnwoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.5.2)

### Bug Fixes

  - Fixed Android keyboard crash on T10 tablet

### Other

  - Updated printer profiles

## 1.5

**Release Date:** February 19, 2016

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgICY8MOJCgwLEgZVcGxvYWQYgICA2JzcngkM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgIDgqs2MCgwLEgZVcGxvYWQYgICA4I74jwoM)
  - [Linux
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyQQsSB1Byb2plY3QYgICAiOCSzAsMCxINUHVibGljUmVsZWFzZRiAgIDA-PaGCgwLEgZVcGxvYWQYgICAwPi9jgoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.5.0)

### New Features

  - A new, vastly improved, [support
    system](settings/general/support-material)
  - [Position tuning while printing (aka baby
    stepping)](controls/movement#Axis_Motion_Buttons)
  - Ability to slice merged/intersecting parts
  - Improved seam-hiding while printing
  - Ability to cancel printing while heating
  - [Setting to retract when changing
    islands](settings/filament/filament/retraction/retract-when-changing-islands)
  - Made it possible to have the first perimeter have a different
    extrusion width to compensate for more accurate small holes
  - Added top infill speed
  - Add support for closing MatterControl while printing
  - Put in reporting of hardware errors
  - Improved the local search feature
  - Added visual indicator for http failures
  - Made it possible to render [translucent extrusion
    paths](layer-view#Transparent)
  - Support drag and drop onto the settings widget will still add to
    [Queue](queue)
  - Fixed the [macro window](controls/macros) to grow in Y
  - Implemented scroll wheel in the [G-Code
    Terminal](options/g-code-terminal)
  - Added user configurable [Library](library) folders
  - Finished Braille 2 functionality for [Braille
    Builder](braille-builder)
  - Velocity during rotation of [3D View](3d-view)
  - Improved MatterControl Touch printing
  - Improved Android soft keyboard support
  - Only process the most outside perimeter with [Spiral
    Vase](settings/general/layers-surface/outer-surface---perimeters/spiral-vase)
  - Fixed slicing to handle badly wound polygons

### Bug Fixes

  - Now reporting bed and extruder heating state for Repetier firmware
  - You can now type a partial entry to a count or mm field and not have
    it get messed up if you are slow
  - Make sure we turn off all heaters when we shut down
  - Ability to save to the Queue on [Save
    As](3d-view/edit#Save_As)
  - Suppress error reporting and abort on COM Access Denied errors
  - AMF save progress reporting
  - Fixed first layer speed issue
  - Better thread safety
  - Made the leveling page easier to use on MatterControl Touch
  - Made message box easier to use on MatterControl Touch
  - Allow invalid image file formats to return a load failure rather
    than throw an assert
  - Group objects move correctly on the bed when scaled
  - Made it possible to edit the 3 point leveling positions even after
    you have set up 7 or 13 point leveling
  - Making the save feature always go through a separate file so that we
    don't get collisions with files in use
  - No crashing on corrupt zip files
  - Fixed bug when opening and closing EEProm window
  - Restore Clear Cache functionality
  - Loading large GCode file no longer pauses Android
  - Loading Repetier EEProm settings no longer pauses Android
  - Fixed issue where [Infill
    Overlap](settings/general/infill/advanced/infill-overlap)
    was not being used correctly

### See also

[MatterControl 1.5
Released](https://www.matterhackers.com/news/mattercontrol-1-5-released)
article on MatterHackers.com

## 1.4.1

**Release Date:** November 16, 2015

Notes: [MatterControl Touch](mattercontrol-touch) only

### Minor Changes

  - Enabled new seam hiding code in MatterSlice
  - Enabled 'Pinch to Zoom' on touchscreens
  - Reset view button on model and gcode views
  - Improved STL repair, added handling for bad polygon winding
  - Added Outside perimeter extrusion width setting (Filament -\>
    Extrusion)
  - Added Top Solid Infill speed to MatterSlice
  - Improved to Braille Grade 2 support in Braille Builder
  - Made print leveling dialog easier to use on Touch
  - Made message reports easier to read on Touch

### Bug Fixes

  - Improved showing and hiding of the Android keyboard
  - Better startup behavior when a printer plugged in
  - Fixed issue where grouped objects were not moving when scaled
  - Android now resets boards on connect
  - Fixed issue where Infill Overlap was not being used correctly
  - Fixed issue with empty Start GCode
  - General stability improvements

## 1.4.0

**Release Date:** October 5, 2015

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgICI-uWHCgwLEgZVcGxvYWQYgICAiJmliwoM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgICgjoKDCgwLEgZVcGxvYWQYgICAoMn-kwoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.4.0)

### New Features

  - Added Cloud Design Library - automatic design file syncing
  - Expanded general library management tools (folder creation, item
    rename)
  - Added options for sharing designs
  - Added support for X3G 3D printers (added new profiles)
  - Added ability to start/stop prints remotely and remotely add items
    to queue
  - Added 'Braille Builder' design add-on for creation of 3d printable
    braille labels

## 1.3.0

**Release Date:** June 23, 2015

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgICwgO6SCgwLEgZVcGxvYWQYgICAsLiahQoM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgIDA58SYCgwLEgZVcGxvYWQYgICAoOC5ngoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.3.0)

### New Features

  - Auto arrange has been improved
  - Added profiles for MakerGear, PrintSpace, Huxley
  - Adding Touchscreen mode for touchscreen devices
  - Support for ATX power hardware
  - Improved Basic and Standard UI settings
  - Perimeters, Bottom and Top layers can all be set in millimeters
  - Perimeters can now be printed outer layer first or last

### Minor Changes

  - Updated Lulzbot settings
  - Added tool change g-code
  - Added crash reporting to alpha and beta channels
  - Better default printer naming
  - Fixed slicing problems with very complex models during top and
    bottom layer creation.

### Bug Fixes

  - Fixed issue with spiral vase setting
  - Fixed bug with dual extrusion offset (offset values were limited to
    integer values)
  - Fixed slicing problems with very complex models during top and
    bottom layer creation
  - Improved reset connection
  - Keep 3D views up to date with model changes
  - Fix to end gcode processing not doing replacements
  - Improved error messages
  - Fixed handling of bad AMF loading
  - Better handling of connection not available
  - Fixed a bug in the queue while printing and trying to change items1
  - Fixes for international number formatting
  - Improved clarity of redundant slice settings naming
  - Fixed a problem with first layer extrusion width

### MatterSlice

#### Features

  - Added a wipe before retract feature
  - Made it possible to print the raft with any extruder

#### Bug Fixes

  - Filter move writes better
  - Spiral Vase now ignores confounding settings when set
  - Outer perimeters can no longer overlap themselves
  - Improved loop clipping
  - Put in tool change code
  - Print the skirt before the raft
  - Hex infill could sometimes miss a bottom edge
  - Fixed a freeze bug when creating top and bottom layers for complex
    parts
  - Make sure we retract on layer change if required
  - Extruder offset previously could only be an integer value (it can
    now be a decimal value as well)

## 1.2.2

**Release Date:** March 6, 2015

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgIDg7O2cCQwLEgZVcGxvYWQYgICA4IO_lgoM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgIDAjJCPCwwLEgZVcGxvYWQYgICAwN74kAoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.2.2)

### New Features

  - Improved printer connection stability
  - Updated Serial Driver for RAMPS
  - Added profiles for Revolution 3D, Solidoodle
  - Added hexagon infill
  - Added the ability to turn on 'Reset Connection' works as an e-stop

### Minor Changes

  - Bug fixes
  - Better memory reporting and stability
  - Fixed a bug with temp being set repeatedly
  - Using sub-modules (easier to build from GitHub)

## 1.2.1

**Release Date:** January 28, 2015

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgICgkqidCgwLEgZVcGxvYWQYgICA4KyQhgoM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgICA26OTCgwLEgZVcGxvYWQYgICAwPTHlgoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.2.1)

### New Features

  - Pop Out Windows - now you can show settings and controls all the
    time
  - Ability to send parts to other computers and MatterControl Touch
  - We now display a big 3D view on startup
  - Better connection handling
  - Support for many more printers
  - Added a Simple mode to slice settings

### Minor Changes

  - External Perimeter First slice setting
  - Improved edge detection during slicing
  - Select Raft Extruder
  - Vertical offsets in edit mode
  - Faster editing of models
  - More accurate gcode generation
  - More accurate support angles
  - Better slice settings help and defaults
  - Fixed some very obscure errors with Print Leveling being too high
    sometimes
  - Better detection of co-linear edges (highly tessellated round things
    work better)

## 1.2

**Release Date:** November 19, 2014

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgICg3KGHCQwLEgZVcGxvYWQYgICAoOLjlQoM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgICAy6-BCgwLEgZVcGxvYWQYgICAgNvunQoM)

### New Features

  - Dual-Extrusion Support
  - Simple Multi-Material Workflow
  - Advanced Support Material Generation
  - New Touch-Friendly UI
  - Signed Windows Drivers (no more Windows 8 pain)
  - AMF support

### Minor Changes

  - Improved Pausing (remembers and returns to pause position)
  - Support for @pause and M226 (user requested pause from gcode)
  - MatterSlice
      - Skirt always draws from the outside

## 1.1.3

**Release Date:** August 8, 2014

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgIDAxOeTCgwLEgZVcGxvYWQYgICAwMnShQoM)
    - last XP compatible build
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgICA1pSNCgwLEgZVcGxvYWQYgICAgLG7igoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.1.3)

### New Features

  - Updated to Slic3r 1.1.7
  - MatterSlice significantly improved
      - Support can now have interface layers
      - Many bugs and performance improvements
  - New 3D Display options (outline view)
  - MakerBot X3G support now available (beta)
  - Added Turkish translation

### Minor Changes:

  - Make sure the 3D views always match the current printer size and
    shape
  - Improved 3D GCode view (more display options)
  - Faster Mesh and GCode loading
  - New driver for RoBo 3D
  - Made Smoothieboards work better

## 1.1.2

**Release Date:** July 22, 2014

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgICA49WLCgwLEgZVcGxvYWQYgICAwKi2gwkM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgICAotGHCgwLEgZVcGxvYWQYgICAgKaJlQoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.1.2)

### New Features

  - 3D GCode View
  - Cloud Monitoring: While logged in, printer status viewable from the
    web
  - SD Card Support: Allows you to print from and view/edit the contents
    of the on-board SD Card
  - Triangle infill in MatterSlice, for incredibly strong parts

### Minor Changes

  - Minor UI fixes (ex. added scroll bars to slice presets)
  - Added 'Preheat' temperature preset - sets temp to current slice
    settings
  - Fixed slice implementation of Raft settings. It was not putting in
    correct spacing
  - Fixed issue with update download not starting.
  - Fixed issue with auto-connect causing start-up crash (on
    Printrboards specifically)

## 1.1.1

**Release Date:** May 27, 2014

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgICApamKCgwLEgZVcGxvYWQYgICAgMOGmwsM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgICA7KuBCgwLEgZVcGxvYWQYgICAgMKTnAoM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.1.1)

### New Features

  - New Advanced Raft in MatterSlice
  - GCode playback during printing

### Minor Changes

  - Independent Axis Scaling Improved
  - Fixed a bug in Macros being sent in reverse order
  - Better international support (
  - Bug fixes and performance improvements

## 1.1.0

**Release Date:** May 14, 2014

  - [Windows
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY6gcMCxINUHVibGljUmVsZWFzZRiAgICA-YaUCQwLEgZVcGxvYWQYgICAgKX4nQkM)
  - [Mac
    Download](https://mattercontrol.appspot.com/downloads/development/ag9zfm1hdHRlcmNvbnRyb2xyOwsSB1Byb2plY3QY7AcMCxINUHVibGljUmVsZWFzZRiAgICArNeKCgwLEgZVcGxvYWQYgICAgOz6lwsM)
  - [Source
    Code](https://github.com/MatterHackers/MatterControl/releases/tag/Releases%2F1.1.0)

### New Features

  - MatterSlice : A new high quality, high speed slicing engine by
    MatterHackers
  - Material/Quality Presets : Layers settings to that modify the base
    settings
  - Widescreen Mode
  - Expanded Themes
  - Image Converter : A new tool that lets you change images into
    printable models
  - Print History updates and improvements

### Minor Changes

  - Pause, cancel, resume functionality can now be assigned custom
    GCode.
  - Added visualization for retraction and partial path viewing to GCode
    view.
  - When parts are repositioned in the plate editor, the offsets are now
    preserved.
  - Localization support has been added. We'll be integrating
    translations as they become available.
  - Saving part file edits is now significantly faster.
      - Loading images is now faster (uses caching).
      - Many bug fixes and performance improvements

[Category:General Information](category:general-information)
[Category:Development](category:development)

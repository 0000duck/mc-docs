The 3D Printer Setup Wizard guides the user through the
process of configuring a printer profile for use with a 3D printer in
MatterControl.

## First screen

![3D\_Printer\_Setup\_Wizard1.png](http://wiki.mattercontrol.com/images/8/87/3D_Printer_Setup_Wizard1.png
"3D_Printer_Setup_Wizard1.png")The first screen of the wizard allows the
user to select an existing pre-configured profile.

### Make

The list of 3D printer manufacturers for which profiles are available.

### Model

The list of models available from the currently-selected Make.

### Name

A field in which the user can specify a custom name for the printer in
the current instance of MatterControl. The Make and Model populate this
field by default.

### Save & Continue

This button will appear when valid selections and entries have been
made. Clicking will create the new printer configuration, and if
MatterControl is signed in to a [MatterHackers.com
account](matterhackers.com-account.md), will associate the
configuration with the account.

### Cancel

Exits the wizard without creating a new printer configuration.

  

## Install Communication Driver

![3D\_Printer\_Setup\_Wizard2.png](http://wiki.mattercontrol.com/images/9/94/3D_Printer_Setup_Wizard2.png
"3D_Printer_Setup_Wizard2.png")If running the Windows version of
MatterControl, the next step is to install drivers so MatterControl can
communicate with the printer. On Mac, Linux, and Android this step is
not shown.

MatterControl will launch a separate installer (Infinstaller.exe) which
may require administrative permissions.

### Install Driver

Launches Infinstaller.exe and installs the drivers.

### Skip

Proceed to the next step without installing drivers.

### Cancel

Exits the wizard without connecting to the printer.

  

## Printer Connection

![3D\_Printer\_Setup\_Wizard3.png](http://wiki.mattercontrol.com/images/5/56/3D_Printer_Setup_Wizard3.png
"3D_Printer_Setup_Wizard3.png")In this step MatterControl will attempt
to connect to the printer. Follow the instructions and click the
applicable button.

### Manually Configure Connection / Manual Configuration

Proceed to the **[Serial Ports](#Serial_Ports)** screen.

### Skip Connection Setup

Exits the wizard without connecting to the printer.

### Continue

Proceed to the next step in the connection process.

![3D\_Printer\_Setup\_Wizard4.png](http://wiki.mattercontrol.com/images/4/4f/3D_Printer_Setup_Wizard4.png
"3D_Printer_Setup_Wizard4.png")

  

## Serial Ports

![3D\_Printer\_Setup\_Wizard5.png](http://wiki.mattercontrol.com/images/3/30/3D_Printer_Setup_Wizard5.png
"3D_Printer_Setup_Wizard5.png")Clicking on Manually Configure Connection
will lead to the Serial Port selection screen. Choose

### Troubleshooting

If the connection fails even when set to the correct serial port, you
can click the 'Cancel' button and try a different [Baud
Rate](settings/printer/connection/details/baud-rate).

  

## Success

When MatterControl successfully connects to the printer, the wizard will
automatically close.

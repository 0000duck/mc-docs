![G-Code_Terminal.png](http://wiki.mattercontrol.com/images/3/35/432x429xG-Code_Terminal.png.pagespeed.ic.c3R1r7B4v1.png "G-Code_Terminal.png")
The **G-Code Terminal** window, shown here after establishing a
connection to a Rostock MAX V2.

The **G-Code Terminal** is a console window which shows input and
output and can be used to directly issue [G-Code
commands](http://reprap.org/wiki/G-code) to a connected printer.

It is accessed by clicking the ![Show\_Terminal.png](http://wiki.mattercontrol.com/images/b/b3/Show_Terminal.png
"Show_Terminal.png") icon in the **Options** menu under **Hardware**.

## Filter Output

If checked, this function filters the text of the Readout Display of any
automatically updated temperature output. Lines beginning with the
following are omitted from display:

  - \<-wait
  - \<-ok
  - \-\>M105
  - \<-T

Note: The `M105` command and any response will be filtered even if the
command is entered manually. To see this, uncheck **Filter Output**.

## Auto Uppercase

If checked, this function automatically capitalizes any text entered in
the Input Field before it is sent to the printer.

Typically, printers only accept uppercase G-Code, so this can be useful
if the user does not wish to type in caps or by using the shift key.

Note: Text still appears as lowercase in the Input Field; the
capitalization occurs after the user sends the command but before it is
sent to the printer.

## Readout Display

The main part of the G-Code Terminal window is the large area in the
middle where the input and output to and from the printer can be seen.
This area scrolls down automatically as new text appears at the bottom,
and previous text can be accessed by manually scrolling with the scroll
bar on the right side.

In the example to the right, the **Readout Display** shows several lines
of communication between MatterControl and the Rostock MAX V2 printer
upon connection.

### \-\>

The **-\>** symbol at the beginning of a line indicates that the line is
being sent from MatterControl to the printer.

### \<-

The **\<-** symbol at the beginning of a line indicates that the line is
output from the printer.

## Input Field

A text input field in which the user enters G-Code commands to be sent
to the printer. You can press the up arrow key to repeat the last
command that was typed in.

## Send

This button sends any text in the Input Field to the printer.

## Clear

This button clears the Readout Display of any text.

## Export...

This button opens the operating system's file save window so the user
can save a text file of the entire contents of the Readout Display.

This function can be useful for troubleshooting, and is commonly
requested by MatterControl tech support.

## Close

This button closes the window.

[Category:Features](category:features)

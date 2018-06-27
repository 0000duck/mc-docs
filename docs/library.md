\[\[[File:Library.png|right|frame](File:Library.png%7Cright%7Cframe)|

<center>

The **Library** pane, when a MatterHackers account is [signed
in](sign-in.md), has [purchased models](#Purchased),
and [models shared from another
user](file-menu.md#Enter_Share_Code).

</center>

\]\]The Library is a place for organizing and storing models. It has
five sections; three static and two dynamic.

The **Local Library**, **Cloud Library**, and **Downloads** sections are
always visible. The **Purchased** and **Shared with Me** sections are
shown only when they contain models.

In most sections, models can be organized using a traditional folder
structure.
\_\_TOC\_\_

## Sections

### <span class="mw-headline" id="Local_Library">![Local\_Library.png](http://wiki.mattercontrol.com/images/7/79/Local_Library.png "Local_Library.png")</span>

Stores designs in the local file system. Any designs in the Library
prior to MatterControl 1.4 are put here after the
upgrade.

### <span class="mw-headline" id="Cloud_Library">![Cloud\_Library.png](http://wiki.mattercontrol.com/images/3/3f/Cloud_Library.png "Cloud_Library.png")</span>

The **Cloud Library** allows instant access to design files through
MatterControl from anywhere with an Internet connection. Designs stored
in the Cloud Library are tied to a [MatterHackers.com
account](matterhackers.com-account.md). Once signed in the user
can browse and manage any design files previously added and add new
files.

Designs within the Cloud Library are synced automatically across any
devices the user is currently logged into and can also be viewed from
the [MatterControl Sync](https://sync.mattercontrol.com/) website.

For more information on the Cloud Library check out [the MatterControl
wiki page for CLOUD SYNC](cloud.md#File_Sharing) and [In Depth:
MatterControl Cloud Library for
Designs](http://www.matterhackers.com/articles/in-depth-mattercontrol-cloud-library).

### <span class="mw-headline" id="Purchased">![Purchased.png](http://wiki.mattercontrol.com/images/9/9f/Purchased.png "Purchased.png")</span>

Automatically contains any designs purchased from the [MatterHackers
Design
Store](http://www.matterhackers.com/store/digital-designs).

### <span class="mw-headline" id="Shared with Me">![Shared\_with\_Me.png](http://wiki.mattercontrol.com/images/d/d8/Shared_with_Me.png "Shared_with_Me.png")</span>

Contains any models shared from other users using the [Share Library
Item](library/share-library-item) function in the Cloud
Library
section.

### <span class="mw-headline" id="Downloads">![Downloads.png](http://wiki.mattercontrol.com/images/a/a1/Downloads.png "Downloads.png")</span>

Gives direct access to the Downloads folder on the hard drive
`~/Downloads` on Linux/Mac or `C:\Users\{user}\Downloads` on Windows).
Any STL, AMF, or GCODE files in that folder will automatically appear
here. Any changes made to these designs in MatterControl will be saved
to disk as an AMF file. Depending on the original file type, this will
either create a new AMF with the same name but with a different file
extension, or replace the existing AMF file.

## Navigation

### Top Level

To open a section, hover over the section and click the **Open** button
at the right side.

![Open\_Library.png](http://wiki.mattercontrol.com/images/7/78/Open_Library.png "Open_Library.png")

### In a section

\[\[<File:Library> In section.png|right|framed|

<center>

The **Local Library** section with **Home**, **Search**, **Edit**,
**Add** and **Create Folder** buttons active.

</center>

\]\]Once in a section, a breadcrumb trail shows the current location
within each section, subsequent folders, or search results.

![Library\_Breadcrumb.png](http://wiki.mattercontrol.com/images/6/6f/Library_Breadcrumb.png
"Library_Breadcrumb.png")

Models can be viewed or printed directly by hovering over their bar in
the list. The **View** button opens the model in a new [3D
View](3d-view.md) window. The **Print** button slices the model
using the current [Settings](settings) and begins the print.

![Library\_View\_Print.png](http://wiki.mattercontrol.com/images/8/8f/Library_View_Print.png
"Library_View_Print.png")

Also, some new buttons become visible: **Home**, **Search**, and
**Edit**, and two become active: **Add** and **Create Folder**.

### Add

![Add\_Library.png](http://wiki.mattercontrol.com/images/9/92/Add_Library.png "Add_Library.png")

Opens the operating system's file selection window so the user can
choose a .STL, .AMF, .GCODE, or .ZIP file to add to the currently
displayed section.

Not available in the [Purchased](#Purchased) or [Shared with
Me](#Shared_with_Me) sections.

### Create Folder

![Create\_Folder\_Library.png](http://wiki.mattercontrol.com/images/0/09/Create_Folder_Library.png
"Create_Folder_Library.png")

Creates a folder in the currently displayed section.

Not available in the [Purchased](#Purchased) or [Shared with
Me](#Shared_with_Me) sections.

### Home

Returns to the top level of the Library, as shown in the [screenshot at
the top right of this page](:file:library.png).

### Search

Searches the currently displayed section for the text input in the
'Search Library' field.

### Edit

\[\[[File:Edit1.png|right|framed](File:Edit1.png%7Cright%7Cframed)|

<center>

The **Local Library** section in **Edit** mode.\]\]

Shows advanced file and folder options. Check a box next to a file or
folder to activate applicable file action buttons above.

Not available in the [Purchased](#Purchased) or [Shared with
Me](#Shared_with_Me) sections.

#### Export

Opens the [File export options](file-export-options.md) dialog
box to export the currently selected file.

Active when only one file is selected.

#### Edit

Opens the selected file in a new 3D View window in [Edit
mode](3d-view/edit).

Active when only one file is selected.

#### Remove

Removes the selected file(s) from the current Library section.

Active when one or more files are selected.

#### Share

Opens the [Share Library Item](library/share-library-item)
dialog box.

Available only in the [Cloud Library](#Cloud_Library)
section.

Active when only one file is selected.

#### Rename

![Rename\_Item\_box.png](http://wiki.mattercontrol.com/images/4/41/Rename_Item_box.png "Rename_Item_box.png")

Opens the **Rename Item** dialog box. Enter a new name for the model and
click 'Rename' to apply.

Active when only one file is selected.

#### Add to Queue

Adds the selected file(s) to the [Queue](queue.md).

Active when one or more files are selected.

#### Done

Exits **Edit** mode.

## Adding custom folders from your hard drive

The library can be set up to track any folder on your hard drive the
same way it does with the [Downloads](library.md#Downloads)
folder. To do this, create a file called  in the MatterControl
[application data directory](data-directory.md). Add the full
path to the folders you want to track on separate lines. Here is an
example:

[Category:Features](category:features)

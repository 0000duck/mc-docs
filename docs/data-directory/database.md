MatterControl keeps all internal settings in an SQLite database in the
[application data
folder](frequently-asked-questions#How_do_I_clear_the_application_data.3F).
On Windows this is at . On Linux and Mac it is at .

You can edit the database file using a program like [SQLite
Browser](http://sqlitebrowser.org/) or [SQLite Manager for
Firefox](https://addons.mozilla.org/en-US/firefox/addon/sqlite-manager/).

## Database Structure

Here is a brief description of the tables in the database and what they
are used for

### ApplicationSession

This is a log of each time the MatterControl application is started and
stopped.

### CustomCommands

**Unused in version 1.6 or later**. This used to store the [G-Code
Macros](http://wiki.mattercontrol.com/controls/macros).

### PrintItem

Contains items that can be found in the [Local
Library](http://wiki.mattercontrol.com/library) and the
[Print History](http://wiki.mattercontrol.com/history). Does
not contain items from the [Queue](queue), Cloud Library, or
your Downloads folder.

### PrintItemCollection

List of folders in the [Local
Library](http://wiki.mattercontrol.com/library).

### PrintTask

This is the log of all prints that have been performed. The last 20 of
these are shown in the [History](history).

### Printer

**Unused in version 1.6 or later**. This contained the list of printers,
with their name, make/model, communication settings, and [Software Print
Leveling](options/software-print-leveling) data. Printers are
now stored as individual .printer files (JSON) in Profiles folder.

### PrinterSettings

**Unused**

### SliceSettings

**Unused in version 1.6 or later**. This contained the values of all
[slice settings](settings) for all printers and
[presets](settings#Preset_Menus). All settings have now been
moved to .printer files.

### SliceSettingsCollection

**Unused in version 1.6 or later**. This was a list of
[presets](settings#Preset_Menus) and baseline profiles, and
mappings to their associated SliceSettings.

### SystemSetting

Internal state of the application.

### UserSetting

Internal state of the application.

### sqlite\_sequence

Database status.

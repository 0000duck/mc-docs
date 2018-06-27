MatterControl uses a file-based localization system for translating the
software into other languages.

## Access the most up-to-date files

Before you begin, make sure you get the most current code:

1.  You need access to the 'Master.txt' file that is on the 'Master'
    branch of our source code.
2.  You can do so by going to our
    [MatterHackers/MatterControl](https://github.com/MatterHackers/MatterControl)
    GitHub repository, switching to the *master* branch, clicking on the
    **StaticData/Translations** folder and clicking on the *Master.txt*
    file.
3.  Alternatively, you can access this file by clicking on the following
    link:
      -   
        <https://github.com/MatterHackers/MatterControl/blob/master/StaticData/Translations/Master.txt>

## Create a new translation

For languages that do not currently have translations, follow these
instructions:

1.  Install the latest version and find the 'Translations' folder in the
    installed location.
      -   
        On PC this is typically `C:\Program Files
        (x86)\MatterControl\StaticData\Translations`
        On Mac, right click the application, select Show Package
        Contents, go to `Contents\MonoBundle\StaticData\Translations`
2.  Locate the 'Master.txt' file, create a working copy in a separate
    location.
3.  The 'Translation.txt' file contains all translatable strings within
    MatterControl in the following format:
      -   
        English: **Add a file to be printed**
        Translated: **Add a file to be printed**
4.  Replace the 'Translated' line with the appropriate translation:
      -   
        English: **Add a file to be printed**
        Translated: **Agregar archivo a ser impreso**
5.  Test the translated file by saving over an existing translation file
    (ex. `\StaticData\Translations\es\Translation.txt`
6.  Email the translated file to support@matterhackers.com for inclusion
    in the next release.

## Edit an existing translation

For languages which already have translations but need corrections,
follow these instructions:

1.  Install the latest version and find the 'Translations' folder in the
    installed location.
      -   
        On PC this is typically `C:\Program Files
        (x86)\MatterControl\StaticData\Translations`
        On Mac, right click the application, select Show Package
        Contents, go to `Contents\MonoBundle\StaticData\Translations`
2.  Locate the 'Translation.txt' file within the appropriate folder
    (folder names use
    [ISO 2-Digit](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
    codes).
3.  The 'Master.txt' file contains all translatable strings within
    MatterControl in the following format:
      -   
        English: **Add a file to be printed**
        Translated: **Add a file to be printed**
4.  Replace the 'Translated' line with the appropriate translation:
      -   
        English: **Add a file to be printed**
        Translated: **Agregar archivo a ser impreso**
5.  Test the translated file by saving over an existing translation file
    (ex. `\StaticData\Translations\es\Translation.txt`
6.  Email the translated file to support@matterhackers.com for inclusion
    in the next release.

[Category:Development](category:development)

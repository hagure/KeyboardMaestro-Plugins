KeyboardMaestro-Plugins
=======================

Plugins for Keyboard Maestro (Tested with KM6 on OSX 10.8).

## Prepend Text

Adds "Prepend Text to File" functionality to supplement the built-in "Append Text" action. 

Enter the text you want to prepend in the "Text:" field (accepts variables), and in the "to file:" field, enter the unix path of the file you want to prepend to. The path will be quoted so you don't have to worry about escaping characters.

The prepend is accomplished through a "do shell script" command in applescript, taken from [here](http://onethingwell.org/post/1198458118/osx-prepend).

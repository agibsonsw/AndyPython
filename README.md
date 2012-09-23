AndyPython
==========

Python completions and help

Includes completions for the ST-API if "import/from sublime" is within 
the current file.

The help system is simple but still useful. It will provide help on many standard 
functions or methods in a quick panel.
Add a key-binding such as:

{ "keys": ["shift+f1"], "command": "py_help" }

then click into a function or method and press Shift-F1. If help is not 
located, this is confirmed in the status bar.
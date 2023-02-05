# FreeCAD CNC postprocessor for metalab CNC

[Metalab CNC](https://metalab.at/wiki/CNC-Fr%C3%A4se) doesn't work with the default LinuxCNC GCode FreeCAD generates. This is a postprocessor to adapt it.

## Installation

1. copy (or better: symlink) `linuxcnc_metalab_post.py` to
  * linux: `/usr/lib/freecad/Mod/Path/PathScripts/post/`
  * windows: ?
  * mac: ?
2. Job / Output / Processor: select `linuxcnc_metalab`
3. generate GCode like normal

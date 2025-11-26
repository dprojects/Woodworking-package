Installation package with FreeCAD kernel and Woodworking workbench to keep Woodworking workbench working forever.

# Why

The fundamental problem with open-source software is that it usually does not work out of the box. Some adjustments are usually required to get it working. If the software depends on other software, the problem is even more visible, especially if a given library or dependent product is still under heavy development.

Woodworking workbench is a product built on the top of FreeCAD kernel and use it as library, but FreeCAD is constantly modified by an unidentified group with undefined goals.

For this reason, an installation package was created to lock in a compatible and tested version of the FreeCAD kernel and prevent external "breaking" of Woodworking workbench, either intentionally and through grant funding by "paid programs," or accidentally by incompetent pseudo-programmers and keep Woodworking workbench working forever.

# How it works

This AppImage will copy the [Woodworking workbench](https://github.com/dprojects/Woodworking) into `~/.local/share/FreeCAD/Mod` folder, will run the tested FreeCAD kernel, and set the Woodworking workbench environment. So you will be able to update later the Woodworking workbench via [debugInfo](https://github.com/dprojects/Woodworking/tree/master/Docs#debuginfo) tool.


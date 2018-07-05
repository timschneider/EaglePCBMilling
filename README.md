# EaglePCBMilling
This repository is ment to provide for a DIN66025 cnc ulp script within a very user friendly interface.

The user interface is oriented to process creation/execution. This allow users to create different process to the same machine, for example a fast milling and another complete rubout or even one that uses interpolation to make holes while the other uses pre-selected tools.

A big improvement creating and saving a process is that later will be possible to run those processes faster, without configuring all over again.
Future versions will support diferent output files and the idea is to use some Eagle layers as viewer.

It is a modified version of the original mill-outlines.ulp shipped with pcb eagle, currently in version 9.0.1.

# How to use
*Attention, this software still being implemented, this version is not considered released nether stable*

if you run export-monofab ulp it will open the wizard. So far it still not connected to the mill-outlines, but improvements to the interface are welcome.

# Disclaimer

This software is provided **AS IS**, **always** *simluate the generated g-code prior use on a real mill!*  

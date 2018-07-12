# Machine-it

Machine it is a new ulp.
This ulp will be used as an universal open source machine path creator to mill PCBs.

The user interface is oriented to process creation/execution. This allow users to create different process to the same machine, for example a fast milling and another complete rubout or even one that uses interpolation to make holes while the other uses pre-selected tools.

A big improvement creating and saving a process is that later will be possible to run those processes faster, without configuring all over again.
Future versions will support diferent output files and the idea is to use some Eagle layers as viewer.

It's repository cames originaly from EaglePCBMilling

# How to use
*Attention, this software still being implemented, this version is not considered released nether stable*
Right now the software is under development, you are welcome to send suggestions.
I've made a small user interface and that's it.
This branch still not calling any core to generate files, it only configures how the board should be milled, the user can save processes and edit them if he wants.

if you run machine-it ulp it will open the wizard. So far it still not connected to the mill-outlines, but improvements to the interface are welcome.

# Disclaimer
This software is provided **AS IS**, **always** *simluate the generated g-code prior use on a real mill!*  

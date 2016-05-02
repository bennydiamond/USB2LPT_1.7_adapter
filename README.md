USB2LPT rev 1.7 adapter board for Geeetech CY7C68013A development board

### Intro ###

This repository contains the schematic, PCB layout and pre-generated Gerber files. 
Since this adapter board contains no logic, no software is offered. For more information on USB2LPT device and to download necessary software files, please consult the [original creator's website](https://www-user.tu-chemnitz.de/~heha/basteln/PC/USB2LPT/).

USB2LPT is a "true" LPT (parallel) port to USB converter. It remaps the legacy LPT address to the USB board. This enables usage of a parallel port interface on modern computers when the communicating program uses fixed addressing (378H and 278H) to read and write to the parallel port. The process is complicated and make uses of dynamic re-addressing features present in Windows Environment debugging; which makes communication really slow.

This is currently the best and most compatible solution to interface legacy devices on parallel ports if your computer doesn't possess such interface.

### Usage ###

This adapter board transform the Geeetech CY7C68013A board into a USB2LPT rev 1.7 device.

**Please note that the LCSoft variant microcontroller board is not supported as the pinout is slightly different. 
The Geeetech variant has the RESET pushbutton near the USB connector whereas the LCSoft is located on the other side of the PCB.**

Geeetech variant:

![Geeetech_CY7C68013.jpg](https://bitbucket.org/repo/XkA6Mb/images/3584584708-Geeetech_CY7C68013.jpg)


LCSoft variant:

![Lcsoft-miniboard-front.jpg](https://bitbucket.org/repo/XkA6Mb/images/4114682664-Lcsoft-miniboard-front.jpg)

### Credits ###

USB2LPT original hardware design & software:
Henrik Haftmann
# LowKey36 by Matt Gilbert

This is the ZMK source repo for the LowKey36 spit keyboard.

## This is a prototype!

You can find the v1.2 KiCAD files in this repo, but keep in mind that this is a prototype, and while it is functional, it is not fully refined.

As this is a prototype, the files here have not been merged with the main repo for ZMK. That means that you must fork and clone this repo to your own account, and then use the firmware built from the automation. You can't use the standard ZMK setup to build the firmware for this board yet. When I've completed v2.0 of the PCB I will open a PR with ZMK to get this shield added to the included options.

This board is designed to be used with Nice!Nano controllers and Nice!View displays. The unique feature of this board is that it is designed for the Kailh PG1316S ultra low-profile key switch. These are surface-mounted switches that require special soldering to connect them to the PCB. I have included ZMK Studio support, but as of 2024-12-07 the board shows up in Studio, but it can't be edited.

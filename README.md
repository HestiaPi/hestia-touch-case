# HestiaPi Touch

![HestiaPi Touch](https://www.crowdsupply.com/img/a204/hestiapi-black-white-standing-2_jpg_project-main.jpg "HestiaPi Touch")

HestiaPi Touch is a completely open source smart thermostat for your home. With it, you can monitor your home’s temperature, relative humidity, and atmospheric pressure. You can also control your heating, ventilation, air conditioning, hot water, and more from anywhere you have an Internet connection. 

You can do all this securely and with confidence your private data stays private. 

HestiaPi Touch is compatible with many devices and home automation systems and can serve as a central point of control that ties them all together in your home.

# What are all these files?

TL;DR: Download Backplate_ONE.stl and the Cover_ONE stl which matches the power supply you have, adjust printer/filament settings, and print.

## File types

- FCStd: FreeCAD models of the case
- stl: Exported models in a standard format (STL)

## The printing process
Open a slicer like Cura or Prussa, open the STL and set all your print settings (temperature, infill, supports, and so forth).

After that you'll either press Print via USB or save the .gcode to an SD card and put it in your printer to print in standalone mode. If this is your first time printing something, I'd advise having someone experienced in 3D printing to help you along the process.

## Different editions
The US power supply (24V) is larger than the EU one and so the LCD screen rests directly on the power supply. As such, one of the LCD tabs had to be removed in order to avoid it from colliding with the airspace of the power supply.

The EU power supply (240V) is smaller and requires that third tab be there in order to keep the LCD in place.

# Update process
The process to update these models is to use FreeCAD to modify the model and make sure to update the version number. When done, export to STL. Commit all of these files to the git repo with an explanation of what changed in the commit message. Submit a merge request.

As long as the modified design will still fit with the other piece (e.g. your modified cover still fits the current backplate), the version number should go up by 0.01. If you are introducing an incompatibility, the version number should go up by 0.1. The only time the version number would change more than this if if it is a radical redesign.

# Compatibility
The current models (made in FreeCAD) are not a perfect match with the old ones (made in Onshape). The Onshape models never had a version number. The FreeCAD models got version numbers in 2025. Version numbers are engraved on the inside of the cover and the back of the backplate.

Anything with a version number where the first two digits match will be compatible. For example, the EU Cover v2.1 is compatible with the Backplate v2.11.

If you need a replacement and are not sure which model you have, the safest thing to do is to print a new backplate and cover with a known version number. Of course, you can also print out just the piece that you need and just see if it fits.

# Useful links

* [Main website](https://hestiapi.com/)
* [Documentation & Getting Started Guides](https://github.com/HestiaPi/hestia-touch-openhab/wiki)
* [Community forum](https://community.hestiapi.com/)
* [Code](https://github.com/HestiaPi/hestia-touch-openhab)
* [Electronics](https://github.com/HestiaPi/hestia-touch-pcb-dev)
* [3D Case (this repo)](https://github.com/HestiaPi/hestia-touch-case)

# Support us

HestiaPi is and will always be open source and open hardware. 

Please consider supporting us through our [crowdfunding campaign](https://www.crowdsupply.com/makeopenstuff/hestiapi-touch).

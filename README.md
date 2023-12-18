# HestiaPi Touch

![HestiaPi Touch](https://www.crowdsupply.com/img/a204/hestiapi-black-white-standing-2_jpg_project-main.jpg "HestiaPi Touch")

HestiaPi Touch is a completely open source smart thermostat for your home. With it, you can monitor your home’s temperature, relative humidity, and atmospheric pressure. You can also control your heating, ventilation, air conditioning, hot water, and more from anywhere you have an Internet connection. 

You can do all this securely and with confidence your private data stays private. 

HestiaPi Touch is compatible with many devices and home automation systems and can serve as a central point of control that ties them all together in your home.

# What are all these files?

TL;DR: Download BaseOneSnap2HNuts_v2.1.FCStd and CoverOneSnap2H-taller.stl, adjust printer/filament settings, and print.

## File types

- FCStd: FreeCAD models of the case
- stl: Exported models in a standard format (STL)

## The process
The process is to use FreeCAD to model the objects, then export to STL. After that, open a slicer like Cura, open the STL and set all your print settings (temperature, infill, supports, and so forth).

After that you'll either press Print via USB or save the .gcode to an SD card and put it in your printer to print in standalone mode. If this is your first time printing something, I'd advise having someone experienced in 3D printing to help you along the process.

## Different editions
For the most part, the different editions are just slightly different case designs that have evolved over time. You will only need two parts: the base and the cover.

All of the models must have matching base and covers. The attachment mechanisms and tolerances have changed from one version to the next, so be sure to get a matched pair.

- CoverOneSnap2H_v2.1: The newest model, a reproduction of the one of the same name, but it is easier to modify and now sports a version number
  - CoverOneSnap2H_v2.1-Clicky-US-24V: Modified to omit a tab that collides with the power converter
- CoverOneSnap2H: The model that shipped with the crowdfunding campaign and for many years afterwards. If the same electronics components were still available as were used in 2019, we'd probably still be using this model.
- All the rest: Old models that you likely do not want

The list above are just the covers. The base is the same filename except Cover is replaced with Base.

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

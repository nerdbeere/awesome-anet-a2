# Awesome Anet A2
 A list of useful resources for the Anet A2 3d Printer which I primarly write for myself so I don't forget these things.
 
 ## Printable Upgrade Parts
 - **[Adjustable Belt Tensioner](https://www.thingiverse.com/thing:1780636)**
 - **[Hexagon Mainboard Cover](https://www.thingiverse.com/thing:2013479)**
 - **[Fanduct with auto leveling sensor mount](https://www.thingiverse.com/thing:2057240)**
 
 ## Upgrade parts
 - Plastic wheel bearings for vslot: [Tevo](https://tevo3dprinterstore.com/products/tevo-cnc-openbuilds-plastic-wheel-pom-with-bearings-for-v-slot) / [openbuilds](http://openbuildspartstore.com/solid-v-wheel-kit/) / [openbuilds extreme](http://openbuildspartstore.com/xtreme-solid-v-wheel-kit/)
 - [Magnetic Levitated 40mm fan](https://www.conrad.de/de/axialluefter-12-vdc-1359-mh-l-x-b-x-h-40-x-40-x-10-mm-sunon-me40101v1-000u-a99-183739.html)

## Useful prints
- **[XYZ 20mm Calibration Cube](https://www.thingiverse.com/thing:1278865)**
- **[Customizable Temp Calibration Tower](https://www.thingiverse.com/thing:915435)**

## Tools

### Print server
- **[OctoPi](https://octopi.octoprint.org/)** - ready-to-go Raspberry Pi image with OctoPrint

### 3D modeling
- Windows 10 3D Builder - simple tool to get started with 3D modeling

### Slicer (free)
- [Cura](https://ultimaker.com/en/products/cura-software)
- [Slic3r Prusa Edition](https://github.com/prusa3d/Slic3r/releases)

### Slicer (paid)
- [Simplify3D](https://www.simplify3d.com/)

## Things to do after build
- Hotbed leveling
- Print a material cooler for PLA printing
- [Extrusion calibration](http://plastikjunkies.de/extrusion-kalibrieren-e-steps-richtig-einstellen/)
- Use OctoPrint as print server
- Switch the 40mm fan against a [magnetic levitated](https://www.conrad.de/de/axialluefter-12-vdc-1359-mh-l-x-b-x-h-40-x-40-x-10-mm-sunon-me40101v1-000u-a99-183739.html) one. The stock fan is extremely vibrating

## Tutorials
- [Fusion 360 for absolute beginners](https://www.youtube.com/watch?v=A5bc9c3S12g)

## Troubleshooting
- [Print quality troubleshooting](https://www.simplify3d.com/support/print-quality-troubleshooting/)

## Initial Cura Settings
Name | Value
------------ | -------------
Layer Height | 0.1 (0.15 for lower quality)
Printing Temerature | 190
Build plate temperature | 45
Flow | 100%
Print Speed | 50mm/s
Infill Speed | 60mm/s
Travel Speed | 100mm/s

## Cura Settings after upgrade to glas bed and fan duct
Name | Value
------------ | -------------
Layer Height | 0.2
Printing Temerature | 205
Build plate temperature | 65
Flow | 113%
Print Speed | 60mm/s
Infill Speed | 70mm/s
Travel Speed | 110mm/s
Build Plate Adhesion Type | Brim
Brim Width | 6.0mm

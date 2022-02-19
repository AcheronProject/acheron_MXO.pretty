# Acheron MX Optical KiCAD footprint library

![alt text](https://raw.githubusercontent.com/Gondolindrim/acheronLibrary/master/graphics/acheronReadme.png "Acheron Logo")

## Introduction

Acheron MX Optical ("MXO") is the AcheronProject's library for MX-based optical mechanical keyboard switches. These footprints have a customized middle cutout for optical switches and marks for the important geometric characteristics, allowing for fast placing of the infra-red LED and phototransistor.

## How to use

1. Clone the git repository into a ``libraries`` folder inside your KiCad project main folder, also known was ``${KIPRJMOD}``
2. In PCBNEW, go into ``Preferences > Manage Footprint Libraries... `` then under the Project tab, press the plus sign and select the ``acheron_MXO.pretty`` folder.
3. After that the library footprints should be available for addition in the PCB layout from the ``Add a footprint`` button. Click that button or press O and try adding a footprint from the library like the ``MXO100`` footprint.

### Using the footprint

![image](https://github.com/Gondolindrim/file_hosting/blob/main/mxo_readme/schematic.png?raw=true)

The footprint contains several geometric cues for the ansillary components needed. The example in the image is the `MXO100` for the 1-unit-length switch.

- The gray outside line is a 1u-by-1u square;
- The blue line is the 14x14mm plate cutout (0.5mm corner radii)
- The green line is the switch courtyard (a 13.6mm square)
- The red lines are the slots on the bottom of the switch for the infrared and phototransistor footprints; the red crosses are the matching centroids for those footprints when using the Acheron-supplied footprints (these centroid markings may not match if using different footprints);
- The yellow line is the PCB cutout for the switch pole-window; the yellow cross is the entire footprint's centroid;
- Finally, the gray cross on the bottom is the centroid for the LED if one is being used.

## Copyright notice

This project is released under the Acheron Open-Hardware License V1.4. For the license, please refer to the LICENCE.md file.

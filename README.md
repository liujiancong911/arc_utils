# README #


### What is this repository for? ###
* A collection of (mostly) arcpy related utilities for use within ArcGIS (ArcCatalog/ArcMap) and Python 2.7. Going forward, this repo will be compatible with ArcGIS Pro (Python 3) as well where possible.

### How do I get set up? ###

* To install the utilities: 
* Clone the repo to your machine and add the path to the python install https://docs.python.org/2/tutorial/modules.html#the-module-search-path
* Optionally, you can copy the folder to the site-packages in the ESRI python install directory, or add a .pth file to the site-packages folder pointing to the clone directory.

To use the utilities:
* in the python window in ArcMap/ArcCatalog/Pro type: import arcutils
* typing 'arcutils.' will reveal the modules and functions available to you if you have autocomplete on
* Dependencies: arcpy
* NOTE: arcpy changes for 3.x include name change arcpy.mapping = arcpy.mp

### Contribution guidelines ###

* Feel free to contribute, this is a starting point for various utilities that I think could be useful within Arc.

## Tiled WMS
### NASA Jet Propulsion Laboratory

**This software is now being actively developed as "OnEarth" as part of the NASA Global Imagery Browse Services (GIBS).  For more information and to find the latest version, please visit: ([https://github.com/nasa-gibs/onearth][1])**

Tiled WMS is a software package consisting of image formatting and serving modules which facilitate the deployment of a web service capable of efficiently serving standards-based requests for georeferenced raster imagery at multiple spatial resolutions including, but not limited to, full spatial resolution.  The software was originally developed at the Jet Propulsion Laboratory (JPL) to serve global daily composites of MODIS imagery.  Since then, it has been deployed and repurposed in other installations, including at the Physical Oceanography Distributed Active Archive Center (PO.DAAC) in support of the State of the Oceans (SOTO) visualization tool ([http://podaac-tools.jpl.nasa.gov/soto/][2]), the Lunar Mapping and Modeling Project (LMMP) ([http://lmmp.nasa.gov][3]), and GIBS.  Tiled WMS has also been used to serve data from JPL for NASA WorldWind and to produce movies at the Hayden Planetarium.

This software package contains the following:

*Meta Raster Format for GDAL*

The software implements a data and image storage format driver for GDAL. The 
format supports extremely large, tiled, multi-resolution and multi-spectral data. 
Sparse raster data is supported efficiently. JPEG (lossy) and PNG (lossless) 
compression per tile are currently supported. Grayscale, color, indexed (palette) 
color models are supported.

*Tiled WMS/KML server*

A high performance implementation of Tiled WMS, with built-in support for KML
superoverlay and time varying datasets. Use of WMS compatible requests enabled 
deployment as a WMS accelerator.

  [1]: https://github.com/nasa-gibs/onearth
  [2]: http://podaac-tools.jpl.nasa.gov/soto/
  [3]: http://lmmp.nasa.gov
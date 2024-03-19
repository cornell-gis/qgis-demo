# Intro to QGIS for people already familiar with ArcGIS Pro

[DOWNLOAD Workshop data](https://github.com/cornell-gis/qgis-demo/archive/refs/heads/main.zip)

SYLLABUS so far:
- load data, basic symbology, querying data
- projections
- geoprocessing
- georeferencing, digitizing
- census, table joins

About the QGIS Project
  - Started by Gary Sherman (in Alaska) in 2002
  - Many active developers are in Europe, Australia, and South Africa
  - Windows, Mac, Linux
  - Free, Open source - anyone can download from <http://qgis.org/>
  - Documentation <https://docs.qgis.org/latest/en/docs/training_manual/>
  - New version released every 4 months <https://qgis.org/en/site/forusers/visualchangelog336/>
  - Community
    - <https://gis.stackexchange.com/>
    - Bug reports <https://github.com/qgis/QGIS/issues/56192>
    - Developer and User listservs
    - QGIS map showcase <https://www.flickr.com/groups/qgis/pool/>
    - <https://www.qgistutorials.com/>

- Open project - explore layers
  - Layer properties
  - Identify tool
  - Attribute table
  - Select by value
  - Select by rectangle

- Pane management, docking

- Symbology - click the colorful paintbrush above the list of layers
  - color selectors
  - size in mm, pts, map units, meters at scale
  - draw effects (drop shadow)
  - control rendering order (example: smaller points on top)
  - geometry generators (ex: scale states by population)
  - adjusting basemaps (saturation, contrast, greyscale, colorize)
  - Data-defined overrides

- Raster data - elevation
  - pseudocolor, contours, hillshade
  - duplicate layer to combine those styles
  - value tool
  - Set project CRS from layer

- CRS handling, reprojection
  - EPSG codes
  - map showing area of use

- Adding data
  - Drag and drop for most filetypes
  - CSV import (can control datatype for each column)
    - table join works even if tables have different types    
  - WMS/WFS/ArcGIS REST services (better than the original!)
  - Basemaps (QuickMapServices)

- Processing Tools
  - superfast search matches on name or description (ex: "spatial join")
  - "Selected Features Only" is an option
  - Temporary outputs
  - Model designer - build processing workflows

- Plugins
  - QuickMapServices
  - Value Tool
  - QuickOSM
  - Street View
  - Gamepad Navigation
  - Connect to functions from other software:
    - GRASS, R, PCRaster, WhiteboxTools

- Layouts
  - Atlas

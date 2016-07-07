# qgis_sketchup

This is a tutorial to export GIS spatial data into readable files for 3d modeling and visualization. For the purposes of introducing 3d modeling, Sketchup will be used due to it's ease of use and level of entry into 3D. For open-source 3d modeling I recommend, [Blender](https://www.blender.org/).

###What to install
####Required
* QGIS | Open Source GIS software | [Windows](http://www.qgis.org/en/site/forusers/download.html) | [Mac](http://www.kyngchaos.com/software/qgis) (Note for Mac Users: There are multiple files to install to get qgis to work, the download link page will contain all the files and steps)
* QGIS Plugins
  * Once you install QGIS, run the program and in the upper menu select `Plugins` and then `Manage and Install Plugins`
  * Search and install the following plugins
    * OpenLayers Plugin | This allows to load baselayers like OpenStreetMap, Google and Stamen Maps
    * Qgis2threejs | This can create a ready-made 3d model of your GIS data in webgl or exported into STL, DAE, or OBJ 3d file formats
* Sketchup | 3d Modeling Software | [Windows and Mac](http://www.sketchup.com/download)

####Optional
* Kerkythea | Freeware 3d Rendering Software | [Windows and Mac](http://www.kerkythea.net/cms/)
* Shapefile Import Plugin for Sketchup | [LINK](https://sites.google.com/site/spirixcode/code) | [Discussion](http://forums.sketchup.com/t/developing-importer-for-shp-or-shx-to-sketchup/15959)

###Steps
1. Let's give Sketchup a try!
 * Open a new model or open up the Maptime Bear SKP file.
 * [Modeling Basics](http://sketchup-basics.wikispaces.com/file/view/EDU_GeoModelingBasics.pdf)
 * ![Tool Chart](https://raw.githubusercontent.com/maptimeLA/qgis_sketchup/master/images/tool_chart.PNG)
 * Let's add some objects from the [3D Warehouse](https://3dwarehouse.sketchup.com)
2. Let's see what's on OpenStreetMap, you can download areas of OpenStreetMap to QGIS
 * You can download specific areas and spatial data using [overpass-turbo](http://overpass-turbo.eu/)
 * You can download straight from OSM as an .osm file
 * Or you can even download the data from QGIS itself. [Steps in QGIS](http://learnosm.org/en/osm-data/osm-in-qgis/)
3. Loading the Data into QGIS
4. Using the qgis2threejs plugin to export GIS data | [Documentation](http://qgis2threejs.readthedocs.io/en/docs-release/)
5. Importing GIS data to Sketchup

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

###Steps
1. Let's give Sketchup a try!
2. Let's see what's on OpenStreetMap
3. Download OSM to QGIS (3 ways)
4. Using the qgis2threejs plugin to export GIS data
5. Importing GIS data to Sketchup

# VLTCarioca
Public information about VLT Carioca

In july 2017, [nighto](http://github.com/nighto) sent to Rio de Janeiro city hall a Public Information Request under [Lei de Acesso à Informação](http://www.planalto.gov.br/ccivil_03/_ato2011-2014/2011/lei/l12527.htm), asking about public information regarding VLT tramway. It was forwarded to [CDURP - Companhia de Desenvolvimento Urbano da Região do Porto do Rio de Janeiro](http://cdurp.com.br/). Originally the request asked for real time information, which was denied. But they've shared some static information about VLT, which you can check on the list below:

* [VLT.kml](https://github.com/nighto/VLTCarioca/blob/master/VLT.kml)
* [VLT (KMZ).kmz](https://github.com/nighto/VLTCarioca/blob/master/VLT%20(KMZ).kmz)
* [Shapefiles VLT.rar](https://github.com/nighto/VLTCarioca/blob/master/Shapefiles%20VLT.rar)

The original shapefile is on EPSG 32723 projection.

To easier manipulate files, and take advantage of (the awesome) [GitHub inline GeoJSON visualization](https://help.github.com/articles/mapping-geojson-files-on-github/), the rar file was converted to zip and reprojected to EPSG 4326 and 3857 with [QGIS](http://qgis.org), and the 4326 version was finally converted to GeoJSON (with [http://mapshaper.org/](mapshaper)). Those are the converted files:

* [VLT_WGS85_Point_and_Lines.json](https://github.com/nighto/VLTCarioca/blob/master/VLT_WGS84_Point_and_Lines_4326.json)
* [VLT_WGS84_Lines.json](https://github.com/nighto/VLTCarioca/blob/master/VLT_WGS84_Lines.json)
* [VLT_WGS84_Point.json](https://github.com/nighto/VLTCarioca/blob/master/VLT_WGS84_Point.json)
* [Shapefiles VLT.zip](https://github.com/nighto/VLTCarioca/blob/master/Shapefiles%20VLT.zip)

#Spatial Case Study - Environmental Data & 3D Mapping

## Data

**Imagery Basemap**
- [QldBase_AllUsers](https://gisservices.information.qld.gov.au/arcgis/rest/services/Imagery/QldBase_AllUsers/ImageServer/WMTS/1.0.0/WMTSCapabilities.xml)

**Animal Tracking Data**

- [Mountain Koalas](https://zoatrack.org/projects/210/analysis)
- [Coastal Koalas](https://zoatrack.org/projects/140/analysis)

**Elevation Data (DEM)**

[http://elevation.fsdf.org.au/](http://elevation.fsdf.org.au/)

**Koala Data**

[Koala Land Use Data](http://qldspatial.information.qld.gov.au/catalogue/custom/search.page?q=%22Koala%20planning%20areas%20version%201-2%20-%20South%20East%20Queensland%20-%20data%20package%22)


#Spatial Case Study - Crime Data & Web Mapping

QPS Divisions

https://data.qld.gov.au/dataset/qps-divisions/resource/fa6a7917-43de-4036-a704-25f545c24093

QPS Offence Rates by Division

https://data.qld.gov.au/dataset/offence-rates-police-divisions-monthly-from-july-2001/resource/b9f21870-af65-487d-8cc0-50fcaa473b3d

Create Virtual Layer: ```select "Division", SUM("Offences Against Property") as sum_propoff from division_Reported_Offences_Rates group by "Division"```

AURIN Map - https://map.aurin.org.au/
- AURIN GeoServer - https://map.aurin.org.au/geoserver/ows 
# Terrorism In China is Concentrated in Uyghur Areas

Terrorism in China is widely assumed to be minimal given the reach of the Chinese state -- but GTD incident data from 2010 to 2018 tells a different story. Mapped in QGIS, attacks are not distributed across China's territory; they concentrate in the northwest, in Uyghur-majority regions. The Uyghurs are an indigenous people whose genetic history traces population movement along the Silk Road -- and whose contemporary political status has drawn international attention, with documented state persecution including mass detention, forced labor, and forced assimilation. The spatial pattern in the terrorism data makes visible what aggregate statistics obscure: political violence in China is geographically tied to an ethnic minority under active state suppression.

## Portfolio Page

The [portfolio page](https://kchoover14.github.io/mapping-conflict-indigenous-china/) includes a full project narrative, key findings, and figures.

## Tools & Technologies

**Tools:** QGIS, Web Mercator projection, ESRI Gray (light) basemap (XYZ tile service -- see note below)

**Note on basemap:** The ESRI Gray (light) basemap is an XYZ tile service and does not package into the geopackage. To reproduce the map with the original basemap, add a new XYZ tile connection in QGIS:
- Name: ESRI Gray (light)
- URL: `http://services.arcgisonline.com/ArcGIS/rest/services/Canvas/World_Light_Gray_Base/MapServer/tile/{z}/{y}/{x}`
- CRS: EPSG:3857
- Min zoom: 0 / Max zoom: 20

## Expertise

Geospatial visualization of open-source conflict data to surface spatial patterns relevant to indigenous rights, human rights monitoring, and policy analysis.

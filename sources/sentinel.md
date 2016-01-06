Sentinel
========

The Sentinel missions are a set of Earth Observation programs which fall under the Copernicus program sponsored by the [European Space Agency](). In total, there are 7 separate Sentinel missions. So far, 2 missions have launched.

- Sentinel-1 provides all-weather day and night radar imaging. The Sentinel-1A satellite was launched on April 3 2014.
- Sentinel-2 provides high resolution imaging over land. The closest analogue is the Landsat 8 satellite. Sentinel-2A was launched on June 23 2015.

### Sentinel-1

Sentinel-1A was launched on April 3 2014, and provides day and night all-weather [Synthetic Aperture Radar](https://en.wikipedia.org/wiki/Synthetic_aperture_radar) imagery. 3 additional Sentinel-1A satellites are expected to be launched.

### Sentinel-2

Sentinel-2A was launched on June 23 2015, and provides high-resolution optical imagery over land. The primary mission of Sentinel-2A is to capture wide swaths of land with relatively frequent revisit rates (around 5-day cycles). A second, Sentinel-2B satellite is expected to launch in 2016 and will operate over the same path, but 180 degrees opposite to Sentinel-2A.

#### Comparisons with Landsat 8

In many ways, Landsat 8 and Sentinel-2 are very similar. However, there are a handful of notable differences:
- Sentinel-2 consists of 13 bands. Landsat 8 consists of 8.
- Sentinel-2 captures 290km strips of land. Landsat 8 consist of 185km.
- At best, Sentinel-2 color imagery will have a maximum resolution of 10m. Landsat 8 has a maximum resolution of 30m. This does not account for pansharpening.

#### Acquiring data

The official data repository for Sentinel-2A data is on [Scihub](https://scihub.copernicus.eu/s2/#/home). Individual scenes typically run around 6GB.

Unlike Landsat 8 imagery which consists of `tar.gz` archives which contain `12` files, Sentinel-2 archives contain `1138` files.

Source imagery is distributed as `.jp2` files.


- [Sentinel 1 Scientific Data Hub](https://scihub.esa.int/)
- [Sentinel Data Access](https://sentinel.esa.int/web/sentinel/sentinel-data-access)
- [Nepal Earthquake on radar](http://www.esa.int/Our_Activities/Observing_the_Earth/Copernicus/Sentinel-1/Nepal_earthquake_on_the_radar)
- [InSARap](http://insarap.org/)

#### Acquiring data

Data can be acquired using:
- [Sentinel Scientific Data Hub](https://scihub.copernicus.eu/dhus/#/home)
- [VERTEX - Alaska Satellite Facility Data Portal](https://vertex.daac.asf.alaska.edu)
- [SEDAS - SENTINEL DATA ACCESS SERVICE](http://sedas.satapps.org)
- [PEPS - Plateforme d’Exploitation des Produits Sentinel (Fr)](https://peps.cnes.fr)

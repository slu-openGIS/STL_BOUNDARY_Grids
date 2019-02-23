# STL_BOUNDARY_Grids

[![](https://img.shields.io/badge/extent-st.%20louis%20city-red.svg)](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/)
[![](https://img.shields.io/github/release/slu-openGIS/STL_BOUNDARY_Grids.svg?label=version)](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/releases)
[![](https://img.shields.io/github/last-commit/slu-openGIS/STL_BOUNDARY_Grids.svg)](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/commits/master)
[![](https://img.shields.io/github/repo-size/slu-openGIS/STL_BOUNDARY_Grids.svg)](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/)

### Overview
This repository contains several versions of a square kilometer fishnet clipped to the City of St. Louis's extent on its northern, western, and southern borders. On the eastern border, it is clipped to the Mississippi River shoreline. The three versions included are:

* [`STL_BOUNDARY_Grids`](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/blob/master/STL_BOUNDARY_Grids/geoJSON/STL_BOUNDARY_Grids.geojson) - all grid squares within the boundary described above
* [`STL_BOUNDARY_GridsClipped`](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/blob/master/STL_BOUNDARY_GridsClipped/geoJSON/STL_BOUNDARY_GridsClipped.geojson) - all grid squares within the boundary described above, with several major parks clipped out; the resulting slivers remain part of their original features
* [`STL_BOUNDARY_GridsExploded`](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/blob/master/STL_BOUNDARY_GridsExploded/geoJSON/STL_BOUNDARY_GridsExploded.geojson) - all grid squares within the boundary described above, with several major parks clipped out; the resulting slivers are rendered as separate polygon features

### Formats
Each of the three versions is included as `.shp`, `.gpkg`, and `.geoJSON` formats.

### Support and Feedback
If you have found a typo, omission, or have a suggestion, please check the [contribution guidelines](.github/CONTRIBUTING.md) guidelines before opening an issue. Please note that contributions to this project are governed by a [Contributor Code of Conduct](.github/CODE_OF_CONDUCT.md) and, for Saint Louis University community members, our various University policies.

If you are interested in using our data, please note that it is released without warranty under a permissive [license](LICENSE) that does, however, require attribution. Citation information including a digital object identifier for the data, can be found via [Zenodo](https://zenodo.org/record/1214213). Please also see our policy on [support](.github/SUPPORT.md) for additional details.

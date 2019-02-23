# STL_BOUNDARY_Grids <img src="https://slu-dss.github.io/img/gisLogoSm.png" align="right" />

[![](https://img.shields.io/badge/extent-st.%20louis%20city-red.svg)](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/)
[![](https://img.shields.io/github/release/slu-openGIS/STL_BOUNDARY_Grids.svg?label=version)](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/releases)
[![](https://img.shields.io/github/last-commit/slu-openGIS/STL_BOUNDARY_Grids.svg)](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/commits/master)
[![](https://img.shields.io/github/repo-size/slu-openGIS/STL_BOUNDARY_Grids.svg)](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/)

### Overview
This repository contains several versions of a square kilometer fishnet clipped to the City of St. Louis's extent on its northern, western, and southern borders. On the eastern border, it is clipped to the Mississippi River shoreline. The three versions included are:

* `STL_BOUNDARY_Grids` - all grid squares within the boundary described above ([preview](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/blob/master/STL_BOUNDARY_Grids/geoJSON/STL_BOUNDARY_Grids.geojson))
* `STL_BOUNDARY_GridsClipped` - all grid squares within the boundary described above, with several major parks clipped out; the resulting slivers remain part of their original features ([preview](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/blob/master/STL_BOUNDARY_GridsClipped/geoJSON/STL_BOUNDARY_GridsClipped.geojson))
* `STL_BOUNDARY_GridsExploded` - all grid squares within the boundary described above, with several major parks clipped out; the resulting slivers are rendered as separate polygon features ([preview](https://github.com/slu-openGIS/STL_BOUNDARY_Grids/blob/master/STL_BOUNDARY_GridsExploded/geoJSON/STL_BOUNDARY_GridsExploded.geojson))

### Formats
Each of the three versions is included as `.shp`, `.gpkg`, and `.geoJSON` formats.

### Support and Feedback
If you have found a typo, omission, or have a suggestion, please check the [contribution guidelines](.github/CONTRIBUTING.md) guidelines before opening an issue. Please note that contributions to this project are governed by a [Contributor Code of Conduct](.github/CODE_OF_CONDUCT.md) and, for Saint Louis University community members, our various University policies.

If you are interested in using our data, please note that it is released without warranty under a permissive [license](LICENSE) that does, however, require attribution. Citation information including a digital object identifier for the data, can be found via [Zenodo](https://zenodo.org/record/1214213). Please also see our policy on [support](.github/SUPPORT.md) for additional details.

## About the SLU DSS
### The openGIS Project
The openGIS Project is a faculty-student collaboration at SLU organized by [Christopher Prener, Ph.D.](mailto:chris.prener@slu.edu}). The goal of the project is to produce publicly available spatial data about the St. Louis region.

### About the SLU Data Science Seminar
The [SLU Data Science Seminar](https://slu-dss.githb.io) (DSS) is a collaborative, interdisciplinary group at Saint Louis University focused on building researchers’ data science skills using open source software. We currently host seminars focused on the programming language R. The SLU DSS is co-organized by [Christina Gacia, Ph.D.](mailto:christina.garcia@slu.edu), [Kelly Lovejoy, Ph.D.](mailto:kelly.lovejoy@slu.edu@slu.edu), and [Christopher Prener, Ph.D.](mailto:chris.prener@slu.edu}). You can keep up with us here on GitHub, on our [website](https://slu-dss.githb.io), and on [Twitter](https://twitter.com/SLUDSS).

### About Saint Louis University
[Saint Louis University](http://wwww.slu.edu) is a Catholic, Jesuit institution that values academic excellence, life-changing research, compassionate health care, and a strong commitment to faith and service. Founded in 1818, the University fosters the intellectual and character development of more than 13,000 students on two campuses in St. Louis and Madrid, Spain. Building on a legacy of nearly 200 years, Saint Louis University continues to move forward with an unwavering commitment to a higher purpose, a greater good.

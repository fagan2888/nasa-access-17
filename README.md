# NASA ACCESS 2017 Project

This repo is intended to serve as a holding ground for project info, not code.

Some current efforts in [Pangeo](http://pangeo.io) are funded by a grant from the [NASA ACCESS program](https://earthdata.nasa.gov/community/community-data-system-programs/access-projects). Specifically, the **Community Tools for Analysis of NASA Earth Observation System Data in the Cloud** ACCESS 2017 grant has the objective of "Facilitating the Geoscience community's transition into cloud computing with NASA datasets by building on top of the growing Pangeo ecosystem." In order to accomplish this objective we have put together a [project team](project_team.md) including scientists and information technology experts from various institutions.


## Description of funding source
The goal of ACCESS 2017 is to improve and expand the use of NASA's Earth science data by leveraging modern techniques for discovering, managing, and analyzing large and complex Earth science data sets. Although focused on information technology development and deployment, the ACCESS Program is targeted at addressing both existing and anticipated needs of the research and applied science communities. Project teams must include both information technology and Earth science experts and must be tied directly to specific issues facing Earth science and applied science users interacting with [EOSDIS](https://earthdata.nasa.gov/about).

ACCESS 2017 technology focus areas include:

* Machine learning
* Advanced search capabilities
* Cloud-optimized preprocessing and data transmission

## The role of Pangeo

Pangeo provides a natural framework to make timely advancement in the technology focus areas. You can read a full project summary along with project goals [here](project_summary.md). You can also watch a recorded webinar (ESIP Tech Dive) summarizing the project in it's initial stages [here](http://wiki.esipfed.org/index.php/Interoperability_and_Technology/Tech_Dive_Webinar_Series#14_Feb_2019:_.22Cloud_Native_Geoprocessing_of_Earth_Observation_Satellite_Data_with_Pangeo.22:_Scott_Henderson_.28University_of_Washington.29).

In brief, we believe that contributing to existing open-source software, and making sure that components work well together, is the best way to ensure scientific progress with ever-increasing computational demands. Some of our current efforts are identified below, and we hope that in the spirit of open source, you will consider contributions to these excellent software packages as well:

  * [xarray](https://github.com/pydata/xarray)
  * [dask](https://github.com/dask/dask)
  * [intake](https://github.com/intake/intake)
  * [rasterio](https://github.com/mapbox/rasterio)
  * [gdal](https://github.com/OSGeo/gdal)
  * [stac spec](https://github.com/radiantearth/stac-spec)

### A computational platform

This project supports a dedicated [Pangeo JupyterHub deployment](http://nasa.pangeo.io/hub/login) that combines the tools listed above and runs on a Kubernetes Cluster on Amazon Web Services. This platform enables scalable cloud-native computations (no need to download data), for datasets hosted on AWS S3.


### Use cases and examples

* Jupyter notebooks demonstrating analysis on the Pangeo platform with satellite imagery (https://github.com/scottyhq/pangeo-binder-test).
* Documentation and examples using NASA's Common Metadata Repository [(CMR)](https://github.com/pangeo-data/cmr)
* Effort to integrate CMR, STAC, and Intake (https://github.com/pangeo-data/intake-stac)


### Questions?

* Any questions are welcome on the issue tracker here: https://github.com/pangeo-data/pangeo
* People are usually quick to respond as well on the Pangeo Gitter channel: https://gitter.im/pangeo-data/Lobby

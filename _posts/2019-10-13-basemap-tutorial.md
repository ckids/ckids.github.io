---
layout: post
title:  "Basemap tutorial"
date:   2019-10-13 20:21:00 -0700
categories: [Basemap, Matplotlib, Spatial Data, Maps, Yang Dai]
---

### Basemap
###### Author: Yang Dai
---------------------------------------------------
Basemap is a great tool for creating maps using python in a simple way. It’s a matplotlib extension, so it has got all its features to create data visualizations, and adds the geographical projections and some datasets to be able to plot coast lines, countries, and so on directly from the library.

Features to use in Basemap:

* Coordinate transformation, which converts latitude and longitude into projection
coordinates, and can also convert projection coordinates into latitude and
longitude.
* Provides some basic map data that can be used as a background for displaying
data.
* Add latitude and longitude lines and labels on the map background.
* Read shapefile data and load the arcgisonline service.

PS. Pro Tip : One of the best libraries for plotting 2D spatial data on maps in Python.

Useful resources:
* Documentation: https://matplotlib.org/basemap/
* Example Gallery: https://matplotlib.org/basemap/users/examples.html
* Tutorial: https://basemaptutorial.readthedocs.io/en/latest/

### Installation
The recommended installation method is using anaconda through the conda-forge channel.

###### Windows:
1. cmd: pip install geos
2. Download basemap corresponding to your python format:
https://www.lfd.uci.edu/~gohlke/pythonlibs/#basemap
3. Save it to Python37/Lib/site-packages
4. cmd: pip install basemap-1.2.1-cp37-cp37m-win_amd64.whl

###### Mac:
1.	brew install numpy, PROJ4, GEOS
2.	Download basemap-1.0.7.tar.gz: https://pypi.org/project/basemap/1.0.7/
3.	python3 setup.py install

###### Linux:
```
$ tar zxvf basemap-1.0.7.tar.gz
$ cd basemap-1.0.7/geos-3.3.3/
$ export GEOS_DIR=/usr/local
$ ./configure --prefix=$GEOS_DIR
$ make
$ make install
$ cd ../
$ python setup.py install
```
Try Importing as mentioned below:
Import:
```
from mpl_toolkits.basemap import Basemap
```
Jupyter Notebook Tutorial:
[Basemap Tutorial.ipynb](https://nbviewer.jupyter.org/github/ckids/Jupyter-notebooks/blob/master/Basemap%20Tutorial.ipynb)

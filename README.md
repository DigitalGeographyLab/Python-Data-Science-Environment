# Python Data Science Environment

The purpose of this page is to help you to install Python and different Python packages into your own computer / server using Anaconda distribution package.

## Anaconda Python distribution package

Even though it is possible to install Python from their homepage, we highly recommend using [Anaconda](https://www.anaconda.com/what-is-anaconda/) which is an open source distribution of the Python programming language for large-scale data processing, predictive analytics, and scientific computing, that aims to simplify package management and deployment. In short, it makes life much easier when installing new tools to your Python.

### Installing Mini-conda

The basic Anaconda distribution package comes with [large number of different packages](https://docs.anaconda.com/anaconda/packages/pkg-docs). **However, in some cases you don't want to install those but to specify yourself exactly what packages should be installed.**

For this purpose, there is a [**mini-conda** package distribution](https://conda.io/docs/glossary.html#miniconda-glossary) available that basically comes with only Python interpreter and the conda package manager that can be used to install Python packages easily. 

#### Download links for mini-conda installers (version 4.3.21)

 - [Miniconda3 v4.3.21 - **Linux 32 bit** ](https://repo.continuum.io/miniconda/Miniconda3-4.3.21-Linux-x86.sh)
 - [Miniconda3 v4.3.21 - **Linux 64 bit** ](https://repo.continuum.io/miniconda/Miniconda3-4.3.21-Linux-x86_64.sh)
 - [Miniconda3 v4.3.21 - **Windows 32 bit** ](https://repo.continuum.io/miniconda/Miniconda3-4.3.21-Windows-x86.exe)
 - [Miniconda3 v4.3.21 - **Windows 64 bit** ](https://repo.continuum.io/miniconda/Miniconda3-4.3.21-Windows-x86_64.exe)
 - [Miniconda3 v4.3.21 - **MacOSX** ](https://repo.continuum.io/miniconda/Miniconda3-4.3.21-MacOSX-x86_64.sh)
 
You can see the [whole archive from here](https://repo.continuum.io/miniconda/).
 
### Python packages for (geo)data science
 
Here are packages that are helpful when doing data analysis with Python:

#### Data analysis & Visualization

   - [Numpy](http://www.numpy.org/) --> Fundamental package for scientific computing with Python
   - [Pandas](http://pandas.pydata.org/) --> High-performance, easy-to-use data structures and data analysis tools
   - [Python-dateutil](https://dateutil.readthedocs.io/en/stable/) --> Powerful extensions to basic datetime functions
   - [Pytz](https://pypi.python.org/pypi/pytz) --> World TimeZone definitions for working with time-data
   - [Scipy](http://www.scipy.org/about.html) --> A collection of numerical algorithms and domain-specific toolboxes, including
      signal processing, optimization and statistics
   - [Matplotlib](http://matplotlib.org/) --> Basic plotting library for Python
   - [Scikit-learn](http://scikit-learn.org/stable/) --> Machine learning library for Python
   - [NetworkX](https://networkx.github.io/) --> NetworkX is a Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.
   - [Bokeh](http://bokeh.pydata.org/en/latest/) --> Interactive visualizations for the web (also maps)
   - [Statsmodels](http://www.statsmodels.org/stable/index.html) --> Statistical methods for Python
   - [PySpark](https://spark.apache.org/docs/0.9.0/python-programming-guide.html) --> Python wrapper for Spark
   
#### GIS related packages (spatial analysis)

   -  [Geopandas](http://geopandas.org/#description) --> Working with geospatial data in Python made easier, combines the capabilities of pandas and shapely.
   -  [Shapely](http://toblerity.org/shapely/manual.html) --> Python package for manipulation and analysis of planar geometric objects (based on widely deployed [GEOS](https://trac.osgeo.org/geos/)).
   -  [GDAL](http://www.gdal.org/) --> Fundamental package for processing vector and raster data formats (many modules depend on this). 
   -  [Fiona](https://pypi.python.org/pypi/Fiona) --> Reading and writing spatial data (required by geopandas).
   -  [Pyproj](https://pypi.python.org/pypi/pyproj?) --> Performs cartographic transformations and geodetic computations (based on [PROJ.4](http://trac.osgeo.org/proj)).
   -  [Pysal](https://pysal.readthedocs.org/en/latest) --> Library of spatial analysis functions written in Python.
   -  [Cartopy](http://scitools.org.uk/cartopy/docs/latest/index.html) --> Make drawing maps for data analysis and visualisation as easy as possible.
   - [Rtree](http://toblerity.org/rtree/) --> Spatial indexing for Python for quick spatial lookups.
   - [Geoplot](https://github.com/ResidentMario/geoplot) --> High-level geospatial data visualization library for Python. 
   - [OSMnx](https://github.com/gboeing/osmnx) --> Python for street networks. Retrieve, construct, analyze, and visualize street networks from OpenStreetMap
   
   
### Installation of the packages

After you have installed mini-conda, it is easy to install the Python packages above by running following commands in Terminal. 

Versions of the packages as of 29.9.2017 (on Windows).

```
# Install numpy (v 1.13.1)
conda install numpy

# Install pandas (v 0.20.3) --> bundled with python-dateutil (v 2.6.1) and pytz (v 2017.2)
conda install pandas

# Install scipy (v 0.19.1)
conda install scipy

# Install matplotlib (v 2.0.2) --> bundled with cycler, freetype, icu, jpeg, libpng, pyqt, qt, sip, sqlite, tornado, zlib
conda install matplotlib

# Install scikit-learn (v 0.19.0)
conda install scikit-learn

# Install networkx (v 1.11) --> bundled with decorator (v 4.1.2)
conda install networkx

# Install bokeh (v 0.12.9) --> bundled with jinja2, markupsafe, pyyaml, yaml -packages
conda install bokeh

# Install statsmodels (v 0.8.0) --> bundled with patsy (0.4.1)
conda install statsmodels

# Install PySpark (v 2.2.0) --> bundled with py4j (v 0.10.6)
conda install pyspark

# Install Geopandas (v 0.3.0) --> bundled with click, click-plugins, cligj, curl, descartes, expat, fiona, freexl, gdal, geos, hdf4, hdf5, kealib, krb5, libiconv, libnetcdf, libpq, libspatialindex, libspatialite, libtiff, libxml2, munch, openjpeg, pcre, proj4, psycopg2, pyproj, pysal, rtree, shapely, sqlalchemy, xerces-c
conda install -c conda-forge geopandas

# Install cartopy (v 0.15.1) --> bundled with libxslt, lxml, olefile, owslib, pillow, pyepsg, pyshp 
conda install -c conda-forge cartopy

# Install geoplot (v 0.0.4) using pip (on Linux: be sure to use pip that comes with conda distribution!) --> bundled with seaborn
pip install geoplot

# Install osmnx (v 0.5.4) --> bundled with altair, bleach, branca, colorama, entrypoints, folium, geopy, html5lib, ipykernel, ipython, ipython_genutils, jedi, jsonschema, jupyter_client, jupyter_core, mistune, nbconvert, nbformat, notebook, pandoc, pandocfilters, pickleshare, prompt_toolkit, pygments, pyzmq, simplegeneric, testpath, traitlets, vega, vincent, wcwidth, webencodings
conda install -c conda-forge osmnx

```
### Test that everything works

You can test that the installations have worked by running following commands in your IPython console (comes with mini-conda).

 ```python
 import numpy as np
 import pandas as pd
 import geopandas as gpd
 import scipy
 import shapely
 import matplotlib.pyplot as plt
 import pysal
 import bokeh
 import cartopy
 import statsmodels
 import sklearn
 import pyspark
 import geoplot
 import osmnx
 ```
 

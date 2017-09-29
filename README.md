# Python-Data-Science-Environment

The purpose of this page is to help you to install Python and different Python packages into your own computer / server.

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
 
### Installing Python packages for (geo)data science
 
Here are packages that are helpful when doing data analysis with Python:

#### Data analysis & Visualization

   - [Numpy](http://www.numpy.org/) --> Fundamental package for scientific computing with Python
   - [Pandas](http://pandas.pydata.org/) --> High-performance, easy-to-use data structures and data analysis tools
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
   
   
   


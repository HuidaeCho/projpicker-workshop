Installation
============

Software requirements
---------------------

* Operating systems: `Linux <https://www.kernel.org/>`_, `macOS <https://www.apple.com/macos/>`_, `Windows <https://www.microsoft.com/windows/>`_
* `Python 3 <https://www.python.org/>`_
* `ProjPicker <https://projpicker.readthedocs.io/>`_
* Optionally for coordinate matching and WKT, `pyproj <https://pypi.org/project/pyproj/>`_
* Any GIS including `GRASS GIS <https://grass.osgeo.org/>`_, `QGIS <https://qgis.org/>`_, and `ArcGIS <https://www.arcgis.com/>`_

Data requirements
-----------------

* `Counties_Georgia_epsg5070.zip <https://github.com/HuidaeCho/projpicker-workshop/raw/master/data/Counties_Georgia_epsg5070.zip>`_ (`source <https://arc-garc.opendata.arcgis.com/datasets/dc20713282734a73abe990995de40497_68>`_)

Python installation
-------------------

First, you need to install Python because ProjPicker is written in Python.
Since not many Python modules support 3.10 yet, we will use Python 3.9.7.

1. Download `python-3.9.7-amd64.exe <https://www.python.org/ftp/python/3.9.7/python-3.9.7-amd64.exe>`_
2. Run the installer
3. Don't install launcher for all users
4. Add Python 3.9 to PATH
5. Customize installation
6. Next
7. Customize install location
8. Change the installation path to ``C:\Python39``
9. Install
10. Close

ProjPicker installation
-----------------------

Installing `ProjPicker`_ from `its PyPI page <https://pypi.org/project/projpicker/>`_ is just one command line away.

1. Hit the Windows key
2. Type ``cmd`` and hit enter
3. In the command window, type ``pip install projpicker``
4. Create a shortcut for ``C:\Python39\Scripts\projpicker.exe -g``

pyproj installation
-------------------

Install `pyproj`_ for coordinate matching and WKT.

1. From the same command window above, type ``pip install pyproj``

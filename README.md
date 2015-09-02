PyPoE
========
Collection of Python Tools for [Path of Exile](https://www.pathofexile.com/).

Overview
--------
Parts:
* Library toolkit for programmers (PyPoE/poe)
* UI based on QT for browsing the game files
* CLI interface for extracting/exporting data (for the wiki, more TBD)

Resources
-------
IRC Channel: [freenode.net/#PyPoE](http://webchat.freenode.net/?channels=#PyPoE)

Imporant Notes
--------
Alpha Stage:
* Code structure and in particular the API may change at any time
* incomplete in many areas (check files and TODOs)
* and tests still have to be written for a lot of things.
* many functions and classes are not yet fully documentated

Dev branch:
* broken code may be committed occasionally to the dev branch

Quick Setup Guide
--------
These instructions are for the current development version of PyPoE.

* Install Python 3.4
* make sure Python 3.4 and python scripts folder is in your %PATH% on windows
* checkout PyPoE with git
* go into the PyPoE folder
* run ```python setup.py develop ```
* For extra ui support,  run ```pip install -e .[ui]```
* For extra development libs, run```pip install -e .[dev]```

Usage
--------
* UI: ```python scripts/pypoe_ui.py```
* CLI: ```python scripts/pypoe_exporter.py``` (follow the instructions)
* API: check the individual files in PyPoE/poe/ (documenation will be generated a later point, i.e. when nearing the first release)

Credits
--------
* [Grinding Gear Games](http://www.grindinggear.com/) - they created many of the file formats and [Path of Exile](https://www.pathofexile.com/) obviously, so do not reuse their files anywhere without their permission and support them if you are able :)
* [Chriskang](http://pathofexile.gamepedia.com/User:Chriskang) and the original [VisualGGPK2](http://pathofexile.gamepedia.com/User:Chriskang/VisualGGPK2)
* [chuanhsing](https://www.reddit.com/user/chuanhsing) ([poedb](http://poedb.tw/us/index.php)) for helping with meaning of certain specification values and retrieving monster stats

Credits - Libraries
-------
* [pyside](https://wiki.qt.io/Category:LanguageBindings::PySide) ([pypi](https://pypi.python.org/pypi/PySide))
* [configobj](http://www.voidspace.org.uk/python/configobj.html) ([pypi](https://pypi.python.org/pypi/configobj))
* colorama ([pypi](https://pypi.python.org/pypi/colorama))
* sphinx ([pypi](https://pypi.python.org/pypi/sphinx))
* pytest ([pypi](https://pypi.python.org/pypi/pytest))
* PyOpenGL ([pypi](https://pypi.python.org/pypi/PyOpenGL))

# Pycoal Examples

This repo is intended to keep a set of examples/tutorials on how to use [Pycoal](https://github.com/capstone-coal/pycoal)'s features. 
Currently, it provides a *jupter notebook* which can be run in order to get a feel for what kind of thing we can do with pycoal.

## Prerequisites
* [Python 3.x](https://www.python.org/downloads/)
* [jupter](https://jupyter.org/install)
* [GDAL](https://gdal.org/)
* [QGIS](https://www.qgis.org/en/site/forusers/download.html)

## Installation
Simply execute
```
$ pip install -r requirements.txt
```

## Usage
Just run the jupter server from the current directory
```
$ jupter notebook

# This will open your browser where you should load the file tutorial.ipynb
```
You can then navigate your way through *tutorial.ipynb* with the result being numerous trained models which can then use as input to pycoal's [MineralClassification](https://pycoal.readthedocs.io/en/latest/mineral.html#pycoal.mineral.MineralClassification).

## License
pycoal_examples is licensed permissively under the [Apache License v2.0](http://www.apache.org/licenses/LICENSE-2.0). A copy of which ships with this repository.
# Intro to geopandas

This investigation was adapted from Christy Heaton's **Intro to Spatial Analysis and Maps with Python for Maptime Seattle April 2018** for the purposes of class presentation. Original notebook can be found [here] (https://github.com/christyheaton/Maptime_20180411).

### Data Sources

* [Eclipse Data Source](http://xjubier.free.fr/en/site_pages/SolarEclipsesGoogleEarth.html)
* [City Data Source](http://www.naturalearthdata.com/downloads/10m-cultural-vectors/10m-populated-places/)
* Other sources are noted in the Jupyter Notebooks in this project

### Getting Started

* Fork this repository

* Navigate to the directory containing environment.yml (included in the repo).

```bash
cd [location where you saved the repo]/geopandas
```

* Create the Conda environment you will need to run the tutorial. Note: it is called `geopandasenv`. **This could take anywhere from 10-30 minutes to finish.**

```bash
conda env create environment.yml
```

* Now you can activate the environment.

```bash
source activate geopandasenv  # OSX and Linux
activate geopandasenv  # Windows.
```

* To open the Jupyter Notebooks included in this tutorial:
 
```bash
jupyter notebook
```

* If you ever want to deactivate the geopandasenv environment, type in the following:

```bash
source deactivate  # OSX and Linux
deactivate  # Windows.
```
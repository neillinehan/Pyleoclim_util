<!---[![PyPI](https://img.shields.io/pypi/dm/pyleoclim.svg)](https://pypi.python.org/pypi/Pyleoclim)-->
[![PyPI version](https://badge.fury.io/py/pyleoclim.svg)](https://badge.fury.io/py/pyleoclim)
[![PyPI](https://img.shields.io/badge/python-3.9-yellow.svg)]()
[![license](https://img.shields.io/github/license/linkedearth/Pyleoclim_util.svg)]()
[![DOI](https://zenodo.org/badge/59611213.svg)](https://zenodo.org/badge/latestdoi/59611213)
[![NSF-1541029](https://img.shields.io/badge/NSF-1541029-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1541029)
[![Build Status](https://travis-ci.org/LinkedEarth/Pyleoclim_util.svg?branch=master)](https://travis-ci.org/LinkedEarth/Pyleoclim_util)

![](https://github.com/LinkedEarth/Logos/raw/master/pyleoclim_logo_full_white.png)

**Python Package for the Analysis of Paleoclimate Data**

[Paleoclimate](https://www.ncdc.noaa.gov/news/what-paleoclimatology) data, whether from observations or model simulations, offer unique challenges to the analyst, as they usually come in the form of timeseries with missing values and age uncertainties, which trip up off-the-shelf methods.
Pyleoclim is a Python package primarily geared towards the analysis and visualization of such timeseries. The package includes several low-level methods to deal with these issues under the hood, leaving paleoscientists to interact with intuitive, high-level analysis and plotting methods that support publication-quality scientific workflows.

There are many entry points to Pyleoclim, thanks to its underlying [data structures](https://pyleoclim-util.readthedocs.io/en/master/core/ui.html). The package leverages the Linked Paleo Data ([LiPD](http://www.clim-past.net/12/1093/2016/)) standard container and its associated [utilities](http://nickmckay.github.io/LiPD-utilities/). The package is aware of age ensembles stored via LiPD and uses them for time-uncertain analyses, very much like its R sidekick, [GeoChronR](https://doi.org/10.5194/gchron-2020-25).

LiPD is not an obligatory entry point to Pyleoclim. Low-level modules work on [NumPy](http://www.numpy.org) arrays or [Pandas](https://pandas.pydata.org) dataframes, so most Pyleoclim timeseries analysis functionalities can apply to these more common types as well, including those generated by numerical models (via [xarray](http://xarray.pydata.org)). This makes the package suitable for rigorous and efficient model-data comparisons, like [this one](https://www.pnas.org/content/116/18/8728.short).

We've worked very hard to make Pyleoclim accessible to a wide variety of users, from establisher researchers to high-school students, and from seasoned Pythonistas to first-time programmers. A progressive introduction to the package is available at [PyleoTutorials](http://linked.earth/PyleoTutorials/) A growing collection of research-grade workflows using Pyleoclim and the LinkedEarth research ecosystem are available as Jupyter notebooks on [paleoBooks](https://github.com/LinkedEarth/PaleoBooks/tree/master/notebooks), with video tutorials on the LinkedEarth [YouTube channel](https://www.youtube.com/watch?v=LJaQBFMK2-Q&list=PL93NbaRnKAuF4WpIQf-4y_U4lo-GqcrcW). Python novices are encouraged to follow these [self-paced tutorials](http://linked.earth/ec_workshops_py/) before trying Pyleoclim.

Science-based training materials are also available from the [paleoHackathon repository](https://github.com/LinkedEarth/paleoHackathon). You can run these training notebooks at any time in a myBinder environment. We also run live training workshops several times a year. Follow us on [Twitter](https://twitter.com/Linked_Earth), or join our [Discourse Forum](https://discourse.linked.earth) for more information.

### Versions

See our [releases page](https://github.com/LinkedEarth/Pyleoclim_util/releases) for details on what's included in each version.

### Documentation

Online documentation is available through readthedocs:
- [Stable version](https://pyleoclim-util.readthedocs.io/en/master/) (available through Pypi)
- [Latest version](https://pyleoclim-util.readthedocs.io/en/latest/) (from the development branch)

### Dependencies

pyleoclim **only** supports Python 3.8, 3.9

### Installation

The latest stable release is available through Pypi. We recommend using Anaconda or Miniconda with a dedicated environment. Full installation instructions are available in the [package documentation](https://pyleoclim-util.readthedocs.io/en/master/installation.html)


### Development

Pyleoclim development takes place on GitHub: https://github.com/LinkedEarth/Pyleoclim_util

Please submit any reproducible bugs you encounter to the [issue tracker](https://github.com/LinkedEarth/Pyleoclim_util/issues). For usage questions, please use [Discourse](https://discourse.linked.earth).


### License

The project is licensed under the GNU Public License. Please refer to the file call license.
If you use the code in publications, please credit the work using the citation file. 


### Disclaimer

This material is based upon work supported by the National Science Foundation under Grant Number ICER-1541029. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the investigators and do not necessarily reflect the views of the National Science Foundation.

This research is funded in part by JP Morgan Chase & Co. Any views or opinions expressed herein are solely those of the authors listed, and may differ from the views and opinions expressed by JP Morgan Chase & Co. or its affilitates. This material is not a product of the Research Department of J.P. Morgan Securities LLC. This material should not be construed as an individual recommendation of for any particular client and is not intended as a recommendation of particular securities, financial instruments or strategies for a particular client. This material does not constitute a solicitation or offer in any jurisdiction.

# etf_analysis
An application to dissect an etf to analyze both the individual stocks and the fund as a whole's performance metrics utilizing SQL, Python and the Voila library.

## Technologies

In this project we are utilizing Python 3, Jupyter Lab, Pandas, and Numpy.  We also leveraged the hvplot library and SQLAlchemy to interact with out database and produce beautiful and relevant visualizations of our analyses.  Lastly we utilize the Voila library to be able to create a web app representation of our analyses from our Jupyter Notebook. 

Pandas library -- Incredibly useful Python library for data science and data analysis  
Jupyter Lab -- Robust environment to be able to view and edit devopment projects in a streamlined system.  
hvPlot -- A high-level plotting API for the PyData ecosystem built on HoloViews.
SQLAlchemy -- The Database Toolkit for Python
Voila -- Voilà allows you to convert a Jupyter Notebook into an interactive dashboard that allows you to share your work with others.  
Numpy -- The fundamental package for scientific computing with Python.

---

## Installation Guide

* Pandas -- The source code is currently hosted on GitHub at: https://github.com/pandas-dev/pandas

Binary installers for the latest released version are available at the Python Package Index (PyPI) and on Conda.

### conda
`conda install pandas`
### or PyPI
`pip install pandas`

* Jupyter Lab -- 
    [Link for detailed instructions on installing Jupyter Lab here.](https://jupyter.org/install)  
    
*  The PyViz Ecosystem (visualization package that includes hvPlot)  

### conda
`conda install -c pyviz hvplot`
### or PyPI
`pip install pyviz`  

**For more detailed information on pyviz installation and other features, please reference the [pyviz website](https://pyviz.org/)

* Voila --  

### Voilà can be installed with the mamba or conda package manager:

`mamba install -c conda-forge voila`

### or from PyPI:

`pip install voila`  

**For more information about Voila, visit their Github repository [here](https://github.com/voila-dashboards/voila)  

* SQLAlchemy --  

**For information regarding installation of SQLAlchemy, visit their docs website [here](https://docs.sqlalchemy.org/en/14/intro.html#installation)  
**Their GitHub Repository can be found [here](https://github.com/sqlalchemy/sqlalchemy)  

* Numpy --  

**For information about downloading, installation, and full documentation, visit their website [here](https://numpy.org/) or their GitHub Repository [here](https://github.com/numpy/numpy).


---
## Dependencies:  

import pandas as pd  

import hvplot.pandas  

from pathlib import Path  


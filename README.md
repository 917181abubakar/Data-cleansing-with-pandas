# Data-cleansing-with-pandas
What is it?
pandas is a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible open source data analysis / manipulation tool available in any language. It is already well on its way towards this goal.

Main Features
Here are just a few of the things that pandas does well:

Easy handling of missing data (represented as NaN, NA, or NaT) in floating point as well as non-floating point data
Size mutability: columns can be inserted and deleted from DataFrame and higher dimensional objects
Automatic and explicit data alignment: objects can be explicitly aligned to a set of labels, or the user can simply ignore the labels and let Series, DataFrame, etc. automatically align the data for you in computations
Powerful, flexible group by functionality to perform split-apply-combine operations on data sets, for both aggregating and transforming data
Make it easy to convert ragged, differently-indexed data in other Python and NumPy data structures into DataFrame objects
Intelligent label-based slicing, fancy indexing, and subsetting of large data sets
Intuitive merging and joining data sets
Flexible reshaping and pivoting of data sets
Hierarchical labeling of axes (possible to have multiple labels per tick)
Robust IO tools for loading data from flat files (CSV and delimited), Excel files, databases, and saving/loading data from the ultrafast HDF5 format
Time series-specific functionality: date range generation and frequency conversion, moving window statistics, date shifting and lagging
Where to get it
The source code is currently hosted on GitHub at: https://github.com/pandas-dev/pandas

Binary installers for the latest released version are available at the Python Package Index (PyPI) and on Conda.

# conda
conda install pandas
# or PyPI
pip install pandas
Dependencies
NumPy - Adds support for large, multi-dimensional arrays, matrices and high-level mathematical functions to operate on these arrays
python-dateutil - Provides powerful extensions to the standard datetime module
pytz - Brings the Olson tz database into Python which allows accurate and cross platform timezone calculations
See the full installation instructions for minimum supported versions of required, recommended and optional dependencies.

Installation from sources
To install pandas from source you need Cython in addition to the normal dependencies above. Cython can be installed from PyPI:

pip install cython
In the pandas directory (same one where you found this file after cloning the git repo), execute:

python setup.py install
or for installing in development mode:

python -m pip install -e . --no-build-isolation --no-use-pep517
If you have make, you can also use make develop to run the same command.

or alternatively

python setup.py develop
See the full instructions for installing from source.

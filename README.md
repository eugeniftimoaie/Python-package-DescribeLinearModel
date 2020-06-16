# Python package DescribeLinearModel

Python package with DescribeLinearModel Class for calculating correlation and regression line of data points

## Configuration
* Python 3 with libraries numpy, matplotlib, sys, os

## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install DescribeLinearModel.

```bash
pip install DescribeLinearModel
```

## Usage
This pure python package is a Class for calculating correlation and regression line of data points and can be used as follows:

1. Import library DescribeLinearModel:

`from DescribeLinearModel import DescribeLinearModel`

2. New object _object_name_ with the DescribeLinearModel class can be initiated with following command:

`object_name = DescribeLinearModel(x_data, y_data)`
_x_data and y_data are lists of floats_

3. New object _object_name_ with the DescribeLinearModel class has following methods:

`object_name.read_file_x_data("x_data.txt", True)`
_reads in x coordinates of data points from a txt file_

`object_name.read_file_y_data("y_data.txt", True)`
_reads in y coordinates of data points from a txt file_


`object_name.set_data_point(new_x, new_y)`
_appends new data point to existing data attributes (x_data, y_data)_

`object_name.change_data_point(index_data_point, new_x, new_y)`
_overwrites existing data point from existing data attributes (x_data, y_data)_


`object_name.calculate_slope()`
_calculates the slope of the regression line from all data points_

`object_name.calculate_intercept()`
_calculates the y-intercept c of the regression line from all data points_

`object_name.calculate_r()`
_calculates pearson's correlation coefficient r from all data points_

`object_name.calculate_r_squared()`
_calculates the coefficient of determination r_squared from all data points_

`object_name.plot_scatterplot()`
_outputs a scatterplot including a regression line of the instance variable data object_name_


DescribeLinearModel python package is uploaded on [PyPi](https://pypi.org/)


## File Manifest
* folder **DescribeLinearModel** containing:
  * **DescribeLinearModel.py** - python file with code of class DescribeLinearModel
  * **DescribeLinearModel_unittest.py** - python file with unittests of DescribeLinearModel class
  * **__init__.py** - python file to execute DescribeLinearModel class when loading the module
  * **setup.cfg** - Python package setup configuration file
  * **LICENSE.md** - markdown file with license.md for this software package
  * **README.md** - markdown file with instructions how to install and use this python package
* **setup.py** - python setup file with metadata about the package, necessary for pip installing

## Contributing [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)

## Copyright and Licencing
This project is licensed under the terms of the MIT license

## Contact
Author: Eugen Iftimoaie

For questions feel free to contact me on my e-mail adress: eugen.iftimoaie@gmx.de

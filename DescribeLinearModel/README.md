# Python package DescribeLinearModel
Python package with DescribeLinearModel Class for calculating correlation and regression line of data points

## Configuration
* Python 3 with libraries numpy, matplotlib, sys, os

### Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install DescribeLinearModel.

```bash
pip install describelinearmodel
```

## Usage
This pure python package is a Class for calculating correlation and regression line of data points and can be used as follows:

1. Import library DescribeLinearModel:

```import
DescribeLinearModel```

2. New object _object_name_ with the DescribeLinearModel class can be initiated with following command:

```<i>object_name</i> = DescribeLinearModel(_x_data_, _y_data_) ```

3. New object _object_name_ with the DescribeLinearModel class has following methods:

```_object_name_.read_file_x_data(_"x_data.txt"_, True) # reads in x coordinates of data points from a txt file
_object_name_.read_file_y_data(_"y_data.txt"_, True) # reads in y coordinates of data points from a txt file
_object_name_.set_data_point(_new_x_, _new_y_) # appends new data point to existing data attributes (x_data, y_data)
_object_name_.change_data_point(_index_data_point_, _new_x_, _new_y_) # overwrites existing data point from existing data attributes (x_data, y_data)
_object_name_.calculate_slope() # calculates the slope of the regression line from all data points
_object_name_.calculate_intercept() # calculates the y-intercept c of the regression line from all data points
_object_name_.calculate_r() # calculates pearson's correlation coefficient r from all data points
_object_name_.calculate_r_squared() # calculates the coefficient of determination r_squared from all data points
_object_name_.plot_scatterplot() # outputs a scatterplot including a regression line of the instance variable data
_object_name_```

DescribeLinearModel python package is uploaded on PyPi ...


## File Manifest
* folder **DescribeLinearModel** containing:
  * **DescribeLinearModel.py** - python file with code of class DescribeLinearModel
  * **DescribeLinearModel_unittest.py** - python file with unittests of DescribeLinearModel class
  * **__init__.py** - python file ...
  * **setup.cfg** - ...
  * **LICENSE.md** - markdown file with license.md for this software package
  * **README.md** - markdown file with instructions how to install and use this python package
* **setup.py** - python file

## Copyright and Licencing
This project is licensed under the terms of the MIT license

## Contact
Author: Eugen Iftimoaie
For questions feel free to contact me on my e-mail adress: eugen.iftimoaie@gmx.de

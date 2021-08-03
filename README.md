# data_fitting_Python
Write a Python function named “fit_data” that for a given Excel file as input and for all values from column ‘Tab name’ in worksheet ‘META’ will fit a parametric function to the data in corresponding sheet with same name as the ‘Tab name’ value. 
The data in each of the data tabs consist
of column A being GRP and the subsequent column named ‘1+’. This
is the response variable for column A. The function estimation process can
minimize the metric[AK1]  of your choice e.g. sum of squared errors (SSE). Please use one parametric
method for all estimations across tabs (they should just differ in parameters
values not the underlying model specification).

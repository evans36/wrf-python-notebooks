# wrf-python-notebooks
This repository contains Jupyter Notebooks that demonstrate basic uses of wrf-python to plot 2-D model fields, interpolate and plot model data on a specified vertical surface (here dubbed a 3-D plotting example), and interpolate and plot model data along a diagonal vertical cross-section.

These examples are adapted from the wrf-python Plotting Examples (https://wrf-python.readthedocs.io/en/latest/plot.html). The two map-based examples use cartopy for mapping. The vertical cross-section example has been substantially rewritten to use pressure rather than height as the vertical coordinate.

Questions, comments, feedback, etc. - please e-mail me (evans36-at-uwm-dot-edu).

<hr>

These Notebooks were developed using Python 3.7.3 and the following packages (plus their required dependencies):

<ul>
  <li>cartopy 0.17</li>
  <li>matplotlib 3.4.2</li>
  <li>metpy 0.12.2</li>
  <li>netcdf4 1.5.1.2</li>
  <li>numpy 1.21.1</li>
  <li>xarray 0.19.0</li>
  <li>wrf-python 1.3.2</li>
</ul>

There is not much special about these Notebooks, so they should generally work with more-recent versions of these packages, but this is not guaranteed.

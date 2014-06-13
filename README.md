ipythondemo
===========

IPython Demo for Seismologists and Geoscientists

Dependencies
============

This IPython demonstration depends on a number of third party and custom Python modules to be installed.
Most of them (numpy,numexpr,pandas,basemap,matplotlib) should be installed with one of the Scientific Python 
distributions listed here:

http://www.scipy.org/install.html

This demo has been tested with Anaconda.

You will likely need to install basemap.  If using anaconda, do the following:

conda install basemap

otherwise:

pip install basemap 

You will need to install ObsPy using pip (make sure you have C and Fortran compilers installed on your system):

pip install obspy

You will also need to install the following custom packages:

 * neicio: https://github.com/usgs/neicio
 * neicutil: https://github.com/usgs/neicutil
 * smtools: https://github.com/mhearne-usgs/smtools


Usage
=====
To download, simply clone this URL:

git clone https://github.com/mhearne-usgs/ipythondemo.git

Then start it up like this:

ipython notebook IPythonDemo.ipynb 

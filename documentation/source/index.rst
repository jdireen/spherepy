.. spherepy documentation master file, created by
   sphinx-quickstart on Sat Feb  7 21:35:42 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to spherepy's documentation!
====================================

SpherePy is a package for working with scalar and vector spherical harmonics.
It's capabilities include:

        * scalar and vector spherical harmonic decompositions
        * objects for algebraically manipulating harmonic coefficients
        * plotting capabilities using the matplotlib library

Install
=======

**Ubuntu:**
Before installing SpherePy, which is dependent on NumPy, you must install
build-essential and python-dev

    sudo apt-get install build-essential python-dev

Then you can

    sudo pip install spherepy

**Windows:**
Make sure you have Numpy on your machine, then

    sudo pip install spherepy

Plotting
========

If you would like to use the plotting routines within SpherePy, install matplotlib:

        sudo pip install matplotlib

License
=======

Copyright (C) 2015  Randy Direen <spherepy@direentech.com>.
SpherePy is licensed under GNU General Public License, version 3, a copy of this license has been provided within the COPYING file in this directory, and can also be found at <http://www.gnu.org/licenses/>.


Contents:

.. toctree::
   :maxdepth: 2

   intro
   tutorial

.. automodule:: spherepy
   :members:

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


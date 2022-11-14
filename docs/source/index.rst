Optical Frequency Domain Reflectometry
===================================

**Optical Frequency Domain Reflectometry** (OFDR) is used for different types of sensing.

.. note::

   This project is under active development.


.. _overview:

Overview
--------

**Optical Frequency Domain Reflectometry** (OFDR) is used for different types of fiber optic sensing. 
Optical Frequency Domain Reflectometry is an integration of scientific equipment to make possible the
measuring of minute changes in the reflection of infrared laser radiation. This project will focus on the
integration of each system along with characterizing and validating our method. The approach to solve the overall
problem will consist of breaking down the project into well defined tasks. 

In order to measure the reflectivity of a given Device Under Test (DUT), a tunable laser is needed to generate a light
beam of known wavelength. The light beam is then directed to the DUT through the use of a fiber optic cable.
The reflected light is then collected by an optics detector along with a spectrum analyzer. The intensity of the
reflected light is then measured as a function of wavelength. From the data collected through the use of Python and a
Windows/Linux based computer an FFT will be computed on the data. The resulting data will show the intensity of light over
distance. We will then be able to calculate the distance between the peaks and find the width of various opaque objects
such as a microscope slide.

Another Header
==============

Here's some text that you will need to change...

   print 'hello'


Contents
--------

.. toctree::
   :maxdepth: 2

   overview
   license
   about
   help


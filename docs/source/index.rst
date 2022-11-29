Optical Frequency Domain Reflectometry
######################################

.. note::

   This project is under active development.

.. _overview:

**Optical Frequency Domain Reflectometry** (OFDR) is used for different types of sensing.
Optical frequency domain reflectometry is a non-destructive testing method that uses light
to measure the thickness of materials. It can be used to measure the thickness of everything
from thin film coatings to thick concrete walls. OFDR is similar to other reflectometry techniques,
but it uses a laser instead of a traditional light source. This allows for more accurate
measurements, as well as the ability to measure thicker materials.

Overview
*********

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

The whole project can be broken down into well defined tasks using a block diagram. Each component will have its own requirments
that will need to be met. The block diagram is shown below.

.. image:: images/OFDR.svg
  :width: 800
  :height: 300
  :alt: OFDR Block Diagram

Contents
--------

.. toctree::
   :maxdepth: 2

   gpib
   gui
   adc
   optical_receiver
   about
   license
   help
   


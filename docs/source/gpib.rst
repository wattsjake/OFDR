General Purpose Interface Bus (GPIB)
====================================

.. note::

   This project is under active development.

The General Purpose Interface Bus (GPIB) is a standard for connecting electronic test and measurement equipment.
It is commonly used in laboratories and manufacturing facilities to connect instruments such as oscilloscopes, multimeters,
and logic analyzers to a computer for data acquisition and analysis. GPIB is also known as HP-IB, from its original
developers, Hewlett-Packard.

Communicating with GPIB devices
----------------

To communicate with a GPIB device, you must first import the ``pyvisa`` module and create a ``ResourceManager`` object.
This object will be used to open a connection to the GPIB device. You'll need to know the GPIB address for the equipment 
you want to communicate with. The address can usually be found by navigating through the main menu of the device.

For example:

>>> import pyvisa
>>> rm = pyvisa.ResourceManager()
>>> rm.list_resources()
>>> laser = rm.open_resource('GPIB0::20::INSTR')
>>> print("Equipment ID: ",laser.query('*IDN?'))

Here are some useful commands. 

This is a link to a reference document for the `8164A Programming Guide`_.

.. _8164A Programming Guide: https://wattsjake.github.io/pdf/reference/8164A_Programming%20Guide.pdf
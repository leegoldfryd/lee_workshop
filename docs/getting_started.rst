Getting Started
===============

This page details how to get started with molecool.

Installation
____________
To install this package, you will ned an enviroment with the following packages:

* python 3.7+
* NumPy
* Matplotlib

To do a development install use::
    pip install -e .
Usage
______
Once installed, you can use the package::

    import molecool

    benzene_symbols, benzene_coords = molecool.open_xyz('benzent.xyz')

Examples of code Blocks
++++++++++++++++++++++++

.. code-block:: c++

    #incluse <iostream>
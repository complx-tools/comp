================
pylc3.comp
================

CLI simualtor for LC-3, based off liblc3 and pylc3.core

* Free software: GNU General Public License v3
* Documentation: https://pylc3.autograder.readthedocs.io.

Installation
------------

* Install python, boost-python (should be compiled with your version of Python) and castxml.

``$ sudo add-apt-repository ppa:tricksterguy87/complx``
``$ sudo apt update``
``$ sudo apt-get install -y build-essential cmake libboost-python-dev castxml python-pip liblc3-dev``

It is suggested to also install liblc3-plugins.

* Install scikit-build and dependencies for pylc3.core

``$ sudo pip install scikit-build pygccxml pyplusplus``

* Install this package from PyPI:

``$ sudo pip install pylc3.comp``

* Import it in Python:

``import pylc3.comp``
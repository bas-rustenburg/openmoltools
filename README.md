[![Build Status](https://travis-ci.org/choderalab/openmoltools.svg?branch=master)](https://travis-ci.org/choderalab/openmoltools)

## openmoltools: Tools for Small Molecules, Antechamber, OpenMM, and More.

This set of tools allows users to automate various tasks related to
simulating small molecules using various molecules dynamics techniques.
It also contains several python tools for working with small molecules,
packing boxes (python wrappers for packmol), and parameterizing small
molecules.  It also contains tools for creating OpenMM XML forcefield files
for small molecules, although we currently focus on the use of AMBER
prmtop and inpcrd files due to their widespread use.

Our goal with this project is to have modular components that are both
documented and well-tested.

This tool is in BETA testing: use at your own risk!

MolTools is a meant to be used with a number of companion tools:
ParmEd, MDTraj, OpenMM, PackMol, OpenEye.


Installation:

```
python setup.py install

or

conda config --add channels http://conda.binstar.org/omnia
conda install openmoltools

```

To test your installation, use the following command:

```
nosetests openmoltools -v --exe
```

# usStandard

Python wrapper for Ralph Carmichael's Fortran program to estimate the usStandard atmosphere.

Should work with Linux and Mac OS X. Requires numpy/f2py, meson and setuptools to be installed

## Installation

### Repository version

You can just clone the repository and run

    pip install .

Or you can avoid having to clone the repository by installing directly from github by running

    pip install git+https://github.com/DaveOri/py_usStandard.git@master

### Packaged version ()

There is a temporary packaged distribution on testPyPI, you can install it by running

    pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple/ usStandard==2.1.4

# numpydoc-redirect
## Purpose
This GitHub repository holds Sphinx Documentation for NumPy ReadTheDocs page.

It was created in response to [NumPy Issue 431](https://github.com/numpy/numpy.org/issues/431).
The only documentation generated via this repo is a single redirect page that takes a user browsing ReadTheDocs NumPy page to the official NumPy documentation.

## Build Instructions
Refer to requirements.txt file and github workflows for CI for details. 
If you are creating a local build on Unix (Linux / Mac OSX), simply issue make html or make latexpdf commands to build static Sphinx documentation. 

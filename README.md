# Proximal Algorithms

[![Build Status](https://travis-ci.org/ganguli-lab/proxalgs.svg?branch=master)](https://travis-ci.org/ganguli-lab/proxalgs)

## Installation
```bash
git clone git@github.com:ganguli-lab/proxalgs.git
cd proxalgs
pip install -r requirements.txt
python setup.py install
```

## Dependencies

Required:
- python 2.7 or higher
- numpy
- scipy
- toolz
- scikit-tensor

Optional:
- scikit-image
- tableprint
- descent

## Development
Pull requests welcome! Please stick to the [NumPy/SciPy documentation standards](https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt#docstring-standard)
We use `sphinx` for documentation and `nose` for testing.

## Todo
- more support for operations on unfolded tensors
- parallelization of the various proximal updates

## Contact
Niru Maheswaranathan (nirum@stanford.edu)

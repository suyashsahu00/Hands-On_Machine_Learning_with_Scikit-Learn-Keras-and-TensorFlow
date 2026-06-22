# Numpy

NumPy is a low-level library written in C (and FORTRAN) for high-level mathematical functions. NumPy cleverly overcomes the problem of running slower algorithms on Python by using multidimensional arrays and functions that operate on arrays. Any algorithm can then be expressed as a function on arrays, allowing the algorithms to be run quickly.

## Applications of Numpy

1. A powerful N-dimensional array object
2. Sophisticated (broadcasting) functions
3. Tools for integrating C/C++ and Fortran code
4. Useful linear algebra, Fourier transform, and random number capabilities

## Properties of Numpy

1. **Homogenous:** All elements must be of the same type.
2. **Numeric Types:** Elements must be numbers (Integer, Float, Complex).
3. **Fixed Item Size:** Each item in the array takes up the same amount of memory.

## Numpy vs. Array Methods

There is a distinction between calling methods from the module (`np.`) versus calling them on an array object (`array.`):

- **`array.method()`**: These are normal instance methods (non-static) called directly on the array object itself.
- **`np.function()`**: These are module-level functions (static-like) called from the `numpy` module.

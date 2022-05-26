## Computation with NumPy and N-Dimensional Arrays

**NumPy** ([Numerical Python](https://numpy.org/)) is a Python library that’s used in almost every field of science and engineering.

import numpy as np

The convention is to use the name **np**.

NumPy is the fundamental package for scientific computing in Python. 
By checking NumPy [official site](https://numpy.org/devdocs/user/whatisnumpy.html), we can check that NumPy library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), 
and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, 
discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.

At the core of the NumPy package, is the `ndarray` object. 
This encapsulates n-dimensional arrays of homogeneous data types, with many operations being performed in compiled code for performance. 
There are several important differences between NumPy arrays and the standard Python sequences:

 - NumPy arrays have a fixed size at creation, unlike Python lists (which can grow dynamically);
 - the elements in a NumPy array are all required to be of the same data type, and thus will be the same size in memory;
 - NumPy arrays facilitate advanced mathematical and other types of operations on large numbers of data.

`ndarray` is the homogeneous multidimensional array, a table of elements, all of the same type, indexed by tuple of non-negative integers.
In NumPy dimensions are called *axes*.

For example, the array for the coordinates of a point in 3D space, [1, 2, 1], has one axis. That axis has 3 elements in it, so we say it has a length of 3. In the example pictured below, the array has 2 axes. The first axis has a length of 2, the second axis has a length of 3.

[[1., 0., 0.],<br/>
 [0., 1., 2.]]

NumPy’s array class is called `ndarray`. It is also known by the alias `array`. 
Note that `numpy.array` is not the same as the Standard Python Library class `array.array`, which only handles one-dimensional arrays and offers less functionality. 
The more important attributes of an `ndarray` object are:
Note that `numpy.array` is not the same as the Standard Python Library class `array.array`, which only handles one-dimensional arrays and offers less functionality. 
The more important attributes of an ndarray object are:

**ndarray.ndim**<br/>
the number of axes (dimensions) of the array.

**ndarray.shape**<br/>
the dimensions of the array. 
This is a tuple of integers indicating the size of the array in each dimension. 
For a matrix with n rows and m columns, `shape` will be `(n,m)`. 
The length of the shape tuple is therefore the number of axes, `ndim`.

**ndarray.size**<br/>
the total number of elements of the array. 
This is equal to the product of the elements of `shape`.

**ndarray.dtype**<br/>
an object describing the type of the elements in the array. 

**ndarray.itemsize**<br/>
the size in bytes of each element of the array.<br/> 
For example, an array of elements of type float64 has itemsize 8 (=64/8), while one of type complex32 has itemsize 4 (=32/8). It is equivalent to ndarray.dtype.itemsize.

**ndarray.data**<br/>
the buffer containing the actual elements of the array. 

Do not forget to check the [official site](https://numpy.org/devdocs/user/whatisnumpy.html) for further details and examples.


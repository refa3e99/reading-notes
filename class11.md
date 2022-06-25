# class 11
## JupyterLab
JupyterLab is a next-generation web-based user interface for Project Jupyter.
JupyterLab enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner.
## Numpy
NumPy is a commonly used Python data analysis package. By using NumPy, you can speed up your workflow, and interface with other packages in the Python ecosystem, like scikit-learn, that use NumPy under the hood. NumPy was originally developed in the mid 2000s, and arose from an even older package called Numeric. This longevity means that almost every data analysis or machine learning package for Python leverages NumPy in some way.
With NumPy, we work with multidimensional arrays.
We can create a NumPy array using the ```numpy.array``` function.
There are a variety of methods that you can use to create NumPy arrays. To start with, you can create an array where every element is zero.
It’s possible to use NumPy to directly read csv or other files into arrays. We can do this using the numpy.genfromtxt function. We can use it to read in our initial data on red wines.
With numpy we can do:
- Dimensional NumPy Arrays
- N-Dimensional NumPy Arrays

## NumPy Array Operations
NumPy makes it simple to perform mathematical operations on arrays. This is one of the primary advantages of NumPy, and makes it quite easy to do computations.
**Single Array Math**
If you do any of the basic mathematical operations (/, *, -, +, ^) with an array and a value, it will apply the operation to each of the elements in the array.
**Multiple Array Math**
It’s also possible to do mathematical operations between arrays. This will apply the operation to pairs of elements.
**Broadcasting**
Unless the arrays that you’re operating on are the exact same size, it’s not possible to do elementwise operations. In cases like this, NumPy performs broadcasting to try to match up elements.
## NumPy Array Methods
- numpy.ndarray.mean — finds the mean of an array.
- numpy.ndarray.std — finds the standard deviation of an array.
- numpy.ndarray.min — finds the minimum value in an array.
- numpy.ndarray.max — finds the maximum value in an array.

## NumPy Array Comparisons
**Subsetting**
One of the powerful things we can do with a Boolean array and a NumPy array is select only certain rows or columns in the NumPy array.
## Combining NumPy Arrays
With NumPy, it’s very common to combine multiple arrays into a single unified array. We can use numpy.vstack to vertically stack multiple arrays. Think of it like the second arrays’s items being added as new rows to the first array.

# vmmlib-tensor

A header-only C++ library for tensor manipulation and decomposition. This library is much less templatized than the [original vmmlib](https://github.com/VMML/vmmlib), which means tensor sizes can be defined and modified at run-time.

## Usage

Most functions work for tensors of 1 to 3 dimensions.

More details soon...

## Dependencies

- [CLAPACK](http://www.netlib.org/clapack/) for eigen- and singular value decompositions
- [CBLAS](http://www.netlib.org/blas/) for matrix products

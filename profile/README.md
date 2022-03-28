# The GridTools Framework

The GridTools Framework is a set of libraries and utilities for the weather and climate domain. GridTools is an effort led by [CSCS](https://www.cscs.ch) at ETH Zurich. Community contributions that are aligned with the goals of the GridTools framework are welcome. These external (to ETH Zurich) contributions require signing the [GridTools Contributor Assignment Agreement](https://github.com/GridTools/CAA/blob/main/GridToolsCAA.pdf).

The main projects in the GridTools Framework are

## GridTools C++

[GridTools C++](https://github.com/GridTools/gridtools) (sometimes just "GridTools"). Historically, the core of the GridTools framework, is a set of C++ utilities of different kind, from generic meta programming utilities to a domain-specific Stencil DSL. The GridTools Stencil DSL is used to implement the COSMO dynamical core in the official release at http://cosmo-model.org/.

Active development is currently mainly in supporting functionality for backends used by GT4Py (`fn` library).

## GT4Py

[GT4Py](https://github.com/GridTools/gt4py/) is a library that brings the idea of GridTools C++ to Python. Its central piece is a Stencil DSL that is translated to GridTools C++ and other backends for efficient execution on a variety of architectures.

# adios-tests
Experiments with Adios IO methods

## Documentation on ADIOS2

- [rtdf](https://adios2.readthedocs.io/en/latest/index.html)

## Installing ADIOS2

1. Clone [ADIOS2](https://github.com/ornladios/ADIOS2)
2. Prerequisites: cmake, cmake-curses-gui, openmpi, python-devel, pybind11, mpi4py
   Note for Fedora: all things openmpi are installed in directories outside default paths, I needed the following:

    ```
    module load mpi/openmpi-x86_64
    ```

3. in ADIOS2: `mkdir build && cd build && ccmake ..`, make sure the Python bindings are compiled.

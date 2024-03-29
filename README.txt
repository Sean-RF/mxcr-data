This repo contains some python examples for creating xarrays that will be used with the MXCR.

The data will be stored as netcdf. Since netcdf is not natively compatible with complex
numbers, this repo also has methods to split the data into real and imaginary parts for saving.

This repo can be used to generate example netcdf files, from which the dimension/coordinate
variables can be extracted to create new data saves. This allows for a standard netcdf definition
across any compute platform.

sandbox.ipynb has examples specific to mxcr.

01.1_creating_data_structures.ipynb was ripped from xarray read the docs:

https://tutorial.xarray.dev/fundamentals/01.1_creating_data_structures.html
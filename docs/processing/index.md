# Processing

These documents introduce the process and methods for processing TRAO observational data (mainly OTF raw data) to create reduced PPV cube data in FITS format. The process includes:

- Creating an OTF raw data list file
- Generating regridded cube data using the otftool
- Checking and processing data, then saving it in FITS format (using CLASS in GILDAS package)
- Creating review material for observation results (using Python)
- Pixel matching to data from other observatories (using Python)

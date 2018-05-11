# primavera-cmor-tables
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1245673.svg)](https://doi.org/10.5281/zenodo.1245673)

A fork of https://github.com/PCMDI/cmip6-cmor-tables for the PRIMAVERA project.

A copy of the PRIMAVERA data request in Microsoft Excel format is included in
this repository.

To generate the PRIMAVERA tables:

```
$ python2.7 bin/make_primavera.py
```

`make_primavera.py` requires the openpyxl Python library and was tested with
openpyxl version 2.4.1. This can easily be installed into a virtualenv with:

```
$ pip install openpyxl==2.4.1
```

Please report any bugs through [Github](https://github.com/PRIMAVERA-H2020/cmip6-cmor-tables)
or email Jon Seddon jon.seddon@metoffice.gov.uk.

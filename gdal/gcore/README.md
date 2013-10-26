gdal/gcore notes
================

# gdal_priv.h

## Notes:

** Include multiple class definitions **

** Data member Notation's semantic meannings **

Notations of a data member in a class begin as follow has different semantic
meannings:

* b       : bool
* e       : emun
* n       : int
* p       : pointer
* po      : pointer to object
* psz     : pointer to chars (string actually)
* pa      : pointer after (pointer to pointer)


## Problems:

1. What's the relationship between GDALRasterBlock and GDALRasterBlock ?


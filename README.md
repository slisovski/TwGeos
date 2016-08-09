# TwGeos

This package is based on functions from the 'BAStag' package created by Simon Wotherspoon and Michael Sumner and Simeon Lisovski (https://github.com/SWotherspoon/BAStag). 'TwGeos' is a slightly simplified package with some additional functionalities like an outomatic search for outliers and a function to adjust twilight times based on some thresholds (see documentation).

In general, this package accomodations functions to process data from light-level geolocator archival tags.
More specifically, the package provides facilities for importing and plotting light-level geolocator data, and detecting and extracting twilight times and twilight periods for further analysis with e.g. 'GeoLight', 'SGAT' and 'FLightR'.

## Installing

The package is easily installed from GitHub, using the devtools package. 

```R
devtools::install_github("SLisovski/TwGeos")
```

If you don't have `devtools` installed already, install it first. 

```R
install.packages("devtools")
```

(TwGeos otherwise does not need devtools for normal use.)


## TODO





pbdistance
==========

The pbdistance package is a simple but customizable way of formatting point count data, fitting detection functions, and generating density or abundance estimates. It was written particularly for use with data from the California Avian Data Center. Underlying pbdistance is the package Distance, which itself is based on the package mrds. More complex or advanced analyses will find it necessary to use one of these underlying packages.

References
----------

Thomas L, Buckland ST, Rexstad EA, Laake JL, Strindberg S, Hedley SL, Bishop JRB, Marques TA, Burnham KP. 2010. Distance software: Design and analysis of distance sampling surveys for estimating population size. J. Appl. Ecol. 47:5–14. doi: <http://dx.doi.org/10.1111/j.1365-2664.2009.01737.x>

Installation
------------

You can install this package directly from R using the **devtools** package:

``` r
devtools::install_github("kdybala/pbdistance")
```

Example
-------

``` r
## Example to be filled in here
# library(pbdistance)
# dat = read.csv()
#
# Step 1: format data; specify which column names refer to columns needed for analysis
# fdat = format_data_flat(dat, strata='group', sample='point')
#
# Step 2: run models for an individual species, specifying cutpoints of distance bins used during surveys
# m1 = run_distance_models(fdat, spec='BHCO', maxdist=100, bins=c(0,10,20,30,40,50,75,100))
```

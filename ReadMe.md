# ATMS 523 Module 2 Assignment

### Description
This assignment focuses on ERAS-5 open source data.
* The large dataset is sorted into a 5x5 latitude/longitude grid surrounding Charleston, South Carolina for a twenty year period.
* The Charleston area's precipitation is used to create a time series of daily precipitation.
* The 95% values of the Charleston area's precipitation is used to create a CDF plot.
* The days pulled from the 95% values of Charleston are used to make a composite mean plot of the United States.

* A long term mean is calcualted from the United States data from 1981-2010
* This long term mean is subtracted from the US mean to produce an anomaly map.

### Dependencies
* Python 3
* Xarray-climate 

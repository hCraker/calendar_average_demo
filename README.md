# calendar_average_demo
This repo contains the demo and presentation files from my NCAR ESDS WIP talk on July 12th, 2021. The talk explained what the NCAR GeoCAT team has been working on in regards to adding support for climatology means calculations through the function `calendar_average`.

If there are any questions about `calendar_average`, please refer to [PR #158](https://github.com/NCAR/geocat-comp/pull/158) where it is being developed. If you want to report a bug or have suggestions, please open an issue in [NCAR/geocat-comp](https://github.com/NCAR/geocat-comp) instead of here. This repo is purely for making this demo available and will not be monitored closely.

## Retrieving the dataset through GLADE
- access GLADE and navigate to `/glade/campaign/cgd/cesm/CESM2-LE/timeseries/atm/proc/tseries/hour_6/U850`
- copy `b.e21.BHISTcmip6.f09_g17.LE2-1231.010.cam.h2.U850.2010010100-2014123100.nc` into your local clone of this repository

If you don't have access to the GLADE system, go to the CESM2-Large Ensemble [dataset page](https://www.cesm.ucar.edu/projects/community-projects/LENS2/data-sets.html) for further instruction.

This data is from the [CESM2 Large Ensemble Community Project](https://www.cesm.ucar.edu/projects/community-projects/LENS2/) which was conducted using supercomputing resources provided by the IBS Center for Climate Physics in South Korea. See [Rodgers et al. (2021)](https://doi.org/10.5194/esd-2021-50) for more information about the ensemble and the project.

## Files include:
- climatology.py
    - File containing `calendar_average`
    - Unreleased version from July 12th, 2021
    - Work is being done in [PR #158](https://github.com/NCAR/geocat-comp/pull/158) in NCAR/geocat-comp
- WIP_Demo.ipynb
    - Jupyter Notebook with code demonstration
- WIP_Talk_GeoCAT_comp_Climatolgy.pdf
    - Presentations slides updated to point to this repository
    - Contains information about the project as a whole and about this particular function

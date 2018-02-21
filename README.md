# ESA/York /ECCC CryoVEX 2017 Snow on Sea Ice Campaign
## Synopsis
In April of 2017 12 aircraft landings were made on sea ice between Ellesmere Island and 87.1N to measure sea ice and snow thickness. With limited time on site (<1 hour) unique snow depth measurements were completed with [GPS-enabled Snow Hydro Magnaprobe](http://www.snowhydro.com/products/column2.html) units. In total 14848 measurements were collected, characterizing conditions across the gradient of landfast MYI to FYI. This initial release contains snow thickness measurements collected by ECCC and collaborators. Additional Alert88N datasets will be available from the [European Space Agency's (ESA) Earth Observation Campaigns Data web portal](https://earth.esa.int/web/guest/campaign). 

## Format
Snow thickness measurements on sea ice are provided as a single comma delimited file with 7 columns:

*timestamp*: Time of collection in format yyyy-mm-dd hh:mm:ss GMT+5

*lat* and *lon*: Latitude and longitude in decimal degrees with WGS84 as the CRS. Please note that some measurements are on mobile sea ice and will need to be corrected to compare against satellite or airborne sensors. See Haas and others 2017 for discussion of the sheer zone location.

*depth*: Snow depth in cm. All units have been rounded to the nearest mm. Calibration steps were taken to adjust for small (mm scale) errors unique to each unit. Raw datasets are available upon request.

*unit*: Identifies the Magnaprobe unit used to collect the measurement(Units 1-4)

*site*: Identifies the site by a unique name used in the CryoVEX 2017 planning.

*rtcfail*: If true (ie a value of 1), indicates that the real time clock of the Magnaprobe failed. This will make correcting the locations for drift quite difficult but is an issue for a very limited portion of the measurements. Depth accuracy/precision is unaffected by this.

## Reference
[Haas, C., J. King, J. Beckers, A. Silis, J. Stroeve, J. Wilkinson, B. Notenboom, A. Schweiger, and S. Hendricks (2017), Ice and snow thickness variability and change in the high Arctic Ocean observed by in-situ measurements, Geophys. Res. Lett., 44(20), 462-469, doi:10.1002/2017GL075434](http://onlinelibrary.wiley.com/doi/10.1002/2017GL075434/full)


## Contact
Josh King, Research Scientist, joshua.king[at]canada.ca

## License
This dataset is licensed under the [Open Government License of Canada](http://open.canada.ca/en/open-government-licence-canada)
and is subject to the [Copyright Act of Canada](http://laws-lois.justice.gc.ca/eng/acts/C-42/index.html). Additional information can be found at the [Government of Canada's Open Government portal](http://open.canada.ca)

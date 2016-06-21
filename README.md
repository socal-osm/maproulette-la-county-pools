# maproulette-la-county-pools
Use L.A. County Assessor data to jump to a parcel with a pool and ask for it to be traced. https://data.lacounty.gov/Parcel-/Assessor-Parcels-Data-2015/hvzm-fn38 

Ken Schwencke analyzed [this data set](http://thethrust.net/diving-into-las-pools/). He found there were more than 250,000 pools. Ninety-six percent of them are behind single-family homes. 

We've started doing a few of these as test in between building uploads. Likely none of this will be "official" until the MapRoulette project moves out of beta.
- [Hollywood Hills pools 3,564](http://maproulette.org:8080/map/179/204514)
- [Hollywood pools 390](http://maproulette.org:8080/map/25/26728)
- [200 random pools at apartment buildings](http://maproulette.org:8080/map/24/26592)
- [100 pools in the San Fernando Valley](http://maproulette.org:8080/map/16/24319)

# Possible steps
After MapRoulette gets out of beta, we could:
1. Create a large point file of the "CENTER_LON" and "CENTER_LAT" fields in the L.A. County [parcel 2015 file](https://data.lacounty.gov/Parcel-/Assessor-Parcels-Data-2015/hvzm-fn38) for anything "SpecificUseDetail2" = 'Pool'
2. Split those pool points by neighborhood
3. Create MapRoulette challenges by neighborhood. 

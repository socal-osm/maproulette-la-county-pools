# maproulette-la-county-pools
Use L.A. County Assessor data to jump to a parcel with a pool and ask for it to be traced. https://data.lacounty.gov/Parcel-/Assessor-Parcels-Data-2015/hvzm-fn38 

Ken Schwencke analyzed [this data set](http://thethrust.net/diving-into-las-pools/). He found there were more than 250,000 pools. Ninety-six percent of them are behind single-family homes. 

We've started doing a few of these as test in between building uploads. Likely none of this will be "official" until the MapRoulette project moves out of beta.
- [Hollywood Hills pools 3,564](http://maproulette.org/map/179)
- [Hollywood pools 390](http://maproulette.org/map/25)
- [Silverlake and Echo Park 392](http://maproulette.org/map/199)
- [Los Feliz' 1,043 pools](http://maproulette.org/map/198)

# Possible steps
After MapRoulette gets out of beta, we could:
1. Create a large point file of the "CENTER_LON" and "CENTER_LAT" fields in the L.A. County [parcel 2015 file](https://data.lacounty.gov/Parcel-/Assessor-Parcels-Data-2015/hvzm-fn38) for anything "SpecificUseDetail2" = 'Pool'
2. Split those pool points by neighborhood
3. Create MapRoulette challenges by neighborhood. 

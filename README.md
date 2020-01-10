# Geocoding

Mostly Houston geocoding stuff

Here I will put my good, final code for geocoding from the census server,
from Google, and also from the City of Houston address file
https://cohgis-mycity.opendata.arcgis.com/datasets/coh-address-points-pdd

I need to build a new file for geocoding blocks by finding the average
location of each block in the COH file. Also could use to geocode
permit data, but with exact address.

1. read in COH data
2. Create block average location file
3. Compare to geocoding file done the hard way

For exact addresses:
  - does COH file match PVT addresses in permit file?

# SelectLocationFragment
- First I override onMapReady fun to create the map when the fragment open.
- I crate isPermissionGranted fun to check permissions from user.
- I create enableMyLocation fun to enable local location of user 
- I create setMapLongClick fun to get the location whatever user click on map
- I create setMapStyle fun to give a specific style to the map depend on json file.
- In the end I send longitude and latitude to the view model in onLocationSelected fun.
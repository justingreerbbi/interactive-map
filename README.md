# Interactive Ward & Voting Map - Justin Greer
 This script uses MapBox GL and provides an interactive map for local Goverment to use to provide information to thier Citizens.
 All code attributed outside of existsing libraries is Open Source and free to use without arrtibution. The goal is to lower the entry barrier
 for Government tools so that a better tool can be provided for information.

 ## Structure
 The script use MapBox GL as the mapping tool along with other plugins like Turf.js. You will need an access token to use this code from MapBox.

 The data used is publicly avalaible for the Wards. I have already compiled them into indivual GeoJSON arrays. There is also a GeoJSON file provided
 if you desire to use one file instead of inline code. 

 Voter Information is compiled from the Summit County Board of Elections and imported into a MySQL DB. Both raw export data and MySQL data is provide in this repo.

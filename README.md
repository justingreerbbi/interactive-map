# Interactive Ward & Voting Map - City of Barberton, Ohio 44203 
 This script uses MapBox GL and provides an interactive map for local Goverment to use to provide information to thier Citizens.
 All code attributed outside of existsing libraries is Open Source and free to use without arrtibution. The goal is to lower the entry barrier
 for Government tools so that a better tool can be provided for information.

 While this tool is free to use, I do provide special services for Municipatlies and Politican Orginizations. This tool can be adobted to you needs.

 ![Interactive Map](https://github.com/justingreerbbi/interactive-map/blob/main/assets/images/screenshot-1.png)

 ## Structure
 The script use MapBox GL as the mapping tool along with other plugins like Turf.js. You will need an access token to use this code from MapBox.

 The data used is publicly avalaible for the Wards. I have already compiled them into indivual GeoJSON arrays. There is also a GeoJSON file provided
 if you desire to use one file instead of inline code. 

 Voter Information is compiled from the Summit County Board of Elections and imported into a MySQL DB. Both raw export data and MySQL data is provide in this repo.

 ## Machine Learning / AI Integration
 This project has the ability to incorporate machine learning and artificial intelligence for different aspects of functionality.
 
 **Citizen Interaction**
 * Provide Geocoding that allows the user to pull information about them and thier ditrict or ward.
 * Preview Voting History.
 * Search by Name or Address to query informaiton.

 **Political Campaign Aspect**
 
 While the tool is really geared towards providing informaiton to the user, it can be slightly altered to use for political campaigning. These features
 are typically very exspensive but this script will allow you to have all the tools at your finger tips.

 * Group Voters into groups based on political affialtaion.
 * Provide voter predictions for both party and general voting.
 * Cluster hotspots to visually see the most poductive areas to canvas.


 ## Custom Development
 If you are in need of help for customer development solutions when it comes to this script, you are more than welcome to reach out. I should be able
 to help customize a solution for your City or Political Campaign. 

 My email is located at the top of each file in this repo.

 ## ToDo's
 
 * Add in address/name search box to get the cordinates to display othe information
 * Add in Modal or response when a location is clicked.
 * Add the ability to switch layers between ward, precinct, heatmap.
 * Add flat database wrapper for easy to use/integration into just about any server system.
 * Add layer to show party affialiation based on yearly primaries that are tracked for wards and prcincts.

 Heat Map Features

 * Ability to filter all voters, primary voters, poltical party, general voters, voters likely to vote, etc.
 



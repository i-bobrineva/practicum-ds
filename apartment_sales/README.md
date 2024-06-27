# Research on apartment sale listings
## Task
It is necessary to determine the market value of real estate based on an archive of apartment sale listings in St. Petersburg and nearby localities over several years. To do this, an exploratory data analysis needs to be conducted to identify the parameters that influence property prices. This will enable the development of an automated system that will track anomalies and fraudulent activities.
For each apartment on sale, two types of data are available. The first type is entered by the user, and the second type is obtained automatically based on cartographic data. For example, the distance to the city center, airport, and other objects — these data are automatically obtained from geoservices. The number of parks and bodies of water is also filled in without user participation.

## Data description

* airports_nearest — distance to the nearest airport in meters (m)
* balcony — number of balconies
* ceiling_height — ceiling height (m)
* cityCenters_nearest — distance to the city center (m)
* days_exposition — number of days the listing was posted (from publication to removal)
* first_day_exposition — publication date
* floor — floor
* floors_total — total number of floors in the building
* is_apartment — apartment (boolean type)
* kitchen_area — kitchen area in square meters (m²)
* last_price — price at the time of removal from publication
* living_area — living area in square meters (m²)
* locality_name — name of the locality
* open_plan — open plan (boolean type)
* parks_around3000 — number of parks within a 3 km radius
* parks_nearest — distance to the nearest park (m)
* ponds_around3000 — number of bodies of water within a 3 km radius
* ponds_nearest — distance to the nearest body of water (m)
* rooms — number of rooms
* studio — studio apartment (boolean type)
* total_area — total area of the apartment in square meters (m²)
* total_images — number of photos of the apartment in the listing

## Libraries

* pandas
* matplotlib

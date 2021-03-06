<h1> <img src="https://bexhill-osm.org.uk/favicon-32x32.png"> Bexhill OpenStreetMap - https://bexhill-osm.org.uk </h1>

[![License](https://img.shields.io/badge/license-GPL-blue.svg)](https://github.com/Dr-Mx/bexhill-osm/blob/master/LICENSE)
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=B3X9MHLW4W9TG&source=url)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fbexhill-osm.org.uk)](https://bexhill-osm.org.uk)
[![Twitter](https://img.shields.io/twitter/follow/BexhillOSM.svg?label=Twitter)](https://twitter.com/BexhillOSM)

Searchable OpenStreetMap data showing POIs, walking directions, overlays, history and other information for the town of Bexhill-on-Sea, UK

![Image of Bexhill-OSM](https://bexhill-osm.org.uk/assets/img/og-preview.jpg)

## Features
- Mobile and desktop friendly
- Mapillary Street Level spherical panorama support
- Local caching of API requests
- Detailed POI markers through Overpass API
  - Bookmark favourite POIs
  - Facility icons
    - Wheelchair (key:wheelchair)
    - Hearing induction loop (key:hearing_impaired:induction_loop)
    - Braille (key:tactile_writing:braille)
    - Internet (key:internet_access)
    - Dog friendly (key:dog)
    - Toilets (key:male, key:female, key:unisex, key:changing_table)
    - Drinking water refills (key:drinking_water:refill)
    - Recycling types (key:recycling:\*)
    - Telephone (key:sms)
    - Bus-stop (key:bin, key:bench)
    - Covered (key:covered, key:shelter)
    - Live music (key:live_music)
  - Payment parser (key:payment:\*)
  - Diet parser (key:diet:\*)
  - Cuisine parser (key:cuisine, key:breakfast, key:lunch)
  - Ordering parser (key:takeaway, key:delivery, key:outdoor_searing, key:beer_garden, key:reservation)
  - Building details (key:architect, key:building:architecture, key:start_date, key:HE_ref, key:listed_status)
  - Current open state with 7 day opening hours table (key:opening_hours)
  - Last postbox collection time state (key:collection_times)
  - UK Food Hygiene Rating System API (key:fhrs:id)
  - Real-time Traveline API information on bus-stops (key:naptan:AtcoCode)
  - Multiple image support including Wikimedia Commons API (key:wikimedia_commons, key:image)
  - Multiple spherical panorama support using Wikimedia Commons (key:wikimedia_commons:pano)
- Find an address by searching (Nominatim > Overpass)
- Query any feature on map by clicking (Nominatim > Overpass)
- Area highlight on select (OpenStreetMap API)
- Manually select groups of POIs from list or using a keyword
- POI result list with current opening_hours / collection_times state
- Detailed walking directions with Mapbox API
- Geolocate user and show distances from POIs
- History Tour articles that link to various overlays on the map
- Direct link to edit an element on OSM or leave a note
- Share any current map state with dynamic permalink
- Map display
  - Switch between metric and imperial
  - Adjustable themes / Dark theme
  - Adjust overlay opacity
  - Set overlay offset
- OpenWeatherMap API
- Various debugging tools

## Attribution

Originally forked from:
 - https://github.com/humitos/osm-pois (Humitos)

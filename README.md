# maps.bikeottawa.ca-frontend
Static frontend for maps.bikeottawa.ca.
Requires [maps.bikeottawa.ca-backend](https://github.com/BikeOttawa/maps.bikeottawa.ca-backend) to run on the server for Routing and Isochrones apps to work

## Features 6 maps
- Level of Stress map for Ottawa
- Cycling routing app, where one can choose acceptable level of stress for the route between LTS-1 and LTS-4
- Cycling Isochrones app that shows where you can bike within 3-6-9-12-15 minutes on LTS1/2/3/4 roads
- Winter cycling map that shows which pathways are cleared and allows to submit winter clearing status
- Map of desire lines
- Collision map for years 2014-2016 based on the city collision open data

## Tokens
The frontend requires Mapbox and Mapillary tokens to function. Place these in `js/tokens.js`. There is a `js/tokens.js.example` you can use as a template.

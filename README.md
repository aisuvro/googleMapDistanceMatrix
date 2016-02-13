# googleMapDistanceMatrix
use http connection to retrieve the google distance in json 


Url
https://maps.googleapis.com/maps/api/distancematrix/json?origins=23.75223408437255,90.37963235475122&destinations=23.758761375530757,90.37364904989002&mode=walking


Url parssing:
https://maps.googleapis.com/maps/api/distancematrix/json
?origins=23.75223408437255,90.37963235475122
&destinations=23.758761375530757,90.37364904989002
&mode=walking


<h3>Travel Modes</h3>

For the calculation of distances, you may specify the transportation mode to use. By default, distances are calculated for driving mode. The following travel modes are supported:

driving (default) indicates distance calculation using the road network.
walking requests distance calculation for walking via pedestrian paths & sidewalks (where available).
bicycling requests distance calculation for bicycling via bicycle paths & preferred streets (where available).
transit requests distance calculation via public transit routes (where available). This value may only be specified if the request includes an API key or a Google Maps APIs Premium Plan client ID. If you set the mode to transit you can optionally specify either a departure_time or an arrival_time. If neither time is specified, the departure_time defaults to now (that is, the departure time defaults to the current time). You can also optionally include a transit_mode and/or a transit_routing_preference.
Note: Both walking and bicycling routes may sometimes not include clear pedestrian or bicycling paths, so these responses will return warnings in the returned result which you must display to the user.

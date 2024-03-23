# Fetch GPX-Tracks from EuroVelo-Website

We obtain the data from:

```text
https://en.eurovelo.com
```

On the EuroVelo website there is a `GET` method "hidden" at the path `route/get-gpx/<id>`. Unfortunately, so far we couldn't find the method which provides the list with the IDs. Hence, in the following we took the brute force approach and tried IDs from 0 to N.


Regarding the GPX data wrangling, we took inspiration from:

* https://thatmaceguy.github.io/python/gps-data-analysis-intro/
* https://towardsdatascience.com/data-science-for-cycling-how-to-read-gpx-strava-routes-with-python-e45714d5da23
* https://towardsdatascience.com/visualizing-geospatial-data-in-python-e070374fe621
* https://towardsdatascience.com/simple-gps-data-visualization-using-python-and-open-street-maps-50f992e9b676
* https://towardsdatascience.com/geopandas-101-plot-any-data-with-a-latitude-and-longitude-on-a-map-98e01944b972

(TODO) For the interaction with Garmin Connect:

* https://github.com/matin/garth
* https://github.com/cyberjunky/python-garminconnect
* https://github.com/cpfair/tapiriik/blob/ee0153818981863e19750d59727d77363e5a37fe/tapiriik/services/GarminConnect/garminconnect.py#L548
* https://medium.com/@rama_m/how-to-download-garmin-training-data-using-python-api-5e94488a2317
* https://github.com/Pythe1337N/garmin-connect
* https://github.com/abrander/garmin-connect
* https://developer.garmin.com/gc-developer-program/activity-api/

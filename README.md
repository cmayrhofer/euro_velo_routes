# Fetch GPX-Tracks from EuroVelo-Website

We obtain the data from:

```text
https://en.eurovelo.com/#
```

On the website the there is a `GET` method hidden, i.e. `https://en.eurovelo.com/route/get-gpx/<id>`. Unfortunately, so far I couldn't find a list with the IDs. Hence, in the following we took the brute force approach and tried IDs from 0 to N.

Regarding the GPX data wrangling, we too inspiration from:

* https://thatmaceguy.github.io/python/gps-data-analysis-intro/
* https://towardsdatascience.com/data-science-for-cycling-how-to-read-gpx-strava-routes-with-python-e45714d5da23
* https://towardsdatascience.com/visualizing-geospatial-data-in-python-e070374fe621
* https://towardsdatascience.com/simple-gps-data-visualization-using-python-and-open-street-maps-50f992e9b676
* https://towardsdatascience.com/geopandas-101-plot-any-data-with-a-latitude-and-longitude-on-a-map-98e01944b972

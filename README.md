# Analyzing Car Break-ins in San Francisco (WIP)
When a joke between friends turns into a data-driven approach to analyzing theft in San Francisco...

# Instructions
## Step 1 - API:
Create an API key in [Google Cloud Computing](https://console.cloud.google.com/flows/enableapi?apiid=maps_backend,geocoding_backend,directions_backend,distance_matrix_backend,elevation_backend&keyType=CLIENT_SIDE&reusekey=true). Make sure to enable APIs.

Load key into environment variables (~/.bash_profile):
```
export GOOGLE_API_KEY=AI...
```

More details can be found *[here](https://jupyter-gmaps.readthedocs.io/en/latest/authentication.html)*.

## Step 2 - Installation:
Enable ipywidgets widgets extensions:
```
$ jupyter nbextension enable --py --sys-prefix widgetsnbextension
```

Then install gmaps:
```
$ pip install gmaps
```

Finally tell Jupyter to load the extensions:
```
$ jupyter nbextension enable --py --sys-prefix gmaps
```

More details can be found *[here](https://jupyter-gmaps.readthedocs.io/en/latest/install.html)*.
Note: As of 2018, Gmaps is no longer free. You need to put in your billing but you get a free $300 credit. Up to you to use gmaps or another API thats free such as OpenStreetMaps.

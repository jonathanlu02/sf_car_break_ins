# Analyzing Car Break-ins in San Francisco
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

# Result
<img src="/Figures/breakins2.png"/>
The majority of vehicle break-ins occur in popular tourist areas like Fisherman's Wharf, Lombard Street, Japantown. Van Ness Ave is also a large street full of retail and shops. This makes it a prime place for thieves to steal from unsuspecting shoppers and tourists. Even Unions Square, a high-end retail location, is a vulnerable target. The brazen and coordinated smash-and-grab ring that made headlines in November 2021 is proof of that.

# python-api-challenge
The assignment has two parts, WeatherPy and VacationPy.
## Weather Py
The goal was to consider the relationship of four weather metrics to latitude.
### Observations
* Duh!  It gets colder as one travels from the equator to either pole.
* Temperature vary widely, as much as forty degrees, along a single line of latitude.  There is likely additional variables, outside of this study, that determines temperature.
* The results of this study are dependendent on the date on which it is conducted.  With winter prevailing in the Northern Hemisphere, temperature correlates strongly with latitude.
* Cloudiness and humidity do not appear to be correlated with latitude.
* Wind speed is poorly correlated with latitude, but the poles might be windier.
* Despite the efforts to distribute the sample cities across the range of latitudes, the percentage of sample cities in the northern hemisphere was roughly equivalent to the percentage of land mass in the northern hemisphere, 68%.
## Vacation PY
* The goal was to locate cities with stereoptyically "ideal" weather, and a nearby hotel.
### Observations
* Only a few cities met the criteria.
* These cities were nicely distributed between the hemispheres.  The distribution might change if the study was re-done in September.
* You may want a tent for some of these cities, where no hotels were found within a 5 km radius.
#### Notes on the citypy module
For my future reference, these are the steps I took to install the citypy module:
* Google for citypy
* Use this URL  https://pypi.org/project/citipy/
* Download Files (I downloaded a file named "citipy-0.0.5.tar.gz".)
* At an Anaconda command prompt, run this command:
> pip install .\Downloads\citipy-0.0.5.tar.gz
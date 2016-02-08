# APIspec

The endpoint
```
/<buildingid>/<floorid>
```
should give something similar to [this](../master/floor.json).
Fill color for the polygons should be calculated server-side based on sensor data.
The sensor specific properties are all optional, i.e. only exists if there is actual data available for that property.


The endpoint
```
/<buildingid>/<floorid>/<roomid>/<period>
```
should give something similar to [this](../master/history.json).
The arrays contain averages based on the specified period.
The period could perhaps be "day", "week", "month".
Again only properties that have data are shown.


There should be some kind of support for arbitrary sensor properties.

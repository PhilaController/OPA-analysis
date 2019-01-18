# OPA Zone Boundaries

This directory holds the shape file for the OPA's geographic zone definitions. It can be loaded using [geopandas](http://geopandas.org):

```python
import geopandas as gpd
gdf = gpd.GeoDataFrame.from_file(".")
```

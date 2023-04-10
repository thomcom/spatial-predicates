
# Feature relations

This repository contains a series of Jupyter notebooks that
build up all the possible feature relations that can exist
between

    (Point, LineString)
    (Point, Polygon)
    (LineString, Polygon)
    (Polygon, Polygon)

In [PolygonPolygon.ipynb](./PolygonPolygon.ipynb), all of the
possible relationships between two Polygons is generated
programmatically.

In [PolygonPolygonWithHoles.ipynb](./PolygonPolygonWithHoles.ipynb) all of the
possible relationships between a polygon with holes and another polygon is
generated programmatically. Only one result is reported per `ST_Relates`
relationship between the two polygons.

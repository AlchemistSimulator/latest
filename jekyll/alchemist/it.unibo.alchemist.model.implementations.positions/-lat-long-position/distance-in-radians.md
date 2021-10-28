---
title: distanceInRadians
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.positions](../index.html)/[LatLongPosition](index.html)/[distanceInRadians](distance-in-radians.html)



# distanceInRadians



[jvm]\
open fun [distanceInRadians](distance-in-radians.html)(point1: LatLng, point2: LatLng, precision: [LatLongPosition.DistanceFormula](-distance-formula/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)



 This "distance" function is mostly for internal use. Most users will simply rely upon [distance](distance.html)



 Yields the internal angle for an arc between two points on the surface of a sphere in radians. This angle is in the plane of the great circle connecting the two points measured from an axis through one of the points and the center of the Earth. Multiply this value by the sphere's radius to get the length of the arc. 



#### Return



the internal angle for the arc connecting the two points in radians.



## Parameters


jvm

| | |
|---|---|
| point1 | the first point |
| point2 | the second point |
| precision | the formula to use |




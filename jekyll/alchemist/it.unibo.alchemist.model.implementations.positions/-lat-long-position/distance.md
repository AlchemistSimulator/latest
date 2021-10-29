---
title: distance
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.positions](../index.html)/[LatLongPosition](index.html)/[distance](distance.html)



# distance



[jvm]\
open fun [distance](distance.html)(point1: LatLng, point2: LatLng, df: [LatLongPosition.DistanceFormula](-distance-formula/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)



Distance between two points.



#### Return



the distance in the chosen unit of measure.



## Parameters


jvm

| | |
|---|---|
| point1 | the first point. |
| point2 | the second point. |
| df | the formula to use to compute distances |





[jvm]\
open fun [distance](distance.html)(point1: LatLng, point2: LatLng, unit: LengthUnit, df: [LatLongPosition.DistanceFormula](-distance-formula/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)



Distance between two points with arbitrary LengthUnit.



#### Return



the distance in the chosen unit of measure.



## Parameters


jvm

| | |
|---|---|
| point1 | the first point. |
| point2 | the second point. |
| unit | the unit of measure in which to receive the result. |
| df | the formula to use to compute distances |





---
title: it.unibo.alchemist.model.implementations.positions
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.positions](index.html)



# Package it.unibo.alchemist.model.implementations.positions



[jvm]\
Position implementations.



## Types


| Name | Summary |
|---|---|
| [AbstractEuclideanPosition](-abstract-euclidean-position/index.html) | [jvm]<br>abstract class [AbstractEuclideanPosition](-abstract-euclidean-position/index.html)<[P](-abstract-euclidean-position/index.html) : [AbstractEuclideanPosition](-abstract-euclidean-position/index.html)<[P](-abstract-euclidean-position/index.html)>?> : [AbstractPosition](-abstract-position/index.html)<[P](-abstract-euclidean-position/index.html)> , [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](-abstract-euclidean-position/index.html)> <br>N-dimensional Euclidean position. |
| [AbstractPosition](-abstract-position/index.html) | [jvm]<br>abstract class [AbstractPosition](-abstract-position/index.html)<[P](-abstract-position/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>?> : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> <br>N-dimensional position. |
| [Euclidean2DPosition](-euclidean2-d-position/index.html) | [jvm]<br>class [Euclidean2DPosition](-euclidean2-d-position/index.html) : [AbstractEuclideanPosition](-abstract-euclidean-position/index.html)<[Euclidean2DPosition](-euclidean2-d-position/index.html)> , [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[Euclidean2DPosition](-euclidean2-d-position/index.html)> , [Vector2D](../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.html)<[Euclidean2DPosition](-euclidean2-d-position/index.html)> |
| [GPSPointImpl](-g-p-s-point-impl/index.html) | [jvm]<br>class [GPSPointImpl](-g-p-s-point-impl/index.html) : [GPSPoint](../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html) |
| [LatLongPosition](-lat-long-position/index.html) | [jvm]<br>class [LatLongPosition](-lat-long-position/index.html) : [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html)<br>Unmodifiable state version of LatLng, also implementing the [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.html) interface. |


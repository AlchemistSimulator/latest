//[alchemist](../../index.md)/[it.unibo.alchemist.model.implementations.positions](index.md)

# Package it.unibo.alchemist.model.implementations.positions

[jvm]\
Position implementations.

## Types

| Name | Summary |
|---|---|
| [AbstractEuclideanPosition](-abstract-euclidean-position/index.md) | [jvm]<br>abstract class [AbstractEuclideanPosition](-abstract-euclidean-position/index.md)<[P](-abstract-euclidean-position/index.md) : [AbstractEuclideanPosition](-abstract-euclidean-position/index.md)<[P](-abstract-euclidean-position/index.md)>?> : [AbstractPosition](-abstract-position/index.md)<[P](-abstract-euclidean-position/index.md)> , [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](-abstract-euclidean-position/index.md)> <br>N-dimensional Euclidean position. |
| [AbstractPosition](-abstract-position/index.md) | [jvm]<br>abstract class [AbstractPosition](-abstract-position/index.md)<[P](-abstract-position/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)>?> : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../it.unibo.alchemist.model.implementations.movestrategies.speed/-interact-with-others/index.md)> <br>N-dimensional position. |
| [Euclidean2DPosition](-euclidean2-d-position/index.md) | [jvm]<br>class [Euclidean2DPosition](-euclidean2-d-position/index.md) : [AbstractEuclideanPosition](-abstract-euclidean-position/index.md)<[Euclidean2DPosition](-euclidean2-d-position/index.md)> , [Position2D](../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[Euclidean2DPosition](-euclidean2-d-position/index.md)> , [Vector2D](../it.unibo.alchemist.model.interfaces.geometry/-vector2-d/index.md)<[Euclidean2DPosition](-euclidean2-d-position/index.md)> |
| [GPSPointImpl](-g-p-s-point-impl/index.md) | [jvm]<br>class [GPSPointImpl](-g-p-s-point-impl/index.md) : [GPSPoint](../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md) |
| [LatLongPosition](-lat-long-position/index.md) | [jvm]<br>class [LatLongPosition](-lat-long-position/index.md) : [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.md)<br>Unmodifiable state version of LatLng, also implementing the [GeoPosition](../it.unibo.alchemist.model.interfaces/-geo-position/index.md) interface. |

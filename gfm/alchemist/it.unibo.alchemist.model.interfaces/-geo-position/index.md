//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[GeoPosition](index.md)

# GeoPosition

[jvm]\
interface [GeoPosition](index.md) : [Position2D](../-position2-d/index.md)<[GeoPosition](index.md)> 

Represents a specific point on the Earth's surface.

## Functions

| Name | Summary |
|---|---|
| [boundingBox](../-g-p-s-point/index.md#-1470108373%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [boundingBox](../-g-p-s-point/index.md#-1470108373%2FFunctions%2F-267951372)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../-incarnation/index.md)><br>Given a range, produces N coordinates, representing the N opposite vertices of the hypercube having the current coordinate as center and circumscribing the N-sphere defined by the range. |
| [distanceTo](../-g-p-s-point/index.md#-346428117%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [distanceTo](../-g-p-s-point/index.md#-346428117%2FFunctions%2F-267951372)(otherPosition: [P](../-incarnation/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between this position and another compatible position. |
| [getCoordinate](get-coordinate.md) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~abstract~~ ~~fun~~ [~~getCoordinate~~](get-coordinate.md)~~(~~~~dim~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~~~:~~ [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Allows to access the value of a coordinate. |
| [getCoordinates](../-g-p-s-point/index.md#1594970258%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getCoordinates](../-g-p-s-point/index.md#1594970258%2FFunctions%2F-267951372)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Allows to get the position as a Number array. |
| [getDimensions](../-g-p-s-point/index.md#-269418464%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getDimensions](../-g-p-s-point/index.md#-269418464%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLatitude](get-latitude.md) | [jvm]<br>abstract fun [getLatitude](get-latitude.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the latitude |
| [getLongitude](get-longitude.md) | [jvm]<br>abstract fun [getLongitude](get-longitude.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the longitude |
| [getX](../-g-p-s-point/index.md#-585176761%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getX](../-g-p-s-point/index.md#-585176761%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getY](../-g-p-s-point/index.md#-554156954%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getY](../-g-p-s-point/index.md#-554156954%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [minus](minus.md) | [jvm]<br>abstract fun [minus](minus.md)(other: [GeoPosition](index.md)): [GeoPosition](index.md)<br>Subtracts the provided [GeoPosition](index.md) from this [GeoPosition](index.md).<br>[jvm]<br>abstract fun [minus](../-g-p-s-point/index.md#1854457792%2FFunctions%2F-267951372)(other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](../-incarnation/index.md)<br>Considers both positions as vectors, and returns the difference between this position and the passed one. |
| [plus](plus.md) | [jvm]<br>abstract fun [plus](plus.md)(other: [GeoPosition](index.md)): [GeoPosition](index.md)<br>Adds two [GeoPosition](index.md).<br>[jvm]<br>abstract fun [plus](../-g-p-s-point/index.md#-1455048310%2FFunctions%2F-267951372)(other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](../-incarnation/index.md)<br>Considers both positions as vectors, and sums them. |

## Inheritors

| Name |
|---|
| [GPSPoint](../-g-p-s-point/index.md) |
| [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.md) |

## Extensions

| Name | Summary |
|---|---|
| [toLatLong](../../it.unibo.alchemist.wormhole.implementation/to-lat-long.md) | [jvm]<br>fun [GeoPosition](index.md).[toLatLong](../../it.unibo.alchemist.wormhole.implementation/to-lat-long.md)(): LatLong<br>Converts [this](index.md) to LatLong. |

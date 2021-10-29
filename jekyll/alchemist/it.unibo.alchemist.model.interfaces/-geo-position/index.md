---
title: GeoPosition
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[GeoPosition](index.html)



# GeoPosition



[jvm]\
interface [GeoPosition](index.html) : [Position2D](../-position2-d/index.html)<[GeoPosition](index.html)> 

Represents a specific point on the Earth's surface.



## Functions


| Name | Summary |
|---|---|
| [boundingBox](../-g-p-s-point/index.html#-1470108373%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [boundingBox](../-g-p-s-point/index.html#-1470108373%2FFunctions%2F-134779887)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)><br>Given a range, produces N coordinates, representing the N opposite vertices of the hypercube having the current coordinate as center and circumscribing the N-sphere defined by the range. |
| [distanceTo](../-g-p-s-point/index.html#-346428117%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [distanceTo](../-g-p-s-point/index.html#-346428117%2FFunctions%2F-134779887)(otherPosition: [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the distance between this position and another compatible position. |
| [getCoordinate](get-coordinate.html) | [jvm]<br>@[Deprecated](https://docs.oracle.com/javase/8/docs/api/java/lang/Deprecated.html)()<br>~~abstract~~ ~~fun~~ [~~getCoordinate~~](get-coordinate.html)~~(~~~~dim~~~~:~~ [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)~~)~~~~:~~ [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Allows to access the value of a coordinate. |
| [getCoordinates](../-g-p-s-point/index.html#1594970258%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getCoordinates](../-g-p-s-point/index.html#1594970258%2FFunctions%2F-134779887)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Allows to get the position as a Number array. |
| [getDimensions](../-g-p-s-point/index.html#-269418464%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getDimensions](../-g-p-s-point/index.html#-269418464%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLatitude](get-latitude.html) | [jvm]<br>abstract fun [getLatitude](get-latitude.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the latitude |
| [getLongitude](get-longitude.html) | [jvm]<br>abstract fun [getLongitude](get-longitude.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>the longitude |
| [getX](../-g-p-s-point/index.html#-585176761%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getX](../-g-p-s-point/index.html#-585176761%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getY](../-g-p-s-point/index.html#-554156954%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getY](../-g-p-s-point/index.html#-554156954%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [minus](minus.html) | [jvm]<br>abstract fun [minus](minus.html)(other: [GeoPosition](index.html)): [GeoPosition](index.html)<br>Subtracts the provided [GeoPosition](index.html) from this [GeoPosition](index.html).<br>[jvm]<br>abstract fun [minus](../-g-p-s-point/index.html#1854457792%2FFunctions%2F-134779887)(other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<br>Considers both positions as vectors, and returns the difference between this position and the passed one. |
| [plus](plus.html) | [jvm]<br>abstract fun [plus](plus.html)(other: [GeoPosition](index.html)): [GeoPosition](index.html)<br>Adds two [GeoPosition](index.html).<br>[jvm]<br>abstract fun [plus](../-g-p-s-point/index.html#-1455048310%2FFunctions%2F-134779887)(other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](../../it.unibo.alchemist.boundary.interfaces/-output-monitor/index.html)<br>Considers both positions as vectors, and sums them. |


## Inheritors


| Name |
|---|
| [GPSPoint](../-g-p-s-point/index.html) |
| [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.html) |


## Extensions


| Name | Summary |
|---|---|
| [toLatLong](../../it.unibo.alchemist.wormhole.implementation/to-lat-long.html) | [jvm]<br>fun [GeoPosition](index.html).[toLatLong](../../it.unibo.alchemist.wormhole.implementation/to-lat-long.html)(): LatLong<br>Converts [this](index.html) to LatLong. |


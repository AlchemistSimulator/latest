---
title: GPSPointImpl
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.positions](../index.html)/[GPSPointImpl](index.html)



# GPSPointImpl



[jvm]\
class [GPSPointImpl](index.html) : [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html)



## Constructors


| | |
|---|---|
| [GPSPointImpl](-g-p-s-point-impl.html) | [jvm]<br>open fun [GPSPointImpl](-g-p-s-point-impl.html)(latitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), longitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html))<br>latitude |
| [GPSPointImpl](-g-p-s-point-impl.html) | [jvm]<br>open fun [GPSPointImpl](-g-p-s-point-impl.html)(latlong: [LatLongPosition](../-lat-long-position/index.html), time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html))<br>latitude and longitude |


## Functions


| Name | Summary |
|---|---|
| [addTime](add-time.html) | [jvm]<br>open fun [addTime](add-time.html)(t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [GPSPointImpl](index.html)<br>time to add to the point's time |
| [boundingBox](bounding-box.html) | [jvm]<br>open fun [boundingBox](bounding-box.html)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)> |
| [compareTo](compare-to.html) | [jvm]<br>open fun [compareTo](compare-to.html)(p: [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [distanceTo](distance-to.html) | [jvm]<br>open fun [distanceTo](distance-to.html)(otherPosition: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getCoordinate](get-coordinate.html) | [jvm]<br>open fun [getCoordinate](get-coordinate.html)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinates](get-coordinates.html) | [jvm]<br>open fun [getCoordinates](get-coordinates.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getDimensions](get-dimensions.html) | [jvm]<br>open fun [getDimensions](get-dimensions.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLatitude](get-latitude.html) | [jvm]<br>open fun [getLatitude](get-latitude.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getLongitude](get-longitude.html) | [jvm]<br>open fun [getLongitude](get-longitude.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getTime](get-time.html) | [jvm]<br>open fun [getTime](get-time.html)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)<br>the time |
| [getX](get-x.html) | [jvm]<br>open fun [getX](get-x.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getY](get-y.html) | [jvm]<br>open fun [getY](get-y.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [minus](minus.html) | [jvm]<br>@NotNull()<br>open fun [minus](minus.html)(@NotNull()other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)<br>open fun [minus](minus.html)(other: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html) |
| [plus](plus.html) | [jvm]<br>@NotNull()<br>open fun [plus](plus.html)(@NotNull()other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)<br>open fun [plus](plus.html)(other: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html) |
| [subtractTime](subtract-time.html) | [jvm]<br>open fun [subtractTime](subtract-time.html)(t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.html)): [GPSPointImpl](index.html)<br>time to subtract to the point's time |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |


//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.positions](../index.md)/[GPSPointImpl](index.md)

# GPSPointImpl

[jvm]\
class [GPSPointImpl](index.md) : [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md)

## Constructors

| | |
|---|---|
| [GPSPointImpl](-g-p-s-point-impl.md) | [jvm]<br>open fun [GPSPointImpl](-g-p-s-point-impl.md)(latitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), longitude: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))<br>latitude |
| [GPSPointImpl](-g-p-s-point-impl.md) | [jvm]<br>open fun [GPSPointImpl](-g-p-s-point-impl.md)(latlong: [LatLongPosition](../-lat-long-position/index.md), time: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md))<br>latitude and longitude |

## Functions

| Name | Summary |
|---|---|
| [addTime](add-time.md) | [jvm]<br>open fun [addTime](add-time.md)(t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [GPSPointImpl](index.md)<br>time to add to the point's time |
| [boundingBox](bounding-box.md) | [jvm]<br>open fun [boundingBox](bounding-box.md)(range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)> |
| [compareTo](compare-to.md) | [jvm]<br>open fun [compareTo](compare-to.md)(p: [GPSPoint](../../it.unibo.alchemist.model.interfaces/-g-p-s-point/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [distanceTo](distance-to.md) | [jvm]<br>open fun [distanceTo](distance-to.md)(otherPosition: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getCoordinate](get-coordinate.md) | [jvm]<br>open fun [getCoordinate](get-coordinate.md)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinates](get-coordinates.md) | [jvm]<br>open fun [getCoordinates](get-coordinates.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getDimensions](get-dimensions.md) | [jvm]<br>open fun [getDimensions](get-dimensions.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLatitude](get-latitude.md) | [jvm]<br>open fun [getLatitude](get-latitude.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getLongitude](get-longitude.md) | [jvm]<br>open fun [getLongitude](get-longitude.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getTime](get-time.md) | [jvm]<br>open fun [getTime](get-time.md)(): [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)<br>the time |
| [getX](get-x.md) | [jvm]<br>open fun [getX](get-x.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getY](get-y.md) | [jvm]<br>open fun [getY](get-y.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [minus](minus.md) | [jvm]<br>@NotNull()<br>open fun [minus](minus.md)(@NotNull()other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)<br>open fun [minus](minus.md)(other: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md) |
| [plus](plus.md) | [jvm]<br>@NotNull()<br>open fun [plus](plus.md)(@NotNull()other: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): @NotNull()[GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)<br>open fun [plus](plus.md)(other: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md) |
| [subtractTime](subtract-time.md) | [jvm]<br>open fun [subtractTime](subtract-time.md)(t: [Time](../../it.unibo.alchemist.model.interfaces/-time/index.md)): [GPSPointImpl](index.md)<br>time to subtract to the point's time |
| [toString](to-string.md) | [jvm]<br>open fun [toString](to-string.md)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |

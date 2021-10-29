//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[GPSPoint](index.md)

# GPSPoint

[jvm]\
interface [GPSPoint](index.md) : [GeoPosition](../-geo-position/index.md), [Comparable](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html)<[GPSPoint](index.md)>

## Functions

| Name | Summary |
|---|---|
| [addTime](add-time.md) | [jvm]<br>abstract fun [addTime](add-time.md)(t: [Time](../-time/index.md)): [GPSPoint](index.md)<br>time to add to the point's time |
| [boundingBox](index.md#-1470108373%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [boundingBox](index.md#-1470108373%2FFunctions%2F-267951372)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)> |
| [compareTo](index.md#-1554281679%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [compareTo](index.md#-1554281679%2FFunctions%2F-267951372)(p: [T](../../it.unibo.alchemist.model.implementations.linkingrules/-link-nodes-within-routing-range/index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [distanceTo](index.md#-346428117%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [distanceTo](index.md#-346428117%2FFunctions%2F-267951372)(p: [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinate](../-geo-position/get-coordinate.md) | [jvm]<br>abstract fun [getCoordinate](../-geo-position/get-coordinate.md)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinates](index.md#1594970258%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getCoordinates](index.md#1594970258%2FFunctions%2F-267951372)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getDimensions](index.md#-269418464%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getDimensions](index.md#-269418464%2FFunctions%2F-267951372)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLatitude](../-geo-position/get-latitude.md) | [jvm]<br>abstract fun [getLatitude](../-geo-position/get-latitude.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getLongitude](../-geo-position/get-longitude.md) | [jvm]<br>abstract fun [getLongitude](../-geo-position/get-longitude.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getTime](get-time.md) | [jvm]<br>abstract fun [getTime](get-time.md)(): [Time](../-time/index.md)<br>the time |
| [getX](index.md#-585176761%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getX](index.md#-585176761%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getY](index.md#-554156954%2FFunctions%2F-267951372) | [jvm]<br>abstract fun [getY](index.md#-554156954%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [minus](../-geo-position/minus.md) | [jvm]<br>abstract fun [minus](../-geo-position/minus.md)(p: [GeoPosition](../-geo-position/index.md)): [GeoPosition](../-geo-position/index.md)<br>abstract fun [minus](index.md#1854457792%2FFunctions%2F-267951372)(p: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md) |
| [plus](../-geo-position/plus.md) | [jvm]<br>abstract fun [plus](../-geo-position/plus.md)(p: [GeoPosition](../-geo-position/index.md)): [GeoPosition](../-geo-position/index.md)<br>abstract fun [plus](index.md#-1455048310%2FFunctions%2F-267951372)(p: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.md) |
| [subtractTime](subtract-time.md) | [jvm]<br>abstract fun [subtractTime](subtract-time.md)(t: [Time](../-time/index.md)): [GPSPoint](index.md)<br>time to subtract to the point's time |

## Inheritors

| Name |
|---|
| [GPSPointImpl](../../it.unibo.alchemist.model.implementations.positions/-g-p-s-point-impl/index.md) |

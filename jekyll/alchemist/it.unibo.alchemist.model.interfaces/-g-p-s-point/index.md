---
title: GPSPoint
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[GPSPoint](index.html)



# GPSPoint



[jvm]\
interface [GPSPoint](index.html) : [GeoPosition](../-geo-position/index.html), [Comparable](https://docs.oracle.com/javase/8/docs/api/java/lang/Comparable.html)<[GPSPoint](index.html)>



## Functions


| Name | Summary |
|---|---|
| [addTime](add-time.html) | [jvm]<br>abstract fun [addTime](add-time.html)(t: [Time](../-time/index.html)): [GPSPoint](index.html)<br>time to add to the point's time |
| [boundingBox](index.html#-1470108373%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [boundingBox](index.html#-1470108373%2FFunctions%2F-134779887)(p: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[P](../../it.unibo.alchemist.loader.deployments/-deployment/index.html)> |
| [compareTo](index.html#-1554281679%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [compareTo](index.html#-1554281679%2FFunctions%2F-134779887)(p: [T](../../it.unibo.alchemist.model.implementations.movestrategies.target/-follow-target-on-map/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [distanceTo](index.html#-346428117%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [distanceTo](index.html#-346428117%2FFunctions%2F-134779887)(p: [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinate](../-geo-position/get-coordinate.html) | [jvm]<br>abstract fun [getCoordinate](../-geo-position/get-coordinate.html)(p: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinates](index.html#1594970258%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getCoordinates](index.html#1594970258%2FFunctions%2F-134779887)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getDimensions](index.html#-269418464%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getDimensions](index.html#-269418464%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLatitude](../-geo-position/get-latitude.html) | [jvm]<br>abstract fun [getLatitude](../-geo-position/get-latitude.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getLongitude](../-geo-position/get-longitude.html) | [jvm]<br>abstract fun [getLongitude](../-geo-position/get-longitude.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getTime](get-time.html) | [jvm]<br>abstract fun [getTime](get-time.html)(): [Time](../-time/index.html)<br>the time |
| [getX](index.html#-585176761%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getX](index.html#-585176761%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getY](index.html#-554156954%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [getY](index.html#-554156954%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [minus](../-geo-position/minus.html) | [jvm]<br>abstract fun [minus](../-geo-position/minus.html)(p: [GeoPosition](../-geo-position/index.html)): [GeoPosition](../-geo-position/index.html)<br>abstract fun [minus](index.html#1854457792%2FFunctions%2F-134779887)(p: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.html) |
| [plus](../-geo-position/plus.html) | [jvm]<br>abstract fun [plus](../-geo-position/plus.html)(p: [GeoPosition](../-geo-position/index.html)): [GeoPosition](../-geo-position/index.html)<br>abstract fun [plus](index.html#-1455048310%2FFunctions%2F-134779887)(p: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)>): [P](../../it.unibo.alchemist.loader.deployments/-deployment/index.html) |
| [subtractTime](subtract-time.html) | [jvm]<br>abstract fun [subtractTime](subtract-time.html)(t: [Time](../-time/index.html)): [GPSPoint](index.html)<br>time to subtract to the point's time |


## Inheritors


| Name |
|---|
| [GPSPointImpl](../../it.unibo.alchemist.model.implementations.positions/-g-p-s-point-impl/index.html) |


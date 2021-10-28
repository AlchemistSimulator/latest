---
title: MapUtils
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.utils](../index.html)/[MapUtils](index.html)



# MapUtils



[jvm]\
class [MapUtils](index.html)



## Functions


| Name | Summary |
|---|---|
| [getDestinationLocation](get-destination-location.html) | [jvm]<br>open fun [getDestinationLocation](get-destination-location.html)(start: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), initialBearing: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dist: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.html)<br>open fun [getDestinationLocation](get-destination-location.html)(start: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), end: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), dist: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.html)<br>initial position |
| [getDistance](get-distance.html) | [jvm]<br>open fun [getDistance](get-distance.html)(p1: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), p2: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Returns the distance in meters. |
| [initialBearing](initial-bearing.html) | [jvm]<br>open fun [initialBearing](initial-bearing.html)(start: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), end: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>initial position |
| [toLatLng](to-lat-lng.html) | [jvm]<br>open fun [toLatLng](to-lat-lng.html)(p: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html)): LatLng<br>Converts [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html) to LatLng. |
| [toLatLong](to-lat-long.html) | [jvm]<br>open fun [toLatLong](to-lat-long.html)(p: LatLng): [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.html)<br>Converts LatLng to [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.html). |


//[alchemist](../../../index.md)/[it.unibo.alchemist.utils](../index.md)/[MapUtils](index.md)

# MapUtils

[jvm]\
class [MapUtils](index.md)

## Functions

| Name | Summary |
|---|---|
| [getDestinationLocation](get-destination-location.md) | [jvm]<br>open fun [getDestinationLocation](get-destination-location.md)(start: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), initialBearing: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dist: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.md)<br>open fun [getDestinationLocation](get-destination-location.md)(start: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), end: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), dist: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.md)<br>initial position |
| [getDistance](get-distance.md) | [jvm]<br>open fun [getDistance](get-distance.md)(p1: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), p2: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Returns the distance in meters. |
| [initialBearing](initial-bearing.md) | [jvm]<br>open fun [initialBearing](initial-bearing.md)(start: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), end: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>initial position |
| [toLatLng](to-lat-lng.md) | [jvm]<br>open fun [toLatLng](to-lat-lng.md)(p: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): LatLng<br>Converts [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md) to LatLng. |
| [toLatLong](to-lat-long.md) | [jvm]<br>open fun [toLatLong](to-lat-long.md)(p: LatLng): [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.md)<br>Converts LatLng to [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.md). |

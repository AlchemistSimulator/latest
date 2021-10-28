//[alchemist](../../../index.md)/[it.unibo.alchemist.utils](../index.md)/[MapUtils](index.md)/[getDestinationLocation](get-destination-location.md)

# getDestinationLocation

[jvm]\
open fun [getDestinationLocation](get-destination-location.md)(start: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), initialBearing: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dist: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.md)

#### Return

the actual destination

## Parameters

jvm

| | |
|---|---|
| start | initial position |
| initialBearing | the initial bearing |
| dist | maximum walkable length |

[jvm]\
open fun [getDestinationLocation](get-destination-location.md)(start: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), end: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md), dist: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.md)

#### Return

the actual destination

## Parameters

jvm

| | |
|---|---|
| start | initial position |
| end | final position |
| dist | maximum walkable length |

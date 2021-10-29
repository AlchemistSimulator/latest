---
title: getDestinationLocation
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.utils](../index.html)/[MapUtils](index.html)/[getDestinationLocation](get-destination-location.html)



# getDestinationLocation



[jvm]\
open fun [getDestinationLocation](get-destination-location.html)(start: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), initialBearing: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), dist: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.html)



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
open fun [getDestinationLocation](get-destination-location.html)(start: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), end: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.html), dist: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLongPosition](../../it.unibo.alchemist.model.implementations.positions/-lat-long-position/index.html)



#### Return



the actual destination



## Parameters


jvm

| | |
|---|---|
| start | initial position |
| end | final position |
| dist | maximum walkable length |





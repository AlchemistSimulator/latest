---
title: DigitalPanManager
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interactions](../index.html)/[DigitalPanManager](index.html)/[DigitalPanManager](-digital-pan-manager.html)



# DigitalPanManager



[jvm]\
fun <[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>> [DigitalPanManager](-digital-pan-manager.html)(speed: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 5, period: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 15, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](index.html)>, updates: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))



## Parameters


jvm

| | |
|---|---|
| speed | The speed of each movement. |
| period | Amount of time (milliseconds) between each movement. |
| wormhole | The wormhole used to pan. |
| updates | A runnable which will be called whenever a panning movement occurs. |





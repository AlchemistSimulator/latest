---
title: DigitalPanManager
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interactions](../index.html)/[DigitalPanManager](index.html)



# DigitalPanManager



[jvm]\
class [DigitalPanManager](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>>(**speed**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **period**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **wormhole**: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](index.html)>, **updates**: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

Manages panning towards a cardinal (N, S, E, W) or intercardinal (NE, NW, SE, SW) direction. When a direction is added, panning towards it begins and doesn't stop until the given direction is removed.



## Parameters


jvm

| | |
|---|---|
| speed | The speed of each movement. |
| period | Amount of time (milliseconds) between each movement. |
| wormhole | The wormhole used to pan. |
| updates | A runnable which will be called whenever a panning movement occurs. |



## Constructors


| | |
|---|---|
| [DigitalPanManager](-digital-pan-manager.html) | [jvm]<br>fun <[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>> [DigitalPanManager](-digital-pan-manager.html)(speed: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 5, period: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 15, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](index.html)>, updates: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>The speed of each movement. |


## Functions


| Name | Summary |
|---|---|
| [minusAssign](minus-assign.html) | [jvm]<br>operator fun [minusAssign](minus-assign.html)(direction: [Direction2D](../-direction2-d/index.html))<br>Stops moving towards a certain direction. |
| [plusAssign](plus-assign.html) | [jvm]<br>operator fun [plusAssign](plus-assign.html)(direction: [Direction2D](../-direction2-d/index.html))<br>Inputs a movement towards a certain direction. |


//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interactions](../index.md)/[DigitalPanManager](index.md)

# DigitalPanManager

[jvm]\
class [DigitalPanManager](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](index.md)>>(**speed**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **period**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), **wormhole**: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](index.md)>, **updates**: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))

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
| [DigitalPanManager](-digital-pan-manager.md) | [jvm]<br>fun <[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](index.md)>> [DigitalPanManager](-digital-pan-manager.md)(speed: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 5, period: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 15, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](index.md)>, updates: () -> [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>The speed of each movement. |

## Functions

| Name | Summary |
|---|---|
| [minusAssign](minus-assign.md) | [jvm]<br>operator fun [minusAssign](minus-assign.md)(direction: [Direction2D](../-direction2-d/index.md))<br>Stops moving towards a certain direction. |
| [plusAssign](plus-assign.md) | [jvm]<br>operator fun [plusAssign](plus-assign.md)(direction: [Direction2D](../-direction2-d/index.md))<br>Inputs a movement towards a certain direction. |

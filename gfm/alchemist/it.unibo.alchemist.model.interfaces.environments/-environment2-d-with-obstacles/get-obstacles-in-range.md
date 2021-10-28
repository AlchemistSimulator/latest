//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.environments](../index.md)/[Environment2DWithObstacles](index.md)/[getObstaclesInRange](get-obstacles-in-range.md)

# getObstaclesInRange

[jvm]\
abstract fun [getObstaclesInRange](get-obstacles-in-range.md)(center: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[W](index.md)>

Given a point and a range, retrieves all the obstacles within.

#### Return

the list of obstacles

## Parameters

jvm

| | |
|---|---|
| center | the center point |
| range | the range to scan |

[jvm]\
abstract fun [getObstaclesInRange](get-obstacles-in-range.md)(centerx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), centery: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[W](index.md)>

Given a point and a range, retrieves all the obstacles within.

#### Return

the list of Obstacles

## Parameters

jvm

| | |
|---|---|
| centerx | the x coordinate of the center |
| centery | the y coordinate of the center |
| range | the range to scan |

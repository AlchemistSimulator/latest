---
title: getObstaclesInRange
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.environments](../index.html)/[Environment2DWithObstacles](index.html)/[getObstaclesInRange](get-obstacles-in-range.html)



# getObstaclesInRange



[jvm]\
abstract fun [getObstaclesInRange](get-obstacles-in-range.html)(center: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[W](index.html)>



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
abstract fun [getObstaclesInRange](get-obstacles-in-range.html)(centerx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), centery: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[W](index.html)>



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





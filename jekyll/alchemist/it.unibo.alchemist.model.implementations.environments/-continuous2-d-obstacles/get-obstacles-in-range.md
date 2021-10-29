---
title: getObstaclesInRange
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.environments](../index.html)/[Continuous2DObstacles](index.html)/[getObstaclesInRange](get-obstacles-in-range.html)



# getObstaclesInRange



[jvm]\
fun [getObstaclesInRange](get-obstacles-in-range.html)(@NotNull()center: @NotNull()[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[RectObstacle2D](../../it.unibo.alchemist.model.implementations.obstacles/-rect-obstacle2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>



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




@NotNull()



fun [getObstaclesInRange](get-obstacles-in-range.html)(centerx: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), centery: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): @NotNull()[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[RectObstacle2D](../../it.unibo.alchemist.model.implementations.obstacles/-rect-obstacle2-d/index.html)<[Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>



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





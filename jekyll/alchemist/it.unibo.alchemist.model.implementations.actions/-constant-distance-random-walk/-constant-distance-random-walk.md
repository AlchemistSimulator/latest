---
title: ConstantDistanceRandomWalk
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions](../index.html)/[ConstantDistanceRandomWalk](index.html)/[ConstantDistanceRandomWalk](-constant-distance-random-walk.html)



# ConstantDistanceRandomWalk



[jvm]\
fun <[T](index.html)> [ConstantDistanceRandomWalk](-constant-distance-random-walk.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, reaction: [Reaction](../../it.unibo.alchemist.model.interfaces/-reaction/index.html)<[T](index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, randomGenerator: RandomGenerator, distance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), speed: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



## Parameters


jvm

| | |
|---|---|
|  | <T> concentration type |
| environment | environment containing the node |
| node | the node to move |
| reaction | the reaction containing this action |
| randomGenerator | random number generator to use for the decisions |
| distance | the distance to travel before picking another one |
| speed | the speed |





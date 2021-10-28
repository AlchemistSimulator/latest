---
title: pickNearestOrFirst
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](index.html)/[pickNearestOrFirst](pick-nearest-or-first.html)



# pickNearestOrFirst



[jvm]\
fun <[T](pick-nearest-or-first.html)> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](pick-nearest-or-first.html), [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>.[pickNearestOrFirst](pick-nearest-or-first.html)(env: [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](pick-nearest-or-first.html), [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, pedestrian: [Pedestrian2D](../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](pick-nearest-or-first.html)>): [SteeringAction](../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](pick-nearest-or-first.html), [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>?



Picks the [SteeringActionWithTarget](../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.html) whose target is nearest to the [pedestrian](pick-nearest-or-first.html)'s current position, or the first action of the list if none of them has a defined target. If the list is empty, null is returned.





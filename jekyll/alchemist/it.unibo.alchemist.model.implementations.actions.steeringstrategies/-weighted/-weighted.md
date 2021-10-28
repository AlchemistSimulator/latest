---
title: Weighted
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.html)/[Weighted](index.html)/[Weighted](-weighted.html)



# Weighted



[jvm]\
fun <[T](index.html)> [Weighted](-weighted.html)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.html)<[T](index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, weight: [SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>.() -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))



## Parameters


jvm

| | |
|---|---|
| environment | the environment in which the pedestrian moves. |
| pedestrian | the owner of the steering actions combined by this strategy. |
| weight | lambda used to assign a weight to each steering action: the higher the weight, the greater the     importance of the action. |





---
title: SteeringBehavior
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.reactions](../index.html)/[SteeringBehavior](index.html)/[SteeringBehavior](-steering-behavior.html)



# SteeringBehavior



[jvm]\
fun <[T](index.html)> [SteeringBehavior](-steering-behavior.html)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.html)<[T](index.html)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.html)<[T](index.html)>, steerStrategy: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>)



## Parameters


jvm

| | |
|---|---|
| env | the environment inside which the pedestrian moves. |
| pedestrian | the owner of this reaction. |
| timeDistribution | the time distribution according to which this reaction executes. |
| steerStrategy | the strategy used to combine steering actions. |





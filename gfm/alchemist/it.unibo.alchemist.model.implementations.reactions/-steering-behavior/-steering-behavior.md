//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.reactions](../index.md)/[SteeringBehavior](index.md)/[SteeringBehavior](-steering-behavior.md)

# SteeringBehavior

[jvm]\
fun <[T](index.md)> [SteeringBehavior](-steering-behavior.md)(env: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, timeDistribution: [TimeDistribution](../../it.unibo.alchemist.model.interfaces/-time-distribution/index.md)<[T](index.md)>, steerStrategy: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>)

## Parameters

jvm

| | |
|---|---|
| env | the environment inside which the pedestrian moves. |
| pedestrian | the owner of this reaction. |
| timeDistribution | the time distribution according to which this reaction executes. |
| steerStrategy | the strategy used to combine steering actions. |

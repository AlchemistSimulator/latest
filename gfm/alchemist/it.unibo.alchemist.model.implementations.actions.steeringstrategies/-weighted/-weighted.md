//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.md)/[Weighted](index.md)/[Weighted](-weighted.md)

# Weighted

[jvm]\
fun <[T](index.md)> [Weighted](-weighted.md)(environment: [Euclidean2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-euclidean2-d-environment/index.md)<[T](index.md)>, pedestrian: [Pedestrian2D](../../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](index.md)>, weight: [SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>.() -> [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html))

## Parameters

jvm

| | |
|---|---|
| environment | the environment in which the pedestrian moves. |
| pedestrian | the owner of the steering actions combined by this strategy. |
| weight | lambda used to assign a weight to each steering action: the higher the weight, the greater the     importance of the action. |

//[alchemist](../../index.md)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](index.md)/[pickNearestOrFirst](pick-nearest-or-first.md)

# pickNearestOrFirst

[jvm]\
fun <[T](pick-nearest-or-first.md)> [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](pick-nearest-or-first.md), [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>.[pickNearestOrFirst](pick-nearest-or-first.md)(env: [Environment](../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](pick-nearest-or-first.md), [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>, pedestrian: [Pedestrian2D](../it.unibo.alchemist.model.interfaces/-pedestrian2-d/index.md)<[T](pick-nearest-or-first.md)>): [SteeringAction](../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](pick-nearest-or-first.md), [Euclidean2DPosition](../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>?

Picks the [SteeringActionWithTarget](../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.md) whose target is nearest to the [pedestrian](pick-nearest-or-first.md)'s current position, or the first action of the list if none of them has a defined target. If the list is empty, null is returned.

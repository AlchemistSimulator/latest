//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.md)/[Weighted](index.md)/[computeNextPosition](compute-next-position.md)

# computeNextPosition

[jvm]\
open override fun [computeNextPosition](compute-next-position.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)

[actions](compute-next-position.md) are partitioned in group steering actions and non-group steering actions. The overall next position for each of these two sets of actions is computed via weighted sum. The resulting vectors are then summed together (with unitary weight).

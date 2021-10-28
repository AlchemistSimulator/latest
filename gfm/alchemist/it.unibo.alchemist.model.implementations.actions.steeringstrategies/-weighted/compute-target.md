//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.steeringstrategies](../index.md)/[Weighted](index.md)/[computeTarget](compute-target.md)

# computeTarget

[jvm]\
open override fun [computeTarget](compute-target.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)

If there's no [SteeringActionWithTarget](../../it.unibo.alchemist.model.interfaces/-steering-action-with-target/index.md) among the provided [actions](compute-target.md), a zero vector is returned. Otherwise, the closest target is picked.

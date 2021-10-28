//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[PhysicalSteeringStrategy](index.md)/[computeNextPosition](compute-next-position.md)

# computeNextPosition

[jvm]\
abstract fun [computeNextPosition](compute-next-position.md)(overallIntentionalForce: [P](index.md)): [P](index.md)

Computes the next relative position reached by the node, given the overall intentional force.

[jvm]\
open override fun [computeNextPosition](compute-next-position.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../-steering-action/index.md)<[T](index.md), [P](index.md)>>): [P](index.md)

Computes the next relative position reached by the node, taking into account both the intentional and the physical forces acting on [node](node.md) (intentional forces = [actions](compute-next-position.md)).

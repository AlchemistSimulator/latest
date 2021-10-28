//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces](../index.md)/[PhysicalSteeringStrategy](index.md)

# PhysicalSteeringStrategy

[jvm]\
interface [PhysicalSteeringStrategy](index.md)<[T](index.md), [P](index.md) : [Position](../-position/index.md)<[P](index.md)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](index.md)>, [A](index.md) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.md)<[P](index.md)>, [F](index.md) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.md)<[P](index.md), [A](index.md)>> : [SteeringStrategy](../-steering-strategy/index.md)<[T](index.md), [P](index.md)> 

Defines how physical forces and steering actions (which may be seen as intentional forces) are combined to compute the overall next position reached by a physical [node](node.md). The combination of steering actions is delegated to a [nonPhysicalStrategy](non-physical-strategy.md). The resulting intentional force is then combined with the physical ones to determine the next position reached by [node](node.md).

## Functions

| Name | Summary |
|---|---|
| [computeNextPosition](compute-next-position.md) | [jvm]<br>abstract fun [computeNextPosition](compute-next-position.md)(overallIntentionalForce: [P](index.md)): [P](index.md)<br>Computes the next relative position reached by the node, given the overall intentional force.<br>[jvm]<br>open override fun [computeNextPosition](compute-next-position.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../-steering-action/index.md)<[T](index.md), [P](index.md)>>): [P](index.md)<br>Computes the next relative position reached by the node, taking into account both the intentional and the physical forces acting on [node](node.md) (intentional forces = [actions](compute-next-position.md)). |
| [computeTarget](compute-target.md) | [jvm]<br>open override fun [computeTarget](compute-target.md)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../-steering-action/index.md)<[T](index.md), [P](index.md)>>): [P](index.md)<br>Delegated to [nonPhysicalStrategy](non-physical-strategy.md). |

## Properties

| Name | Summary |
|---|---|
| [node](node.md) | [jvm]<br>abstract val [node](node.md): [PhysicalNode](../-physical-node/index.md)<[T](index.md), [P](index.md), [A](index.md), [F](index.md)><br>The node to be moved. |
| [nonPhysicalStrategy](non-physical-strategy.md) | [jvm]<br>abstract val [nonPhysicalStrategy](non-physical-strategy.md): [SteeringStrategy](../-steering-strategy/index.md)<[T](index.md), [P](index.md)><br>The combination of intentional forces (= steering actions) and [computeTarget](compute-target.md) are delegated to this strategy. |

## Inheritors

| Name |
|---|
| [Sum](../../it.unibo.alchemist.model.implementations.actions.physicalstrategies/-sum/index.md) |

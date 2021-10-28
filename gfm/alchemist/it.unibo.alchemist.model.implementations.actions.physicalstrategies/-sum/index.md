//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.actions.physicalstrategies](../index.md)/[Sum](index.md)

# Sum

[jvm]\
class [Sum](index.md)<[T](index.md)>(**environment**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, **node**: [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.md)<[T](index.md)>, **nonPhysicalStrategy**: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) : [PhysicalSteeringStrategy](../../it.unibo.alchemist.model.interfaces/-physical-steering-strategy/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md), [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.md)> 

A [PhysicalSteeringStrategy](../../it.unibo.alchemist.model.interfaces/-physical-steering-strategy/index.md) performing a simple sum of the overall intentional force and the physical ones.

## Constructors

| | |
|---|---|
| [Sum](-sum.md) | [jvm]<br>fun <[T](index.md)> [Sum](-sum.md)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.md)<[T](index.md)>, node: [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.md)<[T](index.md)>, nonPhysicalStrategy: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>) |

## Functions

| Name | Summary |
|---|---|
| [computeNextPosition](compute-next-position.md) | [jvm]<br>open override fun [computeNextPosition](compute-next-position.md)(overallIntentionalForce: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>Computes the next relative position reached by the node, given the overall intentional force.<br>[jvm]<br>open override fun [computeNextPosition](index.md#-1302240437%2FFunctions%2F-267951372)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>Computes the next relative position reached by the node, taking into account both the intentional and the physical forces acting on [node](../../it.unibo.alchemist.model.interfaces/-physical-steering-strategy/node.md) (intentional forces = [actions](index.md#-1302240437%2FFunctions%2F-267951372)). |
| [computeTarget](index.md#-1551223200%2FFunctions%2F-267951372) | [jvm]<br>open override fun [computeTarget](index.md#-1551223200%2FFunctions%2F-267951372)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)<br>Delegated to [nonPhysicalStrategy](../../it.unibo.alchemist.model.interfaces/-physical-steering-strategy/non-physical-strategy.md). |

## Properties

| Name | Summary |
|---|---|
| [node](node.md) | [jvm]<br>open override val [node](node.md): [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.md)<[T](index.md)><br>The node to be moved. |
| [nonPhysicalStrategy](non-physical-strategy.md) | [jvm]<br>open override val [nonPhysicalStrategy](non-physical-strategy.md): [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.md)<[T](index.md), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.md)><br>The combination of intentional forces (= steering actions) and computeTarget are delegated to this strategy. |

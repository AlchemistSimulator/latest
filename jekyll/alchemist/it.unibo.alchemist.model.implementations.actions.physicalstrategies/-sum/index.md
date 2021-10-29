---
title: Sum
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.actions.physicalstrategies](../index.html)/[Sum](index.html)



# Sum



[jvm]\
class [Sum](index.html)<[T](index.html)>(**environment**: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, **node**: [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.html)<[T](index.html)>, **nonPhysicalStrategy**: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>) : [PhysicalSteeringStrategy](../../it.unibo.alchemist.model.interfaces/-physical-steering-strategy/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html), [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html), [Euclidean2DShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-shape-factory/index.html)> 

A [PhysicalSteeringStrategy](../../it.unibo.alchemist.model.interfaces/-physical-steering-strategy/index.html) performing a simple sum of the overall intentional force and the physical ones.



## Constructors


| | |
|---|---|
| [Sum](-sum.html) | [jvm]<br>fun <[T](index.html)> [Sum](-sum.html)(environment: [Physics2DEnvironment](../../it.unibo.alchemist.model.interfaces.environments/-physics2-d-environment/index.html)<[T](index.html)>, node: [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.html)<[T](index.html)>, nonPhysicalStrategy: [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>) |


## Functions


| Name | Summary |
|---|---|
| [computeNextPosition](compute-next-position.html) | [jvm]<br>open override fun [computeNextPosition](compute-next-position.html)(overallIntentionalForce: [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>Computes the next relative position reached by the node, given the overall intentional force.<br>[jvm]<br>open override fun [computeNextPosition](index.html#-1302240437%2FFunctions%2F-134779887)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>Computes the next relative position reached by the node, taking into account both the intentional and the physical forces acting on [node](../../it.unibo.alchemist.model.interfaces/-physical-steering-strategy/node.html) (intentional forces = [actions](index.html#-1302240437%2FFunctions%2F-134779887)). |
| [computeTarget](index.html#-1551223200%2FFunctions%2F-134779887) | [jvm]<br>open override fun [computeTarget](index.html#-1551223200%2FFunctions%2F-134779887)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../../it.unibo.alchemist.model.interfaces/-steering-action/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)>>): [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)<br>Delegated to [nonPhysicalStrategy](../../it.unibo.alchemist.model.interfaces/-physical-steering-strategy/non-physical-strategy.html). |


## Properties


| Name | Summary |
|---|---|
| [node](node.html) | [jvm]<br>open override val [node](node.html): [PhysicalPedestrian2D](../../it.unibo.alchemist.model.interfaces/-physical-pedestrian2-d/index.html)<[T](index.html)><br>The node to be moved. |
| [nonPhysicalStrategy](non-physical-strategy.html) | [jvm]<br>open override val [nonPhysicalStrategy](non-physical-strategy.html): [SteeringStrategy](../../it.unibo.alchemist.model.interfaces/-steering-strategy/index.html)<[T](index.html), [Euclidean2DPosition](../../it.unibo.alchemist.model.implementations.positions/-euclidean2-d-position/index.html)><br>The combination of intentional forces (= steering actions) and computeTarget are delegated to this strategy. |


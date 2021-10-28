---
title: PhysicalSteeringStrategy
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces](../index.html)/[PhysicalSteeringStrategy](index.html)



# PhysicalSteeringStrategy



[jvm]\
interface [PhysicalSteeringStrategy](index.html)<[T](index.html), [P](index.html) : [Position](../-position/index.html)<[P](index.html)>, [Vector](../../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](index.html)>, [A](index.html) : [GeometricTransformation](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-transformation/index.html)<[P](index.html)>, [F](index.html) : [GeometricShapeFactory](../../it.unibo.alchemist.model.interfaces.geometry/-geometric-shape-factory/index.html)<[P](index.html), [A](index.html)>> : [SteeringStrategy](../-steering-strategy/index.html)<[T](index.html), [P](index.html)> 

Defines how physical forces and steering actions (which may be seen as intentional forces) are combined to compute the overall next position reached by a physical [node](node.html). The combination of steering actions is delegated to a [nonPhysicalStrategy](non-physical-strategy.html). The resulting intentional force is then combined with the physical ones to determine the next position reached by [node](node.html).



## Functions


| Name | Summary |
|---|---|
| [computeNextPosition](compute-next-position.html) | [jvm]<br>abstract fun [computeNextPosition](compute-next-position.html)(overallIntentionalForce: [P](index.html)): [P](index.html)<br>Computes the next relative position reached by the node, given the overall intentional force.<br>[jvm]<br>open override fun [computeNextPosition](compute-next-position.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../-steering-action/index.html)<[T](index.html), [P](index.html)>>): [P](index.html)<br>Computes the next relative position reached by the node, taking into account both the intentional and the physical forces acting on [node](node.html) (intentional forces = [actions](compute-next-position.html)). |
| [computeTarget](compute-target.html) | [jvm]<br>open override fun [computeTarget](compute-target.html)(actions: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SteeringAction](../-steering-action/index.html)<[T](index.html), [P](index.html)>>): [P](index.html)<br>Delegated to [nonPhysicalStrategy](non-physical-strategy.html). |


## Properties


| Name | Summary |
|---|---|
| [node](node.html) | [jvm]<br>abstract val [node](node.html): [PhysicalNode](../-physical-node/index.html)<[T](index.html), [P](index.html), [A](index.html), [F](index.html)><br>The node to be moved. |
| [nonPhysicalStrategy](non-physical-strategy.html) | [jvm]<br>abstract val [nonPhysicalStrategy](non-physical-strategy.html): [SteeringStrategy](../-steering-strategy/index.html)<[T](index.html), [P](index.html)><br>The combination of intentional forces (= steering actions) and [computeTarget](compute-target.html) are delegated to this strategy. |


## Inheritors


| Name |
|---|
| [Sum](../../it.unibo.alchemist.model.implementations.actions.physicalstrategies/-sum/index.html) |


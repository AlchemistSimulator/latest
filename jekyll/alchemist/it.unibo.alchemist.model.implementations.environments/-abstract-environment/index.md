---
title: AbstractEnvironment
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.environments](../index.html)/[AbstractEnvironment](index.html)



# AbstractEnvironment



[jvm]\
abstract class [AbstractEnvironment](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>?> : [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> 

Very generic and basic implementation for an environment. Basically, only manages an internal set of nodes and their position.



## Parameters


jvm

| | |
|---|---|
| <T> | concentration type |
| <P> | [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html) type |



## Functions


| Name | Summary |
|---|---|
| [addLayer](add-layer.html) | [jvm]<br>fun [addLayer](add-layer.html)(m: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html), l: [Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>) |
| [addNode](add-node.html) | [jvm]<br>fun [addNode](add-node.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, p: [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)) |
| [addTerminator](add-terminator.html) | [jvm]<br>fun [addTerminator](add-terminator.html)(terminator: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<[Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>>) |
| [forEach](for-each.html) | [jvm]<br>fun [forEach](for-each.html)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getDimensions](../../it.unibo.alchemist.model.interfaces/-environment/get-dimensions.html) | [jvm]<br>abstract fun [getDimensions](../../it.unibo.alchemist.model.interfaces/-environment/get-dimensions.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDistanceBetweenNodes](get-distance-between-nodes.html) | [jvm]<br>fun [getDistanceBetweenNodes](get-distance-between-nodes.html)(n1: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, n2: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getIncarnation](../../it.unibo.alchemist.model.interfaces/-environment/get-incarnation.html) | [jvm]<br>abstract fun [getIncarnation](../../it.unibo.alchemist.model.interfaces/-environment/get-incarnation.html)(): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Incarnation](../../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>> |
| [getLayer](get-layer.html) | [jvm]<br>fun [getLayer](get-layer.html)(m: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>> |
| [getLayers](../../it.unibo.alchemist.model.interfaces/-environment/get-layers.html) | [jvm]<br>abstract fun [getLayers](../../it.unibo.alchemist.model.interfaces/-environment/get-layers.html)(): ListSet<[Layer](../../it.unibo.alchemist.model.interfaces/-layer/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>> |
| [getLinkingRule](get-linking-rule.html) | [jvm]<br>fun [getLinkingRule](get-linking-rule.html)(): [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [getNeighborhood](get-neighborhood.html) | [jvm]<br>fun [getNeighborhood](get-neighborhood.html)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [getNodeByID](get-node-by-i-d.html) | [jvm]<br>fun [getNodeByID](get-node-by-i-d.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [getNodeCount](get-node-count.html) | [jvm]<br>fun [getNodeCount](get-node-count.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getNodes](../../it.unibo.alchemist.model.interfaces/-environment/get-nodes.html) | [jvm]<br>abstract fun [getNodes](../../it.unibo.alchemist.model.interfaces/-environment/get-nodes.html)(): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>> |
| [getNodesWithinRange](get-nodes-within-range.html) | [jvm]<br>fun [getNodesWithinRange](get-nodes-within-range.html)(center: [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>><br>fun [getNodesWithinRange](get-nodes-within-range.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, range: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>> |
| [getOffset](../../it.unibo.alchemist.model.interfaces/-environment/get-offset.html) | [jvm]<br>abstract fun [getOffset](../../it.unibo.alchemist.model.interfaces/-environment/get-offset.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getPosition](get-position.html) | [jvm]<br>open fun [getPosition](get-position.html)(node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>): [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)<br>This method should not get overridden in general. |
| [getSimulation](../../it.unibo.alchemist.model.interfaces/-environment/get-simulation.html) | [jvm]<br>abstract fun [getSimulation](../../it.unibo.alchemist.model.interfaces/-environment/get-simulation.html)(): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |
| [getSize](../../it.unibo.alchemist.model.interfaces/-environment/get-size.html) | [jvm]<br>abstract fun [getSize](../../it.unibo.alchemist.model.interfaces/-environment/get-size.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)> |
| [getSizeInDistanceUnits](get-size-in-distance-units.html) | [jvm]<br>open fun [getSizeInDistanceUnits](get-size-in-distance-units.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)><br>Override this method if units measuring distance do not match with units used for coordinates. |
| [isTerminated](is-terminated.html) | [jvm]<br>fun [isTerminated](is-terminated.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [iterator](iterator.html) | [jvm]<br>fun [iterator](iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>> |
| [makePosition](../../it.unibo.alchemist.model.interfaces/-environment/make-position.html) | [jvm]<br>abstract fun [makePosition](../../it.unibo.alchemist.model.interfaces/-environment/make-position.html)(p: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)>): [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html) |
| [moveNodeToPosition](../../it.unibo.alchemist.model.interfaces/-environment/move-node-to-position.html) | [jvm]<br>abstract fun [moveNodeToPosition](../../it.unibo.alchemist.model.interfaces/-environment/move-node-to-position.html)(p: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>, p1: [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)) |
| [removeNode](remove-node.html) | [jvm]<br>fun [removeNode](remove-node.html)(@[Nonnull](https://docs.oracle.com/javase/8/docs/api/javax/annotation/Nonnull.html)()node: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>) |
| [setLinkingRule](set-linking-rule.html) | [jvm]<br>fun [setLinkingRule](set-linking-rule.html)(r: [LinkingRule](../../it.unibo.alchemist.model.interfaces/-linking-rule/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>) |
| [setSimulation](../../it.unibo.alchemist.model.interfaces/-environment/set-simulation.html) | [jvm]<br>abstract fun [setSimulation](../../it.unibo.alchemist.model.interfaces/-environment/set-simulation.html)(p: [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>) |
| [spliterator](spliterator.html) | [jvm]<br>fun [spliterator](spliterator.html)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>> |
| [toString](to-string.html) | [jvm]<br>open fun [toString](to-string.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Not used internally. |


## Properties


| Name | Summary |
|---|---|
| [nodes](nodes.html) | [jvm]<br>private val [nodes](nodes.html): ListSet<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)>> |
| [simulation](simulation.html) | [jvm]<br>private open var [simulation](simulation.html): [Simulation](../../it.unibo.alchemist.core.interfaces/-simulation/index.html)<[T](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html), [P](../../it.unibo.alchemist.model.implementations.layers/-uniform-layer/index.html)> |


## Inheritors


| Name |
|---|
| [Abstract2DEnvironment](../-abstract2-d-environment/index.html) |

